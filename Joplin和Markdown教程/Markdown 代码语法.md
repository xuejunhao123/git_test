---
title: Markdown 代码语法
updated: 2024-12-26 08:39:10Z
created: 2024-12-26 08:35:06Z
source: https://markdown.com.cn/basic-syntax/code.html
---

# [#](#markdown-代码语法) Markdown 代码语法

要将单词或短语表示为代码，请将其包裹在反引号 (`` ` ``) 中。

| Markdown语法 | HTML | 预览效果 |
| --- | --- | --- |
| ``At the command prompt, type `nano`.`` | `At the command prompt, type <code>nano</code>.` | At the command prompt, type `nano`. |

### [#](#转义反引号) 转义反引号

如果你要表示为代码的单词或短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号(` `` `)中。

| Markdown语法 | HTML | 预览效果 |
| --- | --- | --- |
| ``` ``Use `code` in your Markdown file.`` ``` | ``<code>Use `code` in your Markdown file.</code>`` | ``Use `code` in your Markdown file.`` |

### [#](#代码块) 代码块

要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符。

```text
    &lt;html>
      &lt;head>
      &lt;/head>
    &lt;/html>
```

渲染效果如下：

```text
&lt;html>
  &lt;head>
  &lt;/head>
&lt;/html>
```

**Note:** 要创建不用缩进的代码块，请使用 [围栏式代码块（fenced code blocks）](https://markdown.com.cn/extended-syntax/fenced-code-blocks.html).

[Markdown 分隔线语法](https://markdown.com.cn/basic-syntax/horizontal-rules.html) →