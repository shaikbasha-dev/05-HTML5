# Small, Deleted and Inserted Text

## Introduction

HTML provides the `<small>`, `<del>`, and `<ins>` elements for representing text with specific semantic meaning. These elements are commonly used to display supplementary information, indicate removed content, and show newly inserted content within a document.

Unlike using CSS alone, these HTML5 elements provide semantic meaning that can be understood by browsers, search engines, and assistive technologies. Proper use of these elements improves document readability, accessibility, and maintainability.

---

# Definition

## `<small>` Element

The `<small>` element represents side comments, legal notices, disclaimers, copyright information, or other supplementary text.

The text is usually displayed in a smaller font size.

---

## `<del>` Element

The `<del>` element represents content that has been removed from a document.

Browsers usually display deleted text with a strike-through line.

---

## `<ins>` Element

The `<ins>` element represents content that has been inserted into a document.

Browsers usually display inserted text with an underline.

---

# Syntax

## Small Text

```html
<small>Small Text</small>
```

Example:

```html
<small>Terms and conditions apply.</small>
```

---

## Deleted Text

```html
<del>Old Price</del>
```

Example:

```html
<del>₹5,000</del>
```

---

## Inserted Text

```html
<ins>New Price</ins>
```

Example:

```html
<ins>₹4,000</ins>
```

---

# Browser Output

```html
<p>
    <small>Copyright © 2026</small>
</p>

<p>
    <del>Old Version</del>
</p>

<p>
    <ins>Updated Version</ins>
</p>
```

Output:

- Smaller text
- Strikethrough text
- Underlined inserted text

---

# Difference Between `<small>`, `<del>`, and `<ins>`

| `<small>` | `<del>` | `<ins>` |
|------------|----------|----------|
| Displays supplementary text | Represents deleted content | Represents inserted content |
| Usually appears smaller | Usually appears with strike-through | Usually appears underlined |
| Used for notes and legal text | Used for removed information | Used for newly added information |
| Semantic element | Semantic element | Semantic element |

---

# Complete Example

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <title>Small, Deleted and Inserted Text</title>

</head>

<body>

    <h1>HTML Text Formatting</h1>

    <p>
        <small>
            Last updated on July 2026.
        </small>
    </p>

    <p>
        Laptop Price:
        <del>₹65,000</del>
        <ins>₹59,999</ins>
    </p>

    <p>
        Course Duration:
        <del>8 Months</del>
        <ins>6 Months</ins>
    </p>

    <p>
        <small>
            Offer valid until the end of this month.
        </small>
    </p>

</body>

</html>
```

---

# Real-World Applications

These elements are commonly used in:

- E-commerce websites
- Price comparison pages
- Product updates
- Documentation revisions
- Legal notices
- Terms and conditions
- Version history
- Content management systems

---

# Advantages

- Improves readability.
- Clearly indicates document changes.
- Supports semantic HTML.
- Enhances accessibility.
- Helps users identify updates quickly.
- Makes documents easier to maintain.

---

# Best Practices

- Use `<small>` only for supplementary information.
- Use `<del>` to indicate removed content.
- Use `<ins>` to indicate newly added content.
- Avoid using these elements purely for visual styling.
- Keep revision history meaningful and accurate.

---

# Common Mistakes

- Using `<small>` for normal paragraphs.
- Using `<del>` only for decoration.
- Using `<ins>` simply to underline text.
- Ignoring semantic meaning.
- Replacing CSS styling with semantic elements unnecessarily.

---

# Interview Questions

### 1. What is the purpose of the `<small>` element?

The `<small>` element displays supplementary information such as legal notices, copyright information, or side comments.

---

### 2. What does the `<del>` element represent?

The `<del>` element represents content that has been removed from a document.

---

### 3. What does the `<ins>` element represent?

The `<ins>` element represents newly inserted content within a document.

---

### 4. Which HTML elements are commonly used to display document revisions?

The `<del>` and `<ins>` elements.

---

### 5. Are `<small>`, `<del>`, and `<ins>` semantic elements?

Yes. All three elements provide semantic meaning in HTML5.

---

# Summary

The `<small>`, `<del>`, and `<ins>` elements provide semantic ways to display supplementary information, deleted content, and inserted content. These elements improve document clarity, accessibility, and maintainability while helping users easily identify revisions and additional information. Proper use of these formatting elements contributes to creating professional, semantic, and standards-compliant HTML5 webpages.
