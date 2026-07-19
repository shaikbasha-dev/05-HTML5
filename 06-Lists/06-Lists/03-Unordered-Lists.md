# Unordered Lists in HTML

## Introduction

An Unordered List in HTML is used to display a collection of related items where the order or sequence is not important. Instead of numbers or letters, the browser displays each item with a bullet symbol by default.

The Unordered List is created using the `<ul>` element, and each individual item is defined using the `<li>` element.

Unordered lists are widely used for navigation menus, feature lists, shopping lists, categories, product specifications, website menus, and any content where the sequence of items does not matter.

---

# Definition

An Unordered List is an HTML list that displays items using bullet points instead of numbers.

HTML Tags Used:

- `<ul>` — Defines an unordered list.
- `<li>` — Defines each list item.

---

# Syntax

```html
<ul>

    <li>First Item</li>

    <li>Second Item</li>

    <li>Third Item</li>

</ul>
```

---

# Basic Example

```html
<ul>

    <li>HTML</li>

    <li>CSS</li>

    <li>JavaScript</li>

    <li>Bootstrap</li>

</ul>
```

Output:

- HTML
- CSS
- JavaScript
- Bootstrap

---

# Bullet Styles

The appearance of bullets can be changed using CSS.

Common bullet styles include:

| Style | Appearance |
|--------|------------|
| disc | ● (Default) |
| circle | ○ |
| square | ■ |
| none | No Bullet |

Example:

```html
<ul style="list-style-type: square;">

    <li>Java</li>

    <li>Python</li>

    <li>C++</li>

</ul>
```

---

# Nested Unordered List

An unordered list can contain another unordered list.

Example:

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

---

# Complete Example

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <title>Unordered Lists</title>

</head>

<body>

    <h1>HTML Unordered Lists</h1>

    <h2>Programming Languages</h2>

    <ul>

        <li>Java</li>

        <li>Python</li>

        <li>JavaScript</li>

        <li>C</li>

    </ul>

    <h2>Web Technologies</h2>

    <ul style="list-style-type: square;">

        <li>HTML5</li>

        <li>CSS3</li>

        <li>JavaScript</li>

        <li>Bootstrap</li>

    </ul>

    <h2>Development Stack</h2>

    <ul>

        <li>Frontend

            <ul>

                <li>HTML</li>

                <li>CSS</li>

                <li>JavaScript</li>

            </ul>

        </li>

        <li>Backend</li>

        <li>Database</li>

    </ul>

</body>

</html>
```

---

# Real-World Applications

Unordered lists are commonly used in:

- Website navigation menus
- Shopping lists
- Product features
- Categories
- Skills lists
- Portfolio websites
- Service lists
- FAQs
- Blog categories
- Software features

---

# Advantages

- Organizes related information.
- Improves readability.
- Supports semantic HTML.
- Easy to maintain.
- Suitable when order is not important.
- Helps create clean webpage layouts.

---

# Best Practices

- Use unordered lists only when sequence does not matter.
- Keep list items short and meaningful.
- Maintain proper indentation.
- Use CSS for customizing bullet styles.
- Avoid unnecessary nesting.

---

# Common Mistakes

- Using unordered lists when sequence is important.
- Forgetting the `<li>` element.
- Excessive nesting.
- Using manual bullet characters instead of `<ul>`.
- Using `<br>` tags to create list-like content.

---

# Interview Questions

### 1. What is an Unordered List?

An Unordered List is a list that displays items using bullet points instead of numbers.

---

### 2. Which HTML tag creates an Unordered List?

The `<ul>` tag.

---

### 3. Which tag defines list items?

The `<li>` tag.

---

### 4. Can unordered lists be nested?

Yes. An unordered list can contain another unordered or ordered list.

---

### 5. How can the bullet style be changed?

The bullet style can be changed using the CSS `list-style-type` property.

---

### 6. When should an Unordered List be used?

Use an unordered list when the order of items is not important.

---

# Summary

The `<ul>` element is used to create unordered lists where the sequence of items is not significant. Each list item is defined using the `<li>` element, and CSS can be used to customize bullet styles. Unordered lists are widely used in navigation menus, feature lists, categories, and many other real-world applications, making them an essential part of semantic and standards-compliant HTML5 development.
