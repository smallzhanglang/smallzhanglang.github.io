---
title: 自动格式化成类似于Sublime Text's Alignment Plugin的效果
date: 2016-11-01 22:49:51
tags: WebStorm Sublime Plugin Auto-formatting
---

> 写出美感的代码

要实现如下格式的代码块：

```
user : {
  name      : "Bruce Wayne",
  alias     : "Batman",
  favColour : "black",
  dob       : "unknown"
}
```

## 解决方法: 

* `Webstorm` -> `Settings (Preferences on Mac)` -> `Code Style` -> `JavaScript`

* `"Spaces" tab` -> `Other` -> `Before property name-value separator ':'` 勾选此选项

* `"Other" tab` -> `Align object properties = On colon`

* `"Other" tab` -> `Align 'var' statements and assignments` 设置成 `Align multiple 'var' statements and assignments`

