# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading


**Code:**
```markdown
# H1
```

**Result:**
# H1

---
## H2

How to 
```markdown
# H2
```

### H3

How to 
```markdown
# H3
```

### Bold

**bold text**

How to 
```markdown
**bold text**
```

### Italic

*italicized text*

How to 
```markdown
*italicized text*

```
### Blockquote

> blockquote

How to 
```markdown
> blockquote

```

### Ordered List

1. First item
2. Second item
3. Third item

How to 
```markdown
1. First item
2. Second item
3. Third item
```

### Unordered List

- First item
- Second item
- Third item

How to 
```markdown
- First item
- Second item
- Third item
```

### Code

`code`


How to 
```markdown
`code`

```

### Horizontal Rule

---

How to 
```markdown
---

```

### Link

[title](https://www.example.com)

How to 
```markdown
[title](https://www.example.com)

```

### Image

![alt text](image.jpg)

How to 
```markdown
![alt text](image.jpg)

```

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

How to 
```markdown
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
```

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

How to 
```markdown
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

How to 
```markdown
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

```

### Heading ID

### My Great Heading {#custom-id}

How to 
```markdown
### My Great Heading {#custom-id}

```

### Definition List

term
: definition

How to 
```markdown
term
: definition
```

### Strikethrough

~~The world is flat.~~

How to 
```markdown
~~The world is flat.~~
```

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

How to 
```markdown
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```
