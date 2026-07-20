# Table Structure in HTML5

## Overview

The structure of an HTML table defines how data is organized into rows, columns, headers, and cells. A well-structured table improves readability, accessibility, maintainability, and helps browsers correctly interpret tabular information.

HTML5 provides several semantic elements that work together to create a complete table structure. Understanding these elements is essential for building professional and standards-compliant web pages.

---

# What is Table Structure?

Table structure refers to the arrangement of various HTML table elements that work together to display information in a tabular format.

A complete HTML table typically consists of:

- Table Container
- Table Caption
- Header Section
- Body Section
- Footer Section
- Rows
- Header Cells
- Data Cells

---

# Basic HTML Table Structure

```html
<table>

    <tr>

        <th>Name</th>

        <th>Age</th>

    </tr>

    <tr>

        <td>Rahul</td>

        <td>22</td>

    </tr>

</table>
```

---

# Semantic Table Structure

HTML5 recommends organizing tables using semantic elements.

```html
<table>

    <caption>Student Details</caption>

    <thead>

        <tr>

            <th>ID</th>

            <th>Name</th>

            <th>Course</th>

        </tr>

    </thead>

    <tbody>

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

    </tbody>

    <tfoot>

        <tr>

            <td colspan="3">
                Total Students: 2
            </td>

        </tr>

    </tfoot>

</table>
```

---

# HTML Table Elements

| Element | Purpose |
|----------|---------|
| `<table>` | Creates the main table container. |
| `<caption>` | Displays the title of the table. |
| `<thead>` | Groups header rows. |
| `<tbody>` | Groups the main table data. |
| `<tfoot>` | Groups footer rows. |
| `<tr>` | Defines a table row. |
| `<th>` | Defines a table header cell. |
| `<td>` | Defines a table data cell. |

---

# Hierarchy of Table Elements

```text
<table>

│
├── <caption>
│
├── <thead>
│      └── <tr>
│             └── <th>
│
├── <tbody>
│      └── <tr>
│             └── <td>
│
└── <tfoot>
       └── <tr>
              └── <td>
```

---

# Purpose of Each Element

### `<table>`

Acts as the parent container for the entire table.

---

### `<caption>`

Provides a meaningful title describing the table.

---

### `<thead>`

Contains column headings and improves accessibility.

---

### `<tbody>`

Stores the primary data of the table.

---

### `<tfoot>`

Contains summary information such as totals or remarks.

---

### `<tr>`

Represents one horizontal row.

---

### `<th>`

Represents a header cell.

By default, browsers display header text in bold and centered.

---

### `<td>`

Represents a standard data cell.

---

# Visual Representation

```text
+------------------------------------+
|          Table Caption             |
+------------------------------------+
| ID | Name | Course | Marks         |
+------------------------------------+
|101 | Alice| Java   | 95            |
|102 | Bob  | Python | 90            |
|103 | John | HTML5  | 92            |
+------------------------------------+
| Total Students : 3                 |
+------------------------------------+
```

---

# Advantages of Proper Table Structure

A properly structured table:

- Improves readability.
- Enhances accessibility.
- Supports screen readers.
- Simplifies maintenance.
- Improves SEO.
- Separates header, body, and footer logically.
- Makes CSS styling easier.

---

# Real-World Applications

Proper table structures are used in:

- Student databases
- Employee records
- Bank statements
- Sales reports
- Product catalogs
- Hospital records
- Timetables
- Financial reports
- Attendance systems
- Invoice systems

---

# Best Practices

Follow these recommendations:

- Always use `<table>` as the parent element.
- Add a `<caption>` whenever appropriate.
- Use `<thead>`, `<tbody>`, and `<tfoot>` for larger tables.
- Use `<th>` for headings.
- Keep tables organized and readable.
- Apply CSS for styling instead of deprecated HTML attributes.
- Ensure accessibility for assistive technologies.

---

# Common Mistakes

Avoid the following mistakes:

- Using tables for page layout.
- Omitting header cells.
- Placing rows outside the `<table>` element.
- Mixing header and data cells incorrectly.
- Ignoring semantic table sections.
- Creating unnecessarily complex structures.

---

# Browser Support

HTML5 table structure elements are fully supported by all modern browsers:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

---

# Summary

A well-defined HTML table structure forms the foundation of every professional table. By correctly using elements such as `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, and `<td>`, developers can create semantic, accessible, maintainable, and visually organized tables. Following HTML5 standards ensures better compatibility, improved accessibility, and easier styling with CSS.
