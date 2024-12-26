---
title: Markdown 标题编号
updated: 2024-12-26 10:17:36Z
created: 2024-12-26 09:03:45Z
source: https://markdown.com.cn/extended-syntax/heading-ids.html
---

# [#](#markdown-标题编号) Markdown 标题编号

许多Markdown处理器支持[标题](https://markdown.com.cn/basic-syntax/headings.html)的自定义ID - 一些Markdown处理器会自动添加它们。添加自定义ID允许您直接链接到标题并使用CSS对其进行修改。要添加自定义标题ID，请在与标题相同的行上用大括号括起该自定义ID。

```text
### My Great Heading {#custom-id}
```

HTML看起来像这样：

```html
<h3 id="custom-id">My Great Heading</h3>
```

## [#](#链接到标题id-headid) 链接到标题ID (#headid)

通过创建带有数字符号（`#`）和自定义标题ID的\[标准链接\](https://markdown.com.cn/extended-syntax/(/basic-syntax/links.html)，可以链接到文件中具有自定义ID的标题。

| Markdown | HTML | 预览效果 |
| --- | --- | --- |
| `[Heading IDs](#heading-ids)` | `<a href="#heading-ids">Heading IDs</a>` | [Heading IDs](#heading-ids) |

其他网站可以通过将自定义标题ID添加到网页的完整URL（例如`[Heading IDs](https://markdown.com.cn/extended-syntax/heading-ids.html#headid)`）来链接到标题。

← [Markdown 脚注](https://markdown.com.cn/extended-syntax/footnotes.html) [Markdown 定义列表](https://markdown.com.cn/extended-syntax/definition-lists.html) →