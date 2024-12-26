---
title: Markdown 图片语法
updated: 2024-12-26 08:39:22Z
created: 2024-12-26 08:35:19Z
source: https://markdown.com.cn/basic-syntax/images.html
---

# [#](#markdown-图片语法) Markdown 图片语法

要添加图像，请使用感叹号 (`!`), 然后在方括号增加替代文本，图片链接放在圆括号里，括号里的链接后可以增加一个可选的图片标题文本。

插入图片Markdown语法代码：`![图片alt](https://markdown.com.cn/basic-syntax/图片链接 "图片title")`。

对应的HTML代码：`<img src="图片链接" alt="图片alt" title="图片title">`

```text
![这是图片](https://markdown.com.cn/assets/img/philly-magic-garden.jpg "Magic Gardens")
```

渲染效果如下：

<img width="740" height="555" src="../_resources/philly-magic-garden.9c0b4415_d276ee8f5d6b4f38948ec.jpg"/>

### [#](#链接图片) 链接图片

给图片增加链接，请将图像的Markdown 括在方括号中，然后将链接添加在圆括号中。

```text
[![沙漠中的岩石图片](https://markdown.com.cn/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)
```

渲染效果如下：

 <img width="740" height="494" src="../_resources/shiprock.c3b9a023_9886ec2df33f4b9db6017a4bc163eed1.jpg"/> (opens new window)](https://markdown.com.cn)

[Markdown 转义字符语法](https://markdown.com.cn/basic-syntax/escaping-characters.html) →