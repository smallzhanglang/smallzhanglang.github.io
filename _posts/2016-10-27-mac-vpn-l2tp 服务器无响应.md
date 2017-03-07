---
title: MAC VPN 连接 L2TP 报错:VPN服务器没有响应
---

## 解决方案:

在`/etc/ppp`目录下新建`options`文件

``` bash
sudo vim /etc/ppp/options
```

在`options`文件中输入:

``` bash
plugin L2TP.ppp
l2tpnoipsec
```

然后保存退出，问题就能解决了，快去试试吧~
