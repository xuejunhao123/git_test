---
title: Markdown 链接语法
updated: 2024-12-26 08:39:18Z
created: 2024-12-26 08:35:16Z
source: https://markdown.com.cn/basic-syntax/links.html
---

# [#](#markdown-链接语法) Markdown 链接语法

链接文本放在中括号内，链接地址放在后面的括号中，链接title可选。

超链接Markdown语法代码：`[超链接显示名](https://markdown.com.cn/basic-syntax/超链接地址 "超链接title")`

对应的HTML代码：`<a href="超链接地址" title="超链接title">超链接显示名</a>`

```text
这是一个链接 [Markdown语法](https://markdown.com.cn)。
```

渲染效果如下：

这是一个链接 [Markdown语法 (opens new window)](https://markdown.com.cn)。

### [#](#给链接增加-title) 给链接增加 Title

链接title是当鼠标悬停在链接上时会出现的文字，这个title是可选的，它放在圆括号中链接地址后面，跟链接地址之间以空格分隔。

```text
这是一个链接 [Markdown语法](https://markdown.com.cn "最好的markdown教程")。
```

渲染效果如下：

这是一个链接 [Markdown语法 (opens new window)](https://markdown.com.cn "最好的markdown教程")。

### [#](#网址和email地址) 网址和Email地址

使用尖括号可以很方便地把URL或者email地址变成可点击的链接。

```text
<https://markdown.com.cn>
<fake@example.com>
```

渲染效果如下：

[https://markdown.com.cn (opens new window)](https://markdown.com.cn)  
[fake@example.com](mailto:fake@example.com)

### [#](#带格式化的链接) 带格式化的链接

[强调](#emphasis) 链接, 在链接语法前后增加星号。 要将链接表示为代码，请在方括号中添加反引号。

```text
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).
```

渲染效果如下：

I love supporting the **[EFF (opens new window)](https://eff.org)**.  
This is the *[Markdown Guide (opens new window)](https://www.markdownguide.org)*.  
See the section on [`code`](#code).

### [#](#引用类型链接) 引用类型链接

引用样式链接是一种特殊的链接，它使URL在Markdown中更易于显示和阅读。参考样式链接分为两部分：与文本保持内联的部分以及存储在文件中其他位置的部分，以使文本易于阅读。

#### [#](#链接的第一部分格式) 链接的第一部分格式

引用类型的链接的第一部分使用两组括号进行格式设置。第一组方括号包围应显示为链接的文本。第二组括号显示了一个标签，该标签用于指向您存储在文档其他位置的链接。

尽管不是必需的，可以在第一组和第二组括号之间包含一个空格。第二组括号中的标签不区分大小写，可以包含字母，数字，空格或标点符号。

以下示例格式对于链接的第一部分效果相同：

- `[hobbit-hole][1]`
- `[hobbit-hole] [1]`

#### [#](#链接的第二部分格式) 链接的第二部分格式

引用类型链接的第二部分使用以下属性设置格式：

1.  放在括号中的标签，其后紧跟一个冒号和至少一个空格（例如`[label]:`）。
2.  链接的URL，可以选择将其括在尖括号中。
3.  链接的可选标题，可以将其括在双引号，单引号或括号中。

以下示例格式对于链接的第二部分效果相同：

- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)`

可以将链接的第二部分放在Markdown文档中的任何位置。有些人将它们放在出现的段落之后，有些人则将它们放在文档的末尾（例如尾注或脚注）。

### [#](#链接最佳实践) 链接最佳实践

不同的 Markdown 应用程序处理URL中间的空格方式不一样。为了兼容性，请尽量使用%20代替空格。

| ✅  Do this | ❌  Don't do this |
| --- | --- |
| `[link](https://www.example.com/my%20great%20page)` | `[link](https://www.example.com/my great page)` |

[Markdown 图片语法](https://markdown.com.cn/basic-syntax/images.html) →