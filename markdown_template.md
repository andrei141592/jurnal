# Markdown Complete Template

> This file demonstrates **most commonly used Markdown syntax** as supported by CommonMark + GitHub Flavored Markdown (GFM).

---

## Headings

# H1

## H2

### H3

#### H4

##### H5

###### H6

---

## Text Formatting

*Italic* or *Italic*

**Bold** or **Bold**

***Bold Italic***

~~Strikethrough~~

<u>Underline (HTML)</u>

---

## Paragraphs & Line Breaks

This is a paragraph.

This is another paragraph.
Line break using two spaces at the end of the line.
Like this.

---

## Blockquotes

> Single line blockquote

> Multi-line blockquote
> continues here
>
> > Nested blockquote

---

## Lists

### Unordered List

* Item A
* Item B

  * Subitem B1
  * Subitem B2

    * Sub-subitem

### Ordered List

1. First
2. Second
3. Third

   1. Nested First
   2. Nested Second

### Task List (GFM)

* [x] Completed task
* [ ] Incomplete task

---

## Links

Inline link: [OpenAI](https://openai.com)

Reference link: [Markdown Guide][md]

[md]: https://www.markdownguide.org

---

## Images

Inline image:

![Alt text](https://via.placeholder.com/150)

Reference image:

![Alt text][img]

[img]: https://via.placeholder.com/300

---

## Code

### Inline Code

Use `inline code` in a sentence.

### Code Block

```
Generic code block
```

### Syntax Highlighting

```python
def hello():
    print("Hello, Markdown")
```

---

## Tables (GFM)

| Column A | Column B | Column C |
| -------: | :------: | :------- |
|    Right |  Center  | Left     |
|      123 |    456   | 789      |

---

## Horizontal Rule

---

---

---

---

## Escaping Characters

* _ # - + ! `

---

## Footnotes (Extended Markdown)

Here is a sentence with a footnote.[^1]

[^1]: This is the footnote text.

---

## Definition Lists (Extended)

Term 1
: Definition 1

Term 2
: Definition 2

---

## Emojis (GFM)

:smile: :rocket: :warning:

---

## HTML Support

<div style="color:red">HTML block</div>

<span style="color:blue">Inline HTML</span>

---

## Collapsible Sections (GFM)

<details>
<summary>Click to expand</summary>

Hidden content here

</details>

---

## Automatic Links

[https://github.com](https://github.com)

---

## Comments (Not Rendered)

<!-- This is a Markdown comment -->

---

## Math (Platform Dependent)

Inline math: $E=mc^2$

Block math:

$$
\int_0^1 x^2 dx
$$

---

## End of Template

This template covers **nearly all Markdown features** used across popular renderers (GitHub, GitLab, Obsidian, VS Code, Pandoc).
