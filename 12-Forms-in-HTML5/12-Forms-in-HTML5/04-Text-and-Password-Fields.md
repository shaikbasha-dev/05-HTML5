# Text and Password Fields

## Introduction

Text and password fields are among the most commonly used input controls in HTML forms. They allow users to enter textual information such as names, usernames, passwords, addresses, and other personal details.

The text field displays the entered characters normally, whereas the password field hides the entered characters to protect sensitive information.

---

# Text Field

A text field is used to accept single-line textual input from the user.

## Syntax

```html
<input type="text">
```

---

## Example

```html
<label for="fullname">Full Name</label>

<input
    type="text"
    id="fullname"
    name="fullname"
>
```

---

# Password Field

A password field is used to securely collect passwords and confidential information.

Unlike a text field, the entered characters are masked using dots or asterisks.

## Syntax

```html
<input type="password">
```

---

## Example

```html
<label for="password">Password</label>

<input
    type="password"
    id="password"
    name="password"
>
```

---

# Common Attributes

## placeholder

Displays hint text inside the input field.

Example:

```html
<input
    type="text"
    placeholder="Enter your username"
>
```

---

## maxlength

Specifies the maximum number of characters allowed.

Example:

```html
<input
    type="password"
    maxlength="16"
>
```

---

## minlength

Specifies the minimum number of characters required.

Example:

```html
<input
    type="password"
    minlength="8"
>
```

---

## required

Makes the field mandatory.

Example:

```html
<input
    type="text"
    required
>
```

---

## autocomplete

Allows the browser to automatically fill previously entered values.

Example:

```html
<input
    type="text"
    autocomplete="on"
>
```

---

## readonly

Allows users to view the value without modifying it.

Example:

```html
<input
    type="text"
    value="Administrator"
    readonly
>
```

---

# Complete Example

```html
<form>

    <label for="username">Username</label>

    <input
        type="text"
        id="username"
        name="username"
        placeholder="Enter your username"
        required
    >

    <br><br>

    <label for="password">Password</label>

    <input
        type="password"
        id="password"
        name="password"
        placeholder="Enter your password"
        minlength="8"
        maxlength="16"
        required
    >

    <br><br>

    <input
        type="submit"
        value="Login"
    >

</form>
```

---

# Differences Between Text and Password Fields

| Text Field | Password Field |
|------------|----------------|
| Displays entered characters | Hides entered characters |
| Used for general text input | Used for confidential information |
| Suitable for names, usernames, addresses | Suitable for passwords and PINs |
| Characters remain visible | Characters are masked |

---

# Advantages

- Easy to use
- Simple implementation
- Supports HTML5 validation
- Improves user interaction
- Protects confidential information using password masking
- Compatible with all modern browsers

---

# Best Practices

- Use text fields only for plain textual information.
- Use password fields for sensitive information.
- Provide meaningful labels.
- Use placeholder text when appropriate.
- Specify minimum and maximum password lengths.
- Mark mandatory fields using the `required` attribute.
- Avoid storing passwords in plain text on the server.

---

# Summary

Text and password fields are fundamental components of HTML forms. The text field collects visible user input, while the password field securely masks sensitive information. Using the appropriate field type and attributes helps create secure, user-friendly, and accessible web forms.
