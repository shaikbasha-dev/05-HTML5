# Table Rows and Columns in HTML5

## Overview

Rows and columns form the fundamental structure of every HTML table. A table is created by arranging data into horizontal rows and vertical columns, making information easy to read, compare, and analyze.

In HTML5, rows are created using the `<tr>` element, while the data inside each row is represented using either `<th>` (table header cells) or `<td>` (table data cells).

Understanding how rows and columns work together is essential for creating organized, accessible, and professional HTML tables.

---

# What are Table Rows?

A table row is a horizontal group of cells within a table.

Each row is created using the `<tr>` (Table Row) element.

A row can contain:

- Header cells (`<th>`)
- Data cells (`<td>`)
- A combination of both (depending on the table design)

---

# What are Table Columns?

A table column is a vertical arrangement of related cells.

Unlike rows, HTML does not have a separate element to create columns.

Columns are automatically formed by placing cells in the same position across multiple rows.

---

# Basic Syntax

```html
<table>

    <tr>

        <th>ID</th>

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

# Understanding Rows

Example:

```html
<tr>

    <td>101</td>

    <td>Alice</td>

    <td>Java</td>

</tr>
```

This example creates one table row containing three data cells.

---

# Understanding Columns

Consider the following table:

```html
<table>

    <tr>

        <th>ID</th>

        <th>Name</th>

        <th>Course</th>

    </tr>

    <tr>

        <td>101</td>

        <td>Alice</td>

        <td>Java</td>

    </tr>

    <tr>

        <td>102</td>

        <td>Bob</td>

        <td>Python</td>

    </tr>

</table>
```

The table contains:

- **3 Rows**
  - Header Row
  - Student Row 1
  - Student Row 2

- **3 Columns**
  - ID
  - Name
  - Course

---

# Visual Representation

```text
+-----+---------+----------+
| ID  | Name    | Course   |
+-----+---------+----------+
|101  | Alice   | Java     |
+-----+---------+----------+
|102  | Bob     | Python   |
+-----+---------+----------+
```

Rows are horizontal.

Columns are vertical.

---

# Relationship Between Rows and Columns

| Component | Description |
|-----------|-------------|
| Row | Horizontal group of cells. |
| Column | Vertical group of related cells. |
| Cell | Intersection of a row and a column. |

---

# Creating Multiple Rows

Example:

```html
<table>

    <tr>
        <th>Employee ID</th>
        <th>Name</th>
    </tr>

    <tr>
        <td>201</td>
        <td>John</td>
    </tr>

    <tr>
        <td>202</td>
        <td>Mary</td>
    </tr>

    <tr>
        <td>203</td>
        <td>David</td>
    </tr>

</table>
```

---

# Creating Multiple Columns

Example:

```html
<table>

    <tr>
        <th>ID</th>
        <th>Name</th>
        <th>Department</th>
        <th>Salary</th>
    </tr>

    <tr>
        <td>301</td>
        <td>Rahul</td>
        <td>Development</td>
        <td>₹60,000</td>
    </tr>

</table>
```

The table contains four columns.

---

# Real-World Applications

Rows and columns are widely used in:

- Student information systems
- Employee management systems
- Banking applications
- Product catalogs
- Hospital records
- Attendance registers
- Examination results
- Financial statements
- Timetables
- Sales reports

---

# Advantages

Using rows and columns provides several benefits:

- Organizes structured information.
- Improves readability.
- Makes comparisons easier.
- Supports semantic HTML.
- Enhances accessibility.
- Simplifies CSS styling.
- Improves maintainability.

---

# Best Practices

Follow these recommendations:

- Keep the same number of columns in each row whenever possible.
- Use `<th>` for headings.
- Use meaningful column names.
- Align related information consistently.
- Use semantic table sections for larger tables.
- Keep table layouts simple and readable.

---

# Common Mistakes

Avoid the following mistakes:

- Creating inconsistent numbers of cells across rows.
- Using `<td>` instead of `<th>` for headers.
- Mixing unrelated data in the same row.
- Using tables for page layout.
- Forgetting proper indentation.

---

# Browser Support

HTML5 table rows and columns are fully supported by all modern browsers, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

---

# Summary

Rows and columns are the core building blocks of every HTML table. The `<tr>` element creates horizontal rows, while `<th>` and `<td>` define the cells that form vertical columns. Understanding how these elements interact enables developers to build clear, semantic, accessible, and well-organized tables for presenting structured information in modern HTML5 applications.
