---
description: Guide for writing Markdown documentation
---

# Markdown Style Guide

Markdown is an easy to use documentation format that can be used to write articles, documentation, and much more. 

## Headings

Headings are created by using the `#` symbol. The number of `#` symbols define the level of the heading.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## Lists

### Ordered Lists

Ordered lists are created by using numbers followed by a period. 

1. First item
2. Second item

```
1. First item
2. Second item
```

### Unordered Lists

Unordered lists are created by using asterisks (`*`), plus signs (`+`), or hyphens (`-`).

- First item
- Second item

```
- First item
- Second item
```

## Code Blocks

Code blocks are created by using triple backticks (` ``` `) before and after the code block. You can also specify the language for syntax highlighting.

```javascript
function helloWorld() {
  console.log("Hello, world!");
}
```