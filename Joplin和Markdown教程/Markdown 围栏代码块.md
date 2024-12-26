---
title: Markdown 围栏代码块
updated: 2024-12-26 10:17:54Z
created: 2024-12-26 09:02:55Z
source: https://markdown.com.cn/extended-syntax/fenced-code-blocks.html
---

# [#](#markdown-围栏代码块) Markdown 围栏代码块

Markdown基本语法允许您通过将行缩进四个空格或一个制表符来创建[代码块](https://markdown.com.cn/basic-syntax/code-blocks.html)。如果发现不方便，请尝试使用受保护的代码块。根据Markdown处理器或编辑器的不同，您将在代码块之前和之后的行上使用三个反引号（(` ``` `）或三个波浪号（~~~）。

````text
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
````

呈现的输出如下所示：

```text
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

**Tip:**要在代码块中显示反引号？请参阅了解如何[转义](https://markdown.com.cn/basic-syntax/escaping-backticks.html)它们。

## [#](#语法高亮) 语法高亮

许多Markdown处理器都支持受围栏代码块的语法突出显示。使用此功能，您可以为编写代码的任何语言添加颜色突出显示。要添加语法突出显示，请在受防护的代码块之前的反引号旁边指定一种语言。

````text
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
````

呈现的输出如下所示：

{ "firstName": "John", "lastName": "Smith", "age": 25 }

← [Markdown 表格](https://markdown.com.cn/extended-syntax/tables.html) [Markdown 脚注](https://markdown.com.cn/extended-syntax/footnotes.html) →