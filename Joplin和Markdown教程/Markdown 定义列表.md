---
title: Markdown 定义列表
updated: 2024-12-26 10:17:46Z
created: 2024-12-26 09:03:48Z
source: https://markdown.com.cn/extended-syntax/definition-lists.html
---

# [#](#markdown-定义列表) Markdown 定义列表

一些Markdown处理器允许您创建术语及其对应定义的*定义列表*。要创建定义列表，请在第一行上键入术语。在下一行，键入一个冒号，后跟一个空格和定义。

```text
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
```

HTML看起来像这样：

```html
<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>
```

呈现的输出如下所示：

First Term

This is the definition of the first term.

Second Term

This is one definition of the second term.

This is another definition of the second term.

← [Markdown 标题编号](https://markdown.com.cn/extended-syntax/heading-ids.html) [markdown 删除线](https://markdown.com.cn/extended-syntax/strikethrough.html) →