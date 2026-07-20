# Range Validation

## Introduction

Range validation is the process of ensuring that a numeric value falls within a specified minimum and maximum limit. HTML5 provides the `range` input type, allowing users to select a value by moving a slider instead of manually entering a number.

The `range` input type is ideal for selecting values from a continuous interval, such as volume levels, brightness, ratings, percentages, temperatures, and other adjustable settings. It supports the `min`, `max`, and `step` attributes, making it easy to define the valid range and interval between values.

Using HTML5 range validation improves user experience by providing an intuitive and interactive method for selecting numeric values.

---

# What is Range Validation?

Range validation ensures that the selected value remains within predefined minimum and maximum limits.

Instead of typing numbers manually, users select values by moving a slider.

---

# HTML5 Range Input Type

HTML5 provides the `range` input type specifically for selecting numeric values within a range.

## Syntax

```html
<input
    type="range"
>
```

---

# Basic Example

```html
<label for="volume">

    Volume

</label>

<input
    type="range"
    id="volume"
    name="volume"
>
```

A slider appears, allowing users to select a value.

---

# Using `min` and `max`

```html
<input
    type="range"
    min="0"
    max="100"
>
```

The slider allows values from **0** to **100**.

---

# Using `step`

```html
<input
    type="range"
    min="0"
    max="100"
    step="10"
>
```

Valid values include:

- 0
- 10
- 20
- 30
- 40
- 50
- 60
- 70
- 80
- 90
- 100

---

# Setting a Default Value

```html
<input
    type="range"
    min="1"
    max="10"
    value="5"
>
```

The slider initially points to **5**.

---

# Complete Example

```html
<form>

    <label for="brightness">

        Brightness

    </label>

    <input
        type="range"
        id="brightness"
        name="brightness"
        min="0"
        max="100"
        step="5"
        value="50"
    >

    <br><br>

    <label for="temperature">

        Temperature

    </label>

    <input
        type="range"
        id="temperature"
        name="temperature"
        min="16"
        max="30"
        step="1"
        value="22"
    >

    <br><br>

    <label for="rating">

        Rating

    </label>

    <input
        type="range"
        id="rating"
        name="rating"
        min="1"
        max="5"
        step="1"
        value="3"
    >

    <br><br>

    <input
        type="submit"
        value="Submit"
    >

</form>
```

---

# Common Attributes

| Attribute | Description |
|------------|-------------|
| `min` | Specifies the minimum allowed value. |
| `max` | Specifies the maximum allowed value. |
| `step` | Specifies the interval between values. |
| `value` | Specifies the default selected value. |

---

# Advantages

- Provides an interactive user interface.
- Restricts values within a specified range.
- Improves user experience.
- Easy to implement.
- Supports built-in browser validation.
- Works well on desktop and mobile devices.
- Reduces input errors.

---

# Best Practices

- Choose appropriate minimum and maximum values.
- Use meaningful default values.
- Select suitable step intervals.
- Display the selected value when appropriate.
- Validate values again on the server.
- Use labels that clearly describe the purpose of the slider.
- Test usability across different devices.

---

# Real-World Applications

Range validation is commonly used in:

- Audio Volume Controls
- Screen Brightness Settings
- Temperature Selection
- Product Rating Systems
- Survey Rating Forms
- Price Filters
- Percentage Selection
- Speed Control Settings
- Gaming Applications
- Media Player Controls

---

# Difference Between `type="range"` and `type="number"`

| `type="range"` | `type="number"` |
|----------------|-----------------|
| Displays a slider. | Displays a numeric input field. |
| Best for selecting values within a range. | Best for entering exact numeric values. |
| Provides an interactive interface. | Focuses on precise data entry. |
| Commonly used for settings and adjustments. | Commonly used for forms requiring exact numbers. |

---

# Summary

The HTML5 `range` input type provides an intuitive and user-friendly way to select numeric values within a predefined range. By supporting the `min`, `max`, `step`, and `value` attributes, it offers flexibility while ensuring users select valid values. When combined with server-side validation, range validation helps build reliable, interactive, and user-friendly web applications.
