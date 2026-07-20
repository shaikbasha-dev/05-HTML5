# Number and Range Inputs

## Introduction

HTML5 provides specialized input types for accepting numeric values and selecting values within a specified range. The `number` input allows users to enter numerical data, while the `range` input displays a slider that enables users to choose a value visually.

These input types improve user experience, provide built-in validation, and reduce invalid data entry.

---

# Number Input

A number input is used to accept numeric values such as age, quantity, salary, marks, price, and other numerical information.

## Syntax

```html
<input type="number">
```

---

## Example

```html
<label for="age">Age</label>

<input
    type="number"
    id="age"
    name="age"
>
```

---

# Range Input

A range input displays a slider that allows users to select a value within a predefined minimum and maximum range.

## Syntax

```html
<input type="range">
```

---

## Example

```html
<label for="volume">Volume</label>

<input
    type="range"
    id="volume"
    name="volume"
>
```

---

# Common Attributes

## min

Specifies the minimum allowed value.

Example:

```html
<input
    type="number"
    min="1"
>
```

---

## max

Specifies the maximum allowed value.

Example:

```html
<input
    type="number"
    max="100"
>
```

---

## step

Specifies the interval between valid values.

Example:

```html
<input
    type="number"
    step="5"
>
```

---

## value

Defines the default value.

Example:

```html
<input
    type="range"
    value="50"
>
```

---

## required

Makes the field mandatory.

Example:

```html
<input
    type="number"
    required
>
```

---

# Complete Example

```html
<form>

    <label for="age">Age</label>

    <input
        type="number"
        id="age"
        name="age"
        min="18"
        max="60"
        required
    >

    <br><br>

    <label for="experience">Experience Level</label>

    <input
        type="range"
        id="experience"
        name="experience"
        min="0"
        max="10"
        step="1"
        value="5"
    >

    <br><br>

    <input
        type="submit"
        value="Submit"
    >

</form>
```

---

# Advantages

- Built-in numeric validation
- Prevents invalid character input
- Easy value selection using sliders
- Improves user experience
- Reduces data entry errors
- Mobile-friendly controls
- Supported by modern browsers

---

# Best Practices

- Use `type="number"` for numeric values.
- Use `type="range"` when users need to select a value within a range.
- Always specify appropriate `min` and `max` values.
- Use the `step` attribute when fixed intervals are required.
- Provide meaningful labels for accessibility.
- Validate submitted data on the server side.
- Display selected range values when appropriate using JavaScript.

---

# Differences Between Number and Range Inputs

| Number Input | Range Input |
|--------------|-------------|
| Accepts typed numeric values | Uses a slider control |
| Suitable for exact numbers | Suitable for approximate value selection |
| Displays a numeric input box | Displays a horizontal slider |
| Example: Age, Salary, Quantity | Example: Volume, Brightness, Rating |

---

# Real-World Applications

- Age Selection
- Product Quantity
- Employee Salary
- Student Marks
- Shopping Cart Quantity
- Volume Control
- Screen Brightness
- Audio Settings
- Rating Systems
- Progress Indicators

---

# Summary

The HTML5 `number` and `range` input types provide efficient ways to collect numeric information. The `number` input is ideal for precise values, while the `range` input offers an intuitive slider for selecting values within a specified interval. Using these input types improves usability, validation, and the overall user experience in modern web forms.
