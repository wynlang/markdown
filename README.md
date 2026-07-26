# markdown - Official Wyn Package

Markdown to HTML helpers. Pure Wyn.

## Install

```bash
wyn pkg install github.com/wynlang/markdown
```

## Usage

```wyn
import markdown

var html = markdown.md_heading(1, "Hello") + markdown.md_bold("World")
print(html)   // <h1>Hello</h1><strong>World</strong>
```

## API

| Function | Description |
|----------|-------------|
| `md_heading(level, text)` | `<hN>text</hN>` |
| `md_bold(text)` | `<strong>text</strong>` |
| `md_italic(text)` | `<em>text</em>` |
| `md_link(text, url)` | `<a href="url">text</a>` |
| `md_code(text)` | `<code>text</code>` |
| `md_list_item(text)` | `<li>text</li>` |
| `md_paragraph(text)` | `<p>text</p>` |
