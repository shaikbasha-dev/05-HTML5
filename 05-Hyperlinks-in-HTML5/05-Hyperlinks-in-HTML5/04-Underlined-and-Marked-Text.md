# Underlined and Marked Text

## Introduction

HTML provides the `<u>` and `<mark>` elements for formatting text that requires visual distinction. Although both elements make content stand out, they serve different purposes.

The `<u>` element displays underlined text and is generally used to indicate annotations or non-textual cues. The `<mark>` element highlights text to represent information that is relevant or significant within a particular context.

Understanding the appropriate use of these elements helps developers create semantic, accessible, and user-friendly HTML5 documents.

---

# Definition

## `<u>` Element

The `<u>` element represents text that should be visually underlined.

It is commonly used for:

- Proper names in certain writing systems
- Misspelled words (with additional styling)
- Annotations
- Non-textual indications

It should **not** be used simply because text needs emphasis.

---

## `<mark>` Element

The `<mark>` element represents text that has been highlighted because of its relevance or importance within a specific context.

Browsers typically display marked text with a yellow background.

---

# Syntax

## Underlined Text

```html
<u>Underlined Text</u>
```

Example:

```html
<u>Registration Number</u>
```

---

## Highlighted Text

```html
<mark>Highlighted Text</mark>
```

Example:

```html
<mark>Important Notice</mark>
```

---

# Browser Output

```html
<p>
    <u>Underlined Text</u>
</p>

<p>
    <mark>Highlighted Text</mark>
</p>
```

Output:

- Underlined Text
- Highlighted Text

The first text is underlined, while the second text is highlighted.

---

# Difference Between `<u>` and `<mark>`

| `<u>` | `<mark>` |
|--------|----------|
| Underlines text | Highlights text |
| Used for annotations | Used for relevant information |
| No emphasis implied | Indicates contextual relevance |
| Visual formatting | Semantic formatting |
| Less commonly used | Frequently used for search results and highlights |

---

# Complete Example

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <title>Underlined and Marked Text</title>

</head>

<body>

    <h1>HTML Text Formatting</h1>

    <p>
        Student ID:
        <u>JFS2026A001</u>
    </p>

    <p>
        Please read the
        <mark>important examination guidelines</mark>
        before attending the test.
    </p>

    <p>
        Search Result:
        HTML is the
        <mark>standard markup language</mark>
        for creating web pages.
    </p>

    <p>
        The following word is
        <u>underlined</u>
        for demonstration purposes.
    </p>

</body>

</html>
```

---

# Advantages

- Improves readability.
- Draws attention to important information.
- Highlights search results.
- Supports semantic HTML with `<mark>`.
- Enhances user experience.
- Makes important content easier to identify.

---

# Best Practices

- Use `<mark>` for relevant or highlighted content.
- Use `<u>` only when underlining has semantic meaning.
- Avoid underlining ordinary text because users may mistake it for hyperlinks.
- Use CSS when only visual styling is required.
- Keep highlighted content concise.

---

# Common Mistakes

- Using `<u>` instead of CSS for decorative underlining.
- Underlining hyperlinks manually.
- Highlighting excessive amounts of text.
- Using `<mark>` for permanent styling.
- Ignoring semantic meaning.

---

# Interview Questions

### 1. What is the purpose of the `<u>` element?

The `<u>` element displays underlined text and is used for annotations or specific textual conventions.

---

### 2. What is the purpose of the `<mark>` element?

The `<mark>` element highlights text that is relevant or important within a particular context.

---

### 3. What is the difference between `<u>` and `<mark>`?

`<u>` underlines text, whereas `<mark>` highlights text to indicate contextual relevance.

---

### 4. Should `<u>` be used for hyperlinks?

No. Hyperlinks are created using the `<a>` element, and underlining should not be used to imitate links.

---

### 5. Which element is more semantic?

`<mark>` is more semantic because it communicates that the enclosed text is relevant within its surrounding context.

---

# Summary

The `<u>` and `<mark>` elements are useful HTML5 formatting elements for drawing attention to text. The `<u>` element underlines text for annotations or specific conventions, while the `<mark>` element highlights relevant content with semantic meaning. Using these elements appropriately improves readability, accessibility, and semantic HTML, resulting in professional and standards-compliant webpages.
