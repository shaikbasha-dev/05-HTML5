# Subscript and Superscript

## Introduction

HTML provides the `<sub>` and `<sup>` elements to display text below or above the normal text baseline. These formatting elements are widely used in scientific, mathematical, engineering, educational, and chemical documents.

The `<sub>` element represents subscript text, while the `<sup>` element represents superscript text. Both elements are semantic HTML elements because they describe the relationship of the text to the surrounding content rather than merely changing its appearance.

Understanding these elements is essential for creating accurate scientific formulas, mathematical equations, footnotes, and professional technical documentation.

---

# Definition

## `<sub>` Element

The `<sub>` element represents **subscript text**, which appears slightly below the normal baseline.

It is commonly used for:

- Chemical formulas
- Mathematical expressions
- Scientific notation
- Variable indices

---

## `<sup>` Element

The `<sup>` element represents **superscript text**, which appears slightly above the normal baseline.

It is commonly used for:

- Mathematical powers
- Exponents
- Footnotes
- Ordinal numbers

---

# Syntax

## Subscript

```html
<sub>Subscript Text</sub>
```

Example:

```html
H<sub>2</sub>O
```

---

## Superscript

```html
<sup>Superscript Text</sup>
```

Example:

```html
x<sup>2</sup>
```

---

# Browser Output

```html
<p>
    Water: H<sub>2</sub>O
</p>

<p>
    Area Formula: x<sup>2</sup>
</p>
```

Output:

- Water: H₂O
- Area Formula: x²

---

# Difference Between `<sub>` and `<sup>`

| `<sub>` | `<sup>` |
|----------|----------|
| Displays text below the baseline | Displays text above the baseline |
| Used for chemical formulas | Used for exponents and powers |
| Represents subscripts | Represents superscripts |
| Semantic HTML element | Semantic HTML element |

---

# Complete Example

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <title>Subscript and Superscript</title>

</head>

<body>

    <h1>HTML Text Formatting</h1>

    <h2>Chemical Formulas</h2>

    <p>Water: H<sub>2</sub>O</p>

    <p>Carbon Dioxide: CO<sub>2</sub></p>

    <p>Sulfuric Acid: H<sub>2</sub>SO<sub>4</sub></p>

    <h2>Mathematical Expressions</h2>

    <p>x<sup>2</sup> + y<sup>2</sup></p>

    <p>2<sup>10</sup> = 1024</p>

    <p>(a + b)<sup>2</sup></p>

    <h2>Ordinals</h2>

    <p>1<sup>st</sup> Place</p>

    <p>2<sup>nd</sup> Place</p>

    <p>3<sup>rd</sup> Place</p>

</body>

</html>
```

---

# Real-World Applications

The `<sub>` and `<sup>` elements are commonly used in:

- Educational websites
- Mathematics portals
- Scientific journals
- Chemical equations
- Engineering documentation
- Medical reports
- Physics formulas
- Research publications

---

# Advantages

- Represents scientific notation accurately.
- Displays mathematical expressions correctly.
- Supports semantic HTML.
- Improves readability.
- Enhances accessibility.
- Creates professional technical documents.

---

# Best Practices

- Use `<sub>` only for subscripts.
- Use `<sup>` only for superscripts.
- Do not use these elements purely for visual positioning.
- Keep mathematical and scientific expressions accurate.
- Use semantic HTML instead of CSS for these purposes.

---

# Common Mistakes

- Using `<sub>` to move normal text downward.
- Using `<sup>` simply to make text appear smaller.
- Replacing semantic elements with CSS positioning.
- Writing chemical formulas without subscripts.
- Writing exponents without superscripts.

---

# Interview Questions

### 1. What is the purpose of the `<sub>` element?

The `<sub>` element displays subscript text below the normal text baseline.

---

### 2. What is the purpose of the `<sup>` element?

The `<sup>` element displays superscript text above the normal text baseline.

---

### 3. Give an example of using `<sub>`.

```html
H<sub>2</sub>O
```

---

### 4. Give an example of using `<sup>`.

```html
x<sup>2</sup>
```

---

### 5. Are `<sub>` and `<sup>` semantic elements?

Yes. Both elements provide semantic meaning by representing subscripts and superscripts within textual content.

---

# Summary

The `<sub>` and `<sup>` elements are essential HTML5 formatting elements used to display subscripts and superscripts. They are widely used for chemical formulas, mathematical equations, scientific notation, footnotes, and ordinal numbers. Proper use of these semantic elements improves readability, accessibility, and the accuracy of technical content while supporting professional and standards-compliant HTML5 development.
