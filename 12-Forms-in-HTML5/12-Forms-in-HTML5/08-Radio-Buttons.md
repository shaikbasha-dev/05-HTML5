# Radio Buttons

## Introduction

Radio buttons are form controls that allow users to select **only one option** from a group of predefined choices. They are commonly used when multiple options are available, but only one option can be selected at a time.

In HTML5, radio buttons are created using the `<input>` element with `type="radio"`. Radio buttons belonging to the same group must have the same `name` attribute.

---

# What is a Radio Button?

A radio button is an input control that enables users to choose a single option from a set of mutually exclusive options.

---

# Syntax

```html
<input type="radio">
```

---

# Basic Example

```html
<label>

    <input
        type="radio"
        name="gender"
        value="Male"
    >

    Male

</label>

<label>

    <input
        type="radio"
        name="gender"
        value="Female"
    >

    Female

</label>
```

---

# Important Attributes

## type

Specifies the input type as a radio button.

Example:

```html
<input type="radio">
```

---

## name

Groups multiple radio buttons together.

Only one radio button with the same `name` can be selected.

Example:

```html
<input
    type="radio"
    name="gender"
>
```

---

## value

Specifies the value submitted to the server.

Example:

```html
<input
    type="radio"
    value="Male"
>
```

---

## checked

Makes a radio button selected by default.

Example:

```html
<input
    type="radio"
    checked
>
```

---

## required

Ensures that one option must be selected before submitting the form.

Example:

```html
<input
    type="radio"
    required
>
```

---

# Complete Example

```html
<form>

    <p>Select Your Gender</p>

    <label>

        <input
            type="radio"
            name="gender"
            value="Male"
            required
        >

        Male

    </label>

    <br>

    <label>

        <input
            type="radio"
            name="gender"
            value="Female"
        >

        Female

    </label>

    <br>

    <label>

        <input
            type="radio"
            name="gender"
            value="Other"
        >

        Other

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

- Allows only one selection.
- Easy for users to understand.
- Built-in browser support.
- Simple to implement.
- Works well with HTML5 validation.
- Improves form usability.
- Suitable for mutually exclusive choices.

---

# Best Practices

- Use the same `name` attribute for related radio buttons.
- Always provide descriptive labels.
- Use meaningful `value` attributes.
- Use the `required` attribute when a selection is mandatory.
- Keep related options together.
- Avoid using too many radio buttons in a single group.

---

# Real-World Applications

- Gender Selection
- Payment Method
- Shipping Option
- Membership Type
- Language Selection
- Theme Selection
- Delivery Preference
- Employment Type
- Education Level
- Subscription Plans

---

# Differences Between Radio Buttons and Checkboxes

| Radio Buttons | Checkboxes |
|--------------|------------|
| Only one option can be selected | Multiple options can be selected |
| Options share the same `name` | Each checkbox can be selected independently |
| Used for mutually exclusive choices | Used for multiple selections |
| Circular selection control | Square selection control |

---

# Summary

Radio buttons are an essential HTML5 form control used when users must select exactly one option from a group of choices. By grouping radio buttons with the same `name` attribute and providing meaningful labels, developers can create intuitive, accessible, and user-friendly forms.
