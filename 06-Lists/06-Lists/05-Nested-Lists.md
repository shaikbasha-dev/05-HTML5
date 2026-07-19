# Nested Lists in HTML

## Introduction

A Nested List in HTML is a list placed inside another list. Nested lists are used to represent hierarchical relationships between items, where a parent item contains one or more child items.

HTML allows both ordered and unordered lists to be nested within each other, making it possible to organize complex information in a clear and structured manner.

Nested lists are commonly used in navigation menus, website categories, organizational charts, file systems, product categories, documentation, and educational content.

---

# Definition

A Nested List is a list that is placed inside a list item (`<li>`) of another list.

Nested lists help represent parent-child relationships between data.

---

# Syntax

```html
<ul>

    <li>Parent Item

        <ul>

            <li>Child Item 1</li>

            <li>Child Item 2</li>

        </ul>

    </li>

</ul>
```

---

# Basic Example

```html
<ul>

    <li>Frontend

        <ul>

            <li>HTML</li>

            <li>CSS</li>

            <li>JavaScript</li>

        </ul>

    </li>

    <li>Backend</li>

</ul>
```

Output:

- Frontend
  - HTML
  - CSS
  - JavaScript
- Backend

---

# Nested Ordered List

An ordered list can contain another ordered list.

Example:

```html
<ol>

    <li>Semester 1

        <ol>

            <li>Mathematics</li>

            <li>Physics</li>

        </ol>

    </li>

    <li>Semester 2</li>

</ol>
```

---

# Mixed Nested Lists

HTML also allows mixing ordered and unordered lists.

Example:

```html
<ol>

    <li>Java Full Stack

        <ul>

            <li>Core Java</li>

            <li>Advanced Java</li>

            <li>Spring Boot</li>

        </ul>

    </li>

    <li>Projects</li>

</ol>
```

---

# Multi-Level Nested Lists

Nested lists can have multiple levels.

Example:

```html
<ul>

    <li>Programming

        <ul>

            <li>Java

                <ul>

                    <li>Collections</li>

                    <li>JDBC</li>

                </ul>

            </li>

            <li>Python</li>

        </ul>

    </li>

</ul>
```

---

# Complete Example

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <title>Nested Lists</title>

</head>

<body>

    <h1>HTML Nested Lists</h1>

    <ul>

        <li>Frontend

            <ul>

                <li>HTML5</li>

                <li>CSS3</li>

                <li>JavaScript</li>

            </ul>

        </li>

        <li>Backend

            <ul>

                <li>Java

                    <ul>

                        <li>Core Java</li>

                        <li>JDBC</li>

                        <li>Spring Boot</li>

                    </ul>

                </li>

                <li>Python</li>

            </ul>

        </li>

        <li>Database

            <ul>

                <li>Oracle SQL</li>

                <li>MySQL</li>

            </ul>

        </li>

    </ul>

</body>

</html>
```

---

# Real-World Applications

Nested lists are commonly used in:

- Website navigation menus
- Course syllabus
- Product categories
- Organization charts
- File and folder structures
- Documentation indexes
- E-commerce category menus
- Knowledge bases
- Table of contents
- Learning roadmaps

---

# Advantages

- Represents hierarchical information.
- Improves readability.
- Supports semantic HTML.
- Organizes complex data.
- Easy to maintain.
- Enhances user navigation.

---

# Best Practices

- Maintain proper indentation.
- Place nested lists inside `<li>` elements.
- Avoid excessive nesting.
- Use meaningful parent-child relationships.
- Choose ordered or unordered lists appropriately.

---

# Common Mistakes

- Placing nested lists outside `<li>` elements.
- Excessive nesting levels.
- Mixing unrelated items.
- Poor indentation.
- Using nested lists for page layout instead of structured data.

---

# Interview Questions

### 1. What is a Nested List?

A Nested List is a list placed inside another list item to represent hierarchical information.

---

### 2. Can ordered and unordered lists be nested together?

Yes. HTML allows ordered and unordered lists to be nested in any combination.

---

### 3. Where should a nested list be placed?

A nested list should always be placed inside an `<li>` element of the parent list.

---

### 4. What are common uses of nested lists?

Nested lists are used for navigation menus, file structures, product categories, documentation, and course outlines.

---

### 5. Is there a limit to nesting levels?

HTML does not define a fixed limit, but excessive nesting should be avoided because it reduces readability and maintainability.

---

# Summary

Nested lists provide a structured way to display hierarchical information in HTML5. By placing one list inside another, developers can represent parent-child relationships clearly and semantically. Proper use of nested lists improves readability, organization, accessibility, and maintainability, making them an essential feature for modern web development.
