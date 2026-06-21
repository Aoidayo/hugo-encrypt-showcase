---
title: "局部加密"
date: 2026-06-21T09:00:00+08:00
draft: false
tags:
  - hugo
  - stack
---


## 标题1

### 标题2
xxxxxxxxxxxxxxx

### 标题3
xxxxxxxxxxxx


这里是局部加密，👇下面是加密内容。

{{< encrypt password="123" prompt="这里需要密码，密码是123" >}}
这里是需要加密的内容。

支持正常 Markdown：

### 小标题

## 标题1

### 标题2
xxxxxxxxxxxxxxx

### 标题3
xxxxxxxxxxxx


- 列表
- 图片
- 代码块
{{< /encrypt >}}