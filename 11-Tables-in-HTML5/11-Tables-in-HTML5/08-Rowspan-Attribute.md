# Rowspan Attribute in HTML5

## Overview

The `rowspan` attribute is used to merge two or more rows into a single table cell. It allows one cell to extend vertically across multiple rows, making tables more organized and reducing repetitive information.

The `rowspan` attribute can be applied to both `<td>` (table data cells) and `<th>` (table header cells).

Using `rowspan` effectively helps create cleaner, more readable, and professional table layouts while maintaining semantic HTML5 structure.

---

# What is the Rowspan Attribute?

The `rowspan` attribute specifies the number of rows that a table cell should span.

Instead of repeating the same cell content in multiple rows, one cell can extend vertically across adjacent rows.

Syntax:

```html
<td rowspan="2">Content</td>
```

or

```html
<th rowspan="3">Header</th>
```

---

# Why Use Rowspan?

The `rowspan` attribute provides several benefits:

- Merge multiple rows into a single cell.
- Reduce duplicate information.
- Create grouped table layouts.
- Improve readability.
- Organize related data.
- Create professional-looking reports.

---

# Basic Syntax

```html
<td rowspan="2">

    Content

</td>
```

---

# Basic Example

```html
<table border="1">

    <tr>

        <th>Name</th>

        <th>Course</th>

    </tr>

    <tr>

        <td rowspan="2">

            Alice

        </td>

        <td>Java</td>

    </tr>

    <tr>

        <td>Python</td>

    </tr>

</table>
```

In this example, the **Alice** cell spans two rows.

---

# Example with Three Rows

```html
<table border="1">

    <tr>

        <th>Department</th>

        <th>Employee</th>

    </tr>

    <tr>

        <td rowspan="3">

            Development

        </td>

        <td>Rahul</td>

    </tr>

    <tr>

        <td>Alice</td>

    </tr>

    <tr>

        <td>John</td>

    </tr>

</table>
```

The **Development** cell spans three rows.

---

# Visual Representation

```text
Without Rowspan

+-------------+-------------+
| Department  | Employee    |
+-------------+-------------+
| Development | Rahul       |
+-------------+-------------+
| Development | Alice       |
+-------------+-------------+
| Development | John        |
+-------------+-------------+

With rowspan="3"

+-------------+-------------+
| Department  | Employee    |
+-------------+-------------+
|             | Rahul       |
| Development +-------------+
|             | Alice       |
|             +-------------+
|             | John        |
+-------------+-------------+
```

---

# Common Use Cases

The `rowspan` attribute is commonly used for:

- Department-wise employee lists
- Student attendance reports
- Timetables
- Product categories
- Invoice details
- Financial reports
- Hospital records
- Examination reports
- Inventory management
- Grouped business reports

---

# Rules for Using Rowspan

Follow these rules when using `rowspan`:

- Specify a positive integer value.
- Ensure the table structure remains balanced.
- Adjust cells in subsequent rows accordingly.
- Avoid unnecessary row merging.
- Verify the final table layout after applying `rowspan`.

---

# Advantages

Using the `rowspan` attribute provides several advantages:

- Eliminates repeated values.
- Improves table readability.
- Creates cleaner layouts.
- Organizes grouped information.
- Supports semantic HTML.
- Makes reports easier to understand.

---

# Best Practices

Follow these recommendations:

- Use `rowspan` only when it improves clarity.
- Keep merged cells meaningful.
- Combine `rowspan` with semantic table sections when appropriate.
- Maintain consistent table formatting.
- Test tables across different browsers and screen sizes.
- Use CSS for presentation instead of deprecated HTML attributes.

---

# Common Mistakes

Avoid the following mistakes:

- Using incorrect `rowspan` values.
- Forgetting to remove corresponding cells in following rows.
- Creating unbalanced table structures.
- Overusing merged rows.
- Merging unrelated information.

---

# Browser Support

The `rowspan` attribute is fully supported by all modern browsers:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

---

# Difference Between `rowspan` and `colspan`

| Feature | `rowspan` | `colspan` |
|---------|-----------|------------|
| Direction | Vertical | Horizontal |
| Merges | Rows | Columns |
| Common Use | Group related records | Group headings or summaries |
| Example | Department spanning multiple employees | Title spanning multiple columns |

---

# Summary

The HTML5 `rowspan` attribute allows a table cell to span multiple rows, reducing repetitive information and improving the organization of tabular data. When used appropriately, it enhances readability, maintains semantic structure, and creates professional table layouts that are easy to understand and maintain across modern web browsers.
