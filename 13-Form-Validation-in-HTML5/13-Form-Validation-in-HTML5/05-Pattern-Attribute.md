# Pattern Attribute

## Introduction

The `pattern` attribute is an HTML5 validation attribute used to validate user input against a specified regular expression (Regular Expression or Regex). It ensures that the entered value follows a predefined format before the form is submitted.

The `pattern` attribute is commonly used for validating usernames, passwords, phone numbers, postal codes, identification numbers, and other text-based input that must follow a specific format.

HTML5 browsers automatically compare the user's input with the specified regular expression. If the entered value does not match the pattern, the browser prevents form submission and displays a validation message.

---

# What is the Pattern Attribute?

The `pattern` attribute specifies a regular expression that the input value must match.

If the entered value does not satisfy the regular expression, the browser displays a validation error and prevents form submission.

---

# Syntax

```html
<input
    type="text"
    pattern="regular-expression"
>
```

---

# Basic Example

The following example allows only uppercase and lowercase English letters.

```html
<input
    type="text"
    id="name"
    name="name"
    pattern="[A-Za-z]+"
    required
>
```

---

# Common Pattern Examples

## Username Validation

Allows only letters and numbers with a length between 5 and 15 characters.

```html
<input
    type="text"
    pattern="[A-Za-z0-9]{5,15}"
    required
>
```

---

## Password Validation

Requires at least one uppercase letter, one lowercase letter, one number, and a minimum of 8 characters.

```html
<input
    type="password"
    pattern="(?=.*[a-z])(?=.*[A-Z])(?=.*\d).{8,}"
    required
>
```

---

## Phone Number Validation

Allows exactly 10 digits.

```html
<input
    type="tel"
    pattern="[0-9]{10}"
    required
>
```

---

## Postal Code Validation

Allows exactly 6 digits.

```html
<input
    type="text"
    pattern="[0-9]{6}"
    required
>
```

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
        pattern="[A-Za-z0-9]{5,15}"
        required
    >

    <br><br>

    <label for="phone">

        Mobile Number

    </label>

    <input
        type="tel"
        id="phone"
        name="phone"
        pattern="[0-9]{10}"
        required
    >

    <br><br>

    <label for="password">

        Password

    </label>

    <input
        type="password"
        id="password"
        name="password"
        pattern="(?=.*[a-z])(?=.*[A-Z])(?=.*\d).{8,}"
        required
    >

    <br><br>

    <input
        type="submit"
        value="Register"
    >

</form>
```

---

# Advantages

- Validates user input automatically.
- Reduces invalid form submissions.
- Improves data consistency.
- Supports flexible validation rules.
- Reduces JavaScript for simple validation.
- Improves user experience.
- Supported by modern browsers.

---

# Best Practices

- Use simple and readable regular expressions.
- Combine the `pattern` attribute with the `required` attribute when appropriate.
- Provide clear instructions about the expected input format.
- Test regular expressions thoroughly.
- Avoid unnecessarily complex patterns.
- Always perform server-side validation.
- Use meaningful validation messages for users.

---

# Real-World Applications

The `pattern` attribute is commonly used in:

- User Registration Forms
- Login Systems
- Mobile Number Validation
- Employee Registration Forms
- Student Admission Forms
- Password Validation
- Postal Code Validation
- Membership Registration
- Banking Applications
- Government Service Portals

---

# Difference Between Pattern Validation and Input Types

| Pattern Attribute | HTML5 Input Types |
|-------------------|-------------------|
| Uses regular expressions for custom validation. | Provides built-in validation for specific data types. |
| Suitable for custom formats. | Suitable for standard formats such as email, URL, and number. |
| Highly flexible. | Limited to predefined browser validation rules. |

---

# Summary

The HTML5 `pattern` attribute provides a powerful and flexible way to validate user input using regular expressions. It enables developers to enforce custom input formats without writing additional JavaScript, improving data quality and user experience. Since client-side validation can be bypassed, the `pattern` attribute should always be used together with server-side validation to ensure complete security and reliable data processing.
