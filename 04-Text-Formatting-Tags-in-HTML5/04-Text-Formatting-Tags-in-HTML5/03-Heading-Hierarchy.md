# HTML Heading Hierarchy

## Introduction

Heading hierarchy is the logical arrangement of HTML heading elements (`<h1>` to `<h6>`) according to their importance and relationship. A proper heading hierarchy creates a well-structured webpage that is easy for users, search engines, and assistive technologies to understand.

Rather than selecting heading levels based on their visual appearance, developers should use them to represent the structure and organization of content. Maintaining a correct hierarchy is one of the most important best practices in HTML5 development.

---

# Definition

**Heading Hierarchy** is the systematic organization of HTML heading elements from `<h1>` to `<h6>` to represent the structure and importance of webpage content.

---

# Heading Levels

HTML provides six heading levels:

| Heading | Importance | Typical Usage |
|----------|------------|---------------|
| `<h1>` | Highest | Main page title |
| `<h2>` | High | Major sections |
| `<h3>` | Medium | Subsections |
| `<h4>` | Lower | Topics within subsections |
| `<h5>` | Low | Detailed information |
| `<h6>` | Lowest | Minor notes or references |

---

# Visual Hierarchy

```text
H1
│
├── H2
│   ├── H3
│   │   ├── H4
│   │   │   ├── H5
│   │   │   │   └── H6
```

Each heading level represents a child section of the previous heading.

---

# Correct Heading Hierarchy

```html
<h1>HTML Tutorial</h1>

<h2>Introduction</h2>

<h3>What is HTML?</h3>

<h3>Features of HTML</h3>

<h2>HTML Elements</h2>

<h3>Headings</h3>

<h3>Paragraphs</h3>
```

This example follows a logical and meaningful structure.

---

# Incorrect Heading Hierarchy

```html
<h1>HTML Tutorial</h1>

<h4>Introduction</h4>

<h2>HTML Elements</h2>

<h6>Paragraphs</h6>
```

Problems:

- Skips heading levels.
- Creates an illogical document structure.
- Reduces accessibility.
- Makes navigation difficult.

---

# Practical Example

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <title>Heading Hierarchy</title>

</head>

<body>

    <h1>Web Development</h1>

    <h2>Frontend Development</h2>

    <h3>HTML5</h3>

    <h3>CSS3</h3>

    <h3>JavaScript</h3>

    <h2>Backend Development</h2>

    <h3>Java</h3>

    <h3>Spring Boot</h3>

</body>

</html>
```

---

# Why is Heading Hierarchy Important?

A proper heading hierarchy:

- Organizes webpage content logically.
- Improves readability.
- Enhances accessibility.
- Helps screen readers understand document structure.
- Improves Search Engine Optimization (SEO).
- Makes navigation easier.
- Supports semantic HTML.

---

# Advantages

- Creates a well-structured webpage.
- Improves user experience.
- Enhances accessibility.
- Improves SEO performance.
- Makes webpages easier to maintain.
- Encourages semantic coding practices.

---

# Best Practices

- Use only one `<h1>` for the primary page title.
- Follow heading levels sequentially.
- Do not skip heading levels unnecessarily.
- Use headings based on content structure, not appearance.
- Keep headings meaningful and concise.
- Maintain a consistent hierarchy throughout the webpage.

---

# Common Mistakes

- Using multiple `<h1>` elements without purpose.
- Skipping heading levels.
- Choosing headings based on font size.
- Using headings only for styling.
- Creating inconsistent document structure.

---

# Interview Questions

### 1. What is heading hierarchy?

Heading hierarchy is the logical arrangement of HTML headings from `<h1>` to `<h6>` based on content importance.

---

### 2. Why is heading hierarchy important?

It improves readability, accessibility, SEO, and overall webpage organization.

---

### 3. Can heading levels be skipped?

Although browsers will render skipped levels, it is considered a poor practice because it creates an illogical document structure.

---

### 4. How many `<h1>` elements should a webpage have?

Generally, a webpage should have one primary `<h1>` that represents the main title.

---

### 5. Should headings be selected based on font size?

No. Heading levels should represent the logical structure of content, not visual appearance.

---

# Summary

Heading hierarchy is a fundamental concept in HTML5 that organizes webpage content into meaningful sections. Using headings sequentially from `<h1>` to `<h6>` improves readability, accessibility, SEO, and semantic structure. Following a proper heading hierarchy is considered a professional HTML coding practice and is essential for creating accessible, maintainable, and standards-compliant webpages.
