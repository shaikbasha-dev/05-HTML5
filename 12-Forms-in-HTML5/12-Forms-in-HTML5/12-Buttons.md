# Buttons

## Introduction

Buttons are interactive form controls that allow users to perform actions such as submitting a form, resetting form fields, or executing custom operations using JavaScript. They provide an easy and intuitive way for users to interact with web applications.

HTML5 supports multiple types of buttons, each designed for a specific purpose.

---

# What is a Button?

A button is an HTML form control that triggers an action when clicked by the user.

Buttons can submit data, clear form fields, or perform custom client-side operations.

---

# Types of Buttons

HTML5 provides three primary button types:

- Submit Button
- Reset Button
- Normal Button

---

# Submit Button

A submit button sends form data to the server for processing.

## Syntax

```html
<input type="submit">
```

or

```html
<button type="submit">

    Submit

</button>
```

---

## Example

```html
<input
    type="submit"
    value="Register"
>
```

---

# Reset Button

A reset button restores all form fields to their default values.

## Syntax

```html
<input type="reset">
```

or

```html
<button type="reset">

    Reset

</button>
```

---

## Example

```html
<input
    type="reset"
    value="Clear Form"
>
```

---

# Normal Button

A normal button performs custom actions, usually with JavaScript.

## Syntax

```html
<button type="button">

    Click Me

</button>
```

---

## Example

```html
<button
    type="button"
>

    Show Message

</button>
```

---

# Difference Between `<input>` and `<button>`

| `<input>` | `<button>` |
|-----------|------------|
| Self-closing element | Opening and closing tag |
| Limited text content | Can contain text, icons, and HTML |
| Simpler syntax | More flexible |
| Mostly used for basic forms | Used for advanced UI designs |

---

# Complete Example

```html
<form>

    <label for="username">

        Username

    </label>

    <input
        type="text"
        id="username"
        name="username"
        required
    >

    <br><br>

    <input
        type="submit"
        value="Submit"
    >

    <input
        type="reset"
        value="Reset"
    >

    <button
        type="button"
    >

        Help

    </button>

</form>
```

---

# Advantages

- Easy to use.
- Improves user interaction.
- Supports multiple actions.
- Integrates with JavaScript.
- Fully customizable using CSS.
- Supported by all modern browsers.
- Essential for interactive web applications.

---

# Best Practices

- Use descriptive button text.
- Use the correct button type.
- Avoid unnecessary reset buttons.
- Keep button labels short and meaningful.
- Style buttons consistently.
- Ensure buttons are easily accessible.
- Provide sufficient spacing between buttons.

---

# Real-World Applications

- Login Forms
- Registration Forms
- Payment Pages
- Contact Forms
- Search Forms
- Shopping Cart Checkout
- Survey Forms
- Feedback Forms
- Dashboard Controls
- Administrative Panels

---

# Summary

Buttons are fundamental components of HTML5 forms that allow users to interact with web applications efficiently. Whether submitting data, resetting fields, or performing custom actions, selecting the appropriate button type improves usability, accessibility, and the overall user experience.
