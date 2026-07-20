# Table Header Cells in HTML5

## Overview

Table header cells are used to define the headings of columns or rows within an HTML table. They provide labels that describe the data contained in the corresponding table cells, making tables easier to understand and navigate.

In HTML5, header cells are created using the `<th>` element. Unlike regular data cells (`<td>`), header cells have semantic meaning, which improves accessibility, readability, and search engine optimization.

Screen readers use header cells to help visually impaired users understand the relationship between table headings and table data.

---

# What are Table Header Cells?

A table header cell is a special type of table cell that describes the contents of a row or column.

Header cells are created using the `<th>` element.

Example:

```html
<th>Name</th>
```

The browser typically displays header cells in **bold** and **center-aligned** by default.

---

# Why Use Header Cells?

Using table header cells provides several benefits:

- Identifies the purpose of each column.
- Improves table readability.
- Enhances accessibility.
- Supports screen readers.
- Creates semantic HTML.
- Improves SEO.
- Makes large tables easier to understand.

---

# Basic Syntax

```html
<table>

    <tr>

        <th>ID</th>

        <th>Name</th>

        <th>Department</th>

    </tr>

</table>
```

---

# Basic Example

```html
<table>

    <tr>

        <th>Student ID</th>

        <th>Name</th>

        <th>Course</th>

    </tr>

    <tr>

        <td>101</td>

        <td>Alice</td>

        <td>Java</td>

    </tr>

</table>
```

---

# Difference Between `<th>` and `<td>`

| `<th>` | `<td>` |
|----------|----------|
| Defines a header cell. | Defines a data cell. |
| Usually displayed in bold. | Usually displayed in normal text. |
| Center aligned by default. | Left aligned by default. |
| Provides semantic meaning. | Displays actual data. |
| Improves accessibility. | Stores table values. |

---

# Column Headers

Column headers describe the information stored in each column.

Example:

```html
<tr>

    <th>ID</th>

    <th>Name</th>

    <th>Salary</th>

</tr>
```

---

# Row Headers

Header cells can also describe rows.

Example:

```html
<table>

    <tr>

        <th></th>

        <th>Quarter 1</th>

        <th>Quarter 2</th>

    </tr>

    <tr>

        <th>Sales</th>

        <td>₹50,000</td>

        <td>₹60,000</td>

    </tr>

</table>
```

---

# Using the `scope` Attribute

The `scope` attribute defines whether a header applies to a row or a column.

### Column Header

```html
<th scope="col">Name</th>
```

### Row Header

```html
<th scope="row">Employee</th>
```

### Common Values

| Value | Description |
|--------|-------------|
| `col` | Header applies to a column. |
| `row` | Header applies to a row. |
| `colgroup` | Header applies to a group of columns. |
| `rowgroup` | Header applies to a group of rows. |

Using the `scope` attribute improves accessibility for assistive technologies.

---

# Real-World Applications

Table header cells are commonly used in:

- Student records
- Employee databases
- Product catalogs
- Financial reports
- Timetables
- Hospital management systems
- Sales reports
- Banking applications
- Inventory management
- Examination results

---

# Advantages

Using `<th>` provides several benefits:

- Clearly labels table data.
- Improves accessibility.
- Enhances readability.
- Supports semantic HTML.
- Helps screen readers interpret tables.
- Makes tables easier to maintain.

---

# Best Practices

Follow these recommendations:

- Always use `<th>` for headings.
- Use meaningful header names.
- Apply the `scope` attribute when appropriate.
- Keep header text concise.
- Group related headers logically.
- Use CSS for styling instead of deprecated HTML attributes.

---

# Common Mistakes

Avoid the following mistakes:

- Using `<td>` for header cells.
- Leaving header cells blank unnecessarily.
- Using unclear or generic headings.
- Ignoring accessibility.
- Mixing header cells with unrelated data.

---

# Browser Support

The `<th>` element is fully supported by all modern browsers:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

---

# Summary

The HTML5 `<th>` element is used to create table header cells that describe the contents of rows and columns. Proper use of header cells improves readability, accessibility, semantic structure, and maintainability. By combining meaningful headings with the `scope` attribute and following HTML5 best practices, developers can build professional and user-friendly tables for modern web applications.
