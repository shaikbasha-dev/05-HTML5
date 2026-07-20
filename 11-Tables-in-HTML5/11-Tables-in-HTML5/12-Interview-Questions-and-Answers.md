# HTML5 Tables Interview Questions and Answers

## Overview

HTML tables are one of the most frequently discussed topics during HTML5, Frontend Development, Java Full Stack, and Web Development interviews. Interviewers often assess a candidate's understanding of table elements, semantic structure, accessibility, responsive design, and best practices.

This document provides commonly asked HTML5 table interview questions along with clear and concise answers to strengthen both conceptual understanding and interview preparation.

---

# Basic Interview Questions

## 1. What is an HTML table?

**Answer:**

An HTML table is used to display data in a structured format consisting of rows and columns. It is created using the `<table>` element.

---

## 2. Which HTML element creates a table?

**Answer:**

The `<table>` element creates an HTML table.

Example:

```html
<table>

</table>
```

---

## 3. Which element creates a table row?

**Answer:**

The `<tr>` (Table Row) element creates a row.

Example:

```html
<tr>

</tr>
```

---

## 4. Which element creates a table data cell?

**Answer:**

The `<td>` (Table Data) element creates a data cell.

Example:

```html
<td>Java</td>
```

---

## 5. Which element creates a table header cell?

**Answer:**

The `<th>` element creates a header cell.

Example:

```html
<th>Name</th>
```

---

# Intermediate Interview Questions

## 6. What is the difference between `<th>` and `<td>`?

**Answer:**

| `<th>` | `<td>` |
|----------|----------|
| Creates a header cell. | Creates a data cell. |
| Usually bold by default. | Normal text by default. |
| Used for headings. | Used for table values. |
| Improves accessibility. | Displays actual data. |

---

## 7. What is the purpose of the `<caption>` element?

**Answer:**

The `<caption>` element provides a descriptive title for a table, helping users understand its purpose and improving accessibility.

---

## 8. What are `<thead>`, `<tbody>`, and `<tfoot>`?

**Answer:**

- `<thead>` contains the table headers.
- `<tbody>` contains the main table data.
- `<tfoot>` contains summary or footer information.

These elements organize tables into semantic sections.

---

## 9. What is the `colspan` attribute?

**Answer:**

The `colspan` attribute allows a table cell to span multiple columns.

Example:

```html
<td colspan="2">

    Total

</td>
```

---

## 10. What is the `rowspan` attribute?

**Answer:**

The `rowspan` attribute allows a table cell to span multiple rows.

Example:

```html
<td rowspan="3">

    Development

</td>
```

---

# Advanced Interview Questions

## 11. Why should tables not be used for page layout?

**Answer:**

Tables are intended for displaying tabular data only.

For page layouts, modern CSS techniques such as:

- Flexbox
- CSS Grid

should be used because they provide better responsiveness, accessibility, and maintainability.

---

## 12. What is the purpose of the `scope` attribute?

**Answer:**

The `scope` attribute defines whether a header applies to a row or a column.

Example:

```html
<th scope="col">

    Name

</th>
```

It improves accessibility for screen readers.

---

## 13. How do you make an HTML table responsive?

**Answer:**

Wrap the table inside a container with horizontal scrolling.

Example:

```html
<div class="table-container">

    <table>

    </table>

</div>
```

CSS:

```css
.table-container {

    overflow-x: auto;

}
```

---

## 14. What is semantic table structure?

**Answer:**

Semantic table structure means organizing a table using:

- `<caption>`
- `<thead>`
- `<tbody>`
- `<tfoot>`
- `<th>`

This improves readability and accessibility.

---

## 15. Which CSS property removes double borders?

**Answer:**

```css
border-collapse: collapse;
```

---

# Scenario-Based Interview Questions

## 16. When should you use `colspan`?

**Answer:**

Use `colspan` when a cell needs to span across multiple columns, such as creating grouped headings or summary rows.

---

## 17. When should you use `rowspan`?

**Answer:**

Use `rowspan` when a cell needs to span across multiple rows, such as grouping related records under the same category.

---

## 18. Why are table captions important?

**Answer:**

Captions:

- Describe the table.
- Improve accessibility.
- Help screen readers.
- Provide context before users read the table.

---

## 19. What are some HTML table best practices?

**Answer:**

- Use tables only for tabular data.
- Use semantic table elements.
- Add captions.
- Use meaningful headers.
- Apply CSS for styling.
- Make tables responsive.
- Follow accessibility guidelines.

---

## 20. Which browsers support HTML5 tables?

**Answer:**

HTML5 table elements are fully supported by all modern browsers, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

---

# Quick Revision

| Topic | Key Point |
|--------|-----------|
| `<table>` | Creates the table container. |
| `<tr>` | Creates a table row. |
| `<td>` | Creates a table data cell. |
| `<th>` | Creates a table header cell. |
| `<caption>` | Adds a table title. |
| `<thead>` | Groups header rows. |
| `<tbody>` | Groups main table data. |
| `<tfoot>` | Groups footer rows. |
| `colspan` | Merges columns. |
| `rowspan` | Merges rows. |
| `scope` | Improves accessibility. |
| `border-collapse` | Removes double borders. |
| Responsive Table | Uses `overflow-x: auto`. |

---

# Summary

A strong understanding of HTML5 tables requires knowledge of semantic table elements, rows, columns, captions, table sections, merged cells, accessibility features, responsive design, and best practices. Reviewing these interview questions and answers will help learners prepare confidently for technical interviews, coding assessments, and real-world frontend development tasks.
