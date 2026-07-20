# Input Elements

## Introduction

Input elements are the most commonly used controls in HTML forms. They allow users to enter different types of information such as text, passwords, email addresses, phone numbers, dates, files, and much more.

The HTML5 `<input>` element supports numerous input types, making it possible to collect user data efficiently while providing built-in validation and improved user experience.

---

# What is an Input Element?

An input element is an HTML form control used to collect information from users.

It is created using the `<input>` tag, which is a self-closing element.

---

# Syntax

```html
<input type="value">
```

Example:

```html
<input type="text">
```

---

# Basic Structure

```html
<label for="username">Username</label>

<input
    type="text"
    id="username"
    name="username"
>
```

---

# Common Input Types

HTML5 provides many input types, including:

- text
- password
- email
- number
- tel
- url
- search
- date
- time
- datetime-local
- month
- week
- color
- range
- checkbox
- radio
- file
- hidden
- submit
- reset
- button

---

# Common Attributes

## type

Specifies the type of input field.

Example:

```html
<input type="email">
```

---

## id

Provides a unique identifier for the input element.

Example:

```html
<input id="email">
```

---

## name

Specifies the name of the input field that will be submitted to the server.

Example:

```html
<input name="email">
```

---

## value

Specifies the default value.

Example:

```html
<input
    type="text"
    value="John"
>
```

---

## placeholder

Displays hint text inside the input field.

Example:

```html
<input
    type="text"
    placeholder="Enter your full name"
>
```

---

## required

Makes the input field mandatory.

Example:

```html
<input
    type="email"
    required
>
```

---

## readonly

Allows users to view but not modify the value.

Example:

```html
<input
    type="text"
    value="India"
    readonly
>
```

---

## disabled

Disables the input field.

Example:

```html
<input
    type="text"
    disabled
>
```

---

# Complete Example

```html
<form>

    <label for="fullname">Full Name</label>

    <input
        type="text"
        id="fullname"
        name="fullname"
        placeholder="Enter your full name"
        required
    >

    <br><br>

    <label for="email">Email</label>

    <input
        type="email"
        id="email"
        name="email"
        placeholder="Enter your email"
        required
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

- Easy to use
- Supports multiple data types
- Built-in HTML5 validation
- Improves user experience
- Works across modern browsers
- Easily customizable with CSS
- Integrates with JavaScript

---

# Best Practices

- Use the correct input type.
- Always associate labels with input fields.
- Use meaningful `name` attributes.
- Provide placeholder text where appropriate.
- Mark required fields clearly.
- Keep forms simple and user-friendly.
- Validate input before processing.

---

# Summary

The `<input>` element is the foundation of HTML forms. With its wide variety of input types and attributes, HTML5 enables developers to build interactive, accessible, and user-friendly forms for collecting different kinds of user information efficiently.
