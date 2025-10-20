# Markdown Syntax Guide

This guide covers all the common Markdown syntax elements you can use to format your documents.

## Headers

You can create headers using the `#` symbol. The number of `#` determines the header level:

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

## Emphasis

*This text is italicized* or _this too_
**This text is bold** or __this too__
***This text is bold and italic*** or ___this too___
~~This text is strikethrough~~

## Lists

### Unordered Lists
* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
- Another item
+ Yet another item

### Ordered Lists
1. First item
2. Second item
3. Third item
   1. Subitem 3.1
   2. Subitem 3.2

## Links

[Visit GitHub](https://github.com)
[Link with Title](https://github.com "GitHub's Homepage")
<https://github.com> <!-- Auto-links -->

## Images

![Alt text for image](https://github.com/github-mark.png "GitHub Logo")

## Blockquotes

> This is a blockquote
> 
> It can span multiple lines
>> And can be nested

## Code

### Inline Code
Use `backticks` for inline code

### Code Blocks
```python
def hello_world():
    print("Hello, World!")
```

```javascript
function greeting(name) {
    console.log(`Hello, ${name}!`);
}
```

## Tables

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Data     | Data     |
| Row 2    | Data     | Data     |

## Horizontal Rules

---
or
***
or
___

## Task Lists

- [x] Completed task
- [ ] Uncompleted task
- [ ] Another task

## Footnotes

Here's a sentence with a footnote[^1].

[^1]: This is the footnote content.

## Escaping Characters

\* This asterisk is escaped
\# This hashtag is escaped
\[ These brackets are escaped \]

## Comments

[//]: # (This is a comment that won't appear in the output)

## Collapsible Sections

<details>
<summary>Click to expand!</summary>

This content is hidden by default but can be revealed by clicking.
</details>

## Line Breaks

To create a line break, end a line with two or more spaces  
Like this.

Or use a blank line between paragraphs.

## URLs and Email Links

<example@example.com>

## Definition Lists

Term
: Definition

## Subscript and Superscript

H~2~O (subscript)
X^2^ (superscript)

---

Remember:
- Always preview your Markdown to ensure proper formatting
- Different Markdown processors might support different features
- Some platforms may have additional or custom syntax
