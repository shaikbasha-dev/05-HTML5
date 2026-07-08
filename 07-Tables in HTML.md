# Tables in HTML

## Introduction

HTML Tables are used to **organize and display data in rows and columns**.

Tables are commonly used to represent:

* Student Records
* Employee Details
* Product Information
* Marks Sheets
* Financial Reports

HTML provides several tags to create tables such as:

* `<table>`
* `<tr>`
* `<th>`
* `<td>`

---

## Example Program

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Tables Tags</title>
</head>
<body>

    <h2>Java Full Stack Training Batch Matrix</h2>

    <table border="1">

        <tr>
            <th>Roll Number</th>
            <th>Student Name</th>
            <th>Academic CGPA</th>
        </tr>

        <tr>
            <td>1</td>
            <td>Apple</td>
            <td>9.8</td>
        </tr>

        <tr>
            <td>2</td>
            <td>Banana</td>
            <td>9.3</td>
        </tr>

    </table>

</body>
</html>
```

---

## Tags Used in HTML Tables

### 1. `<table></table>`

#### Definition

The `<table>` tag is used to **create a table in HTML**.

It acts as a container that stores:

* Rows
* Columns
* Headers
* Table Data

#### Syntax

```html
<table>

</table>
```

#### Example

```html
<table border="1">

</table>
```

---

### 2. `<tr></tr>` - Table Row

#### Definition

The `<tr>` tag stands for **Table Row**.

It is used to **create a row inside a table**.

#### Syntax

```html
<tr>

</tr>
```

#### Example

```html
<tr>
    <td>1</td>
    <td>Apple</td>
    <td>9.8</td>
</tr>
```

---

### 3. `<th></th>` - Table Header

#### Definition

The `<th>` tag stands for **Table Header**.

It is used to **define heading cells inside a table**.

By default:

* Text is bold.
* Text is centered.

#### Syntax

```html
<th>Header Name</th>
```

#### Example

```html
<th>Student Name</th>
```

Output:

```text
Student Name
```

---

### 4. `<td></td>` - Table Data

#### Definition

The `<td>` tag stands for **Table Data**.

It is used to **insert actual data inside table cells**.

#### Syntax

```html
<td>Value</td>
```

#### Example

```html
<td>Apple</td>
```

Output:

```text
Apple
```

---

## Border Attribute

### Definition

The `border` attribute is used to **display borders around the table and cells**.

### Example

```html
<table border="1">
```

Output:

The browser displays visible borders around:

* Table
* Rows
* Columns

---

## Explanation of the Program

### Heading

```html
<h2>Java Full Stack Training Batch Matrix</h2>
```

Displays a heading above the table.

---

### Table Creation

```html
<table border="1">
```

Creates a table with visible borders.

---

### Header Row

```html
<tr>

<th>Roll Number</th>

<th>Student Name</th>

<th>Academic CGPA</th>

</tr>
```

Creates the first row containing table headings.

---

### First Data Row

```html
<tr>

<td>1</td>

<td>Apple</td>

<td>9.8</td>

</tr>
```

Displays:

| **Roll Number** | **Student Name** | **Academic CGPA** |
| ----------- | ------------ | ------------- |
| 1           | Apple        | 9.8           |

---

### Second Data Row

```html
<tr>

<td>2</td>

<td>Banana</td>

<td>9.3</td>

</tr>
```

Displays:

| **Roll Number** | **Student Name** | **Academic CGPA** |
| ----------- | ------------ | ------------- |
| 2           | Banana       | 9.3           |

---

## Output

| **Roll Number** | **Student Name** | **Academic CGPA** |
| ----------- | ------------ | ------------- |
| 1           | Apple        | 9.8           |
| 2           | Banana       | 9.3           |

---

## Difference Between Table Tags

| **Tag**       | **Purpose**               |
| --------- | --------------------- |
| `<table>` | Creates a table       |
| `<tr>`    | Creates a row         |
| `<th>`    | Creates a header cell |
| `<td>`    | Creates a data cell   |

---

## Important Points

* `<table>` creates the table structure.
* `<tr>` creates rows.
* `<th>` creates headings.
* `<td>` inserts data.
* The `border` attribute displays table borders.
* Tables organize data in rows and columns.
* Tables are widely used in dashboards, reports, forms, and databases.

---

## Summary

HTML Tables are used to display structured information in rows and columns. The `<table>`, `<tr>`, `<th>`, and `<td>` tags work together to create well-organized tabular data. Tables are one of the fundamental HTML elements and are extensively used in real-world web applications and enterprise systems.
