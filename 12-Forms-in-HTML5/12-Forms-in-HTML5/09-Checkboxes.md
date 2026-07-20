# Checkboxes

## Introduction

Checkboxes are HTML form controls that allow users to select one or more options from a list of available choices. Unlike radio buttons, checkboxes support multiple selections, making them ideal when users need to choose several options simultaneously.

In HTML5, checkboxes are created using the `<input>` element with the `type="checkbox"` attribute.

---

# What is a Checkbox?

A checkbox is an input control that enables users to select or deselect one or more independent options within a form.

---

# Syntax

```html
<input type="checkbox">
```

---

# Basic Example

```html
<label>

    <input
        type="checkbox"
        name="java"
        value="Java"
    >

    Java

</label>

<label>

    <input
        type="checkbox"
        name="python"
        value="Python"
    >

    Python

</label>
```

---

# Important Attributes

## type

Specifies the input type as a checkbox.

Example:

```html
<input type="checkbox">
```

---

## name

Specifies the name of the checkbox.

Example:

```html
<input
    type="checkbox"
    name="skills"
>
```

---

## value

Specifies the value submitted to the server when the checkbox is selected.

Example:

```html
<input
    type="checkbox"
    value="HTML5"
>
```

---

## checked

Selects the checkbox by default.

Example:

```html
<input
    type="checkbox"
    checked
>
```

---

## required

Requires at least one checkbox to be selected before form submission.

Example:

```html
<input
    type="checkbox"
    required
>
```

---

## disabled

Disables the checkbox.

Example:

```html
<input
    type="checkbox"
    disabled
>
```

---

# Complete Example

```html
<form>

    <p>Select Your Skills</p>

    <label>

        <input
            type="checkbox"
            name="skills"
            value="HTML5"
        >

        HTML5

    </label>

    <br>

    <label>

        <input
            type="checkbox"
            name="skills"
            value="CSS3"
        >

        CSS3

    </label>

    <br>

    <label>

        <input
            type="checkbox"
            name="skills"
            value="JavaScript"
        >

        JavaScript

    </label>

    <br>

    <label>

        <input
            type="checkbox"
            name="skills"
            value="Java"
        >

        Java

    </label>

    <br><br>

    <input
        type="submit"
        value="Submit"
    >

</form>
```

---

# Advantages

- Supports multiple selections.
- Simple and easy to use.
- Improves user interaction.
- Built-in browser support.
- Easy to style with CSS.
- Compatible with JavaScript.
- Supported by all modern browsers.

---

# Best Practices

- Provide descriptive labels for every checkbox.
- Group related checkboxes together.
- Use meaningful `name` and `value` attributes.
- Use the `checked` attribute only when an option should be selected by default.
- Avoid presenting too many checkboxes in a single group.
- Ensure forms remain accessible by associating labels with checkboxes.

---

# Real-World Applications

- Selecting Technical Skills
- Hobbies
- Interests
- Course Enrollment
- Newsletter Subscription
- Terms and Conditions Agreement
- Product Features
- Food Preferences
- Notification Preferences
- Software Installation Options

---

# Differences Between Checkboxes and Radio Buttons

| Checkboxes | Radio Buttons |
|------------|---------------|
| Multiple options can be selected | Only one option can be selected |
| Independent selections | Mutually exclusive selections |
| Square selection control | Circular selection control |
| Used for multiple-choice input | Used for single-choice input |

---

# Summary

Checkboxes are essential HTML5 form controls that allow users to select multiple options independently. They are widely used in registration forms, surveys, preference settings, and questionnaires. Proper use of labels, meaningful values, and semantic structure ensures that checkboxes remain accessible, user-friendly, and effective in modern web applications.
