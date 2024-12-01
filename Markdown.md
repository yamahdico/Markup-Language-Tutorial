<div dir="rtl">
# Markdown Tutorial

Markdown is a lightweight and easy-to-use syntax for styling text. It’s commonly used for documentation, blogging, and writing in code repositories like **GitHub**. Here's a comprehensive tutorial.
</div>
---

## Basic Structure and Syntax of Markdown

### 1. **Headings**
Use the `#` symbol to create headings. The number of `#` determines the level of the heading (1 to 6 levels).

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

### Output:
# Heading 1  
## Heading 2  
### Heading 3  
#### Heading 4  
##### Heading 5  
###### Heading 6  

---

### 2. **Emphasis (Bold and Italic)**

- **Bold**: Use `**` or `__` to bold text.
- *Italic*: Use `*` or `_` to italicize text.
- ***Bold and Italic***: Combine both.

```markdown
**Bold Text**
*Italic Text*
***Bold and Italic Text***
```

### Output:
**Bold Text**  
*Italic Text*  
***Bold and Italic Text***

---

### 3. **Lists**

#### a) **Ordered Lists**:
Use numbers followed by a period for ordered lists.

```markdown
1. First item
2. Second item
3. Third item
```

#### b) **Unordered Lists**:
Use `-`, `+`, or `*` for unordered lists.

```markdown
- Item 1
- Item 2
  - Sub-item 2.1
  - Sub-item 2.2
- Item 3
```

### Output:
1. First item  
2. Second item  
3. Third item  

- Item 1  
- Item 2  
  - Sub-item 2.1  
  - Sub-item 2.2  
- Item 3  

---

### 4. **Links**

Create links using the syntax `[link text](URL)`.

```markdown
[Visit Google](https://www.google.com)
```

### Output:
[Visit Google](https://www.google.com)

---

### 5. **Images**

Insert images using the syntax `![alt text](image URL)`.

```markdown
![Markdown Logo](https://markdown-here.com/img/icon256.png)
```

### Output:
![Markdown Logo](https://markdown-here.com/img/icon256.png)

---

### 6. **Code and Code Blocks**

#### a) **Inline Code**:
Use backticks `` ` `` for inline code.

```markdown
Use `git status` to check the status.
```

#### b) **Code Block**:
Use triple backticks or tildes for multi-line code blocks. Specify the language for syntax highlighting.

```markdown
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
```

### Output:
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

---

### 7. **Tables**

Create tables using `|` and `-`.

```markdown
| Name    | Age | Country |
|---------|-----|---------|
| Alice   | 25  | USA     |
| Bob     | 30  | UK      |
| Charlie | 22  | Canada  |
```

### Output:

| Name    | Age | Country |
|---------|-----|---------|
| Alice   | 25  | USA     |
| Bob     | 30  | UK      |
| Charlie | 22  | Canada  |

---

### 8. **Blockquotes**

Use `>` for blockquotes.

```markdown
> This is a blockquote.
> You can write multiple lines.
```

### Output:
> This is a blockquote.  
> You can write multiple lines.

---

### 9. **Horizontal Rule**

Use `---`, `***`, or `___` for horizontal rules.

```markdown
---
```

### Output:
---

---

### 10. **Task Lists**

Create task lists using `- [ ]` for unchecked and `- [x]` for checked items.

```markdown
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```

### Output:
- [x] Task 1  
- [ ] Task 2  
- [ ] Task 3  

---

### 11. **HTML in Markdown**

You can also use HTML tags in Markdown.

```markdown
<p style="color: red;">This is a red text.</p>
```

### Output:
<p style="color: red;">This is a red text.</p>

---

Markdown is a powerful and easy tool for documentation. With this tutorial, you can format your content effectively.
