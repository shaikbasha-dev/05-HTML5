# Email and URL Fields

## Introduction

HTML5 introduced specialized input types such as `email` and `url` to simplify data collection and improve form validation. These input types automatically validate the entered data format before the form is submitted, reducing errors and improving the user experience.

The `email` input is used for collecting email addresses, while the `url` input is used for collecting website addresses.

---

# Email Field

An email field is used to collect a valid email address from the user.

HTML5 automatically checks whether the entered value follows a valid email format.

## Syntax

```html
<input type="email">
```

---

## Example

```html
<label for="email">Email Address</label>

<input
    type="email"
    id="email"
    name="email"
    placeholder="example@gmail.com"
>
```

---

# URL Field

A URL field is used to collect website addresses from users.

The browser validates that the entered value follows a proper URL format.

## Syntax

```html
<input type="url">
```

---

## Example

```html
<label for="website">Website</label>

<input
    type="url"
    id="website"
    name="website"
    placeholder="https://example.com"
>
```

---

# Common Attributes

## placeholder

Displays sample text inside the input field.

Example:

```html
<input
    type="email"
    placeholder="Enter your email"
>
```

---

## required

Makes the field mandatory.

Example:

```html
<input
    type="url"
    required
>
```

---

## autocomplete

Allows browsers to suggest previously entered values.

Example:

```html
<input
    type="email"
    autocomplete="email"
>
```

---

## maxlength

Limits the maximum number of characters.

Example:

```html
<input
    type="email"
    maxlength="100"
>
```

---

## readonly

Allows viewing but prevents editing.

Example:

```html
<input
    type="url"
    value="https://example.com"
    readonly
>
```

---

# Complete Example

```html
<form>

    <label for="email">Email Address</label>

    <input
        type="email"
        id="email"
        name="email"
        placeholder="example@gmail.com"
        required
    >

    <br><br>

    <label for="website">Website</label>

    <input
        type="url"
        id="website"
        name="website"
        placeholder="https://example.com"
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

- Built-in HTML5 validation
- Improves data accuracy
- Reduces invalid submissions
- Enhances user experience
- Displays appropriate keyboards on mobile devices
- Easy to implement
- Supported by all modern browsers

---

# Best Practices

- Use `type="email"` only for email addresses.
- Use `type="url"` for website links.
- Provide meaningful placeholder text.
- Mark mandatory fields using the `required` attribute.
- Use descriptive labels for accessibility.
- Validate submitted data again on the server side.
- Avoid relying only on client-side validation.

---

# Differences Between Email and URL Fields

| Email Field | URL Field |
|-------------|-----------|
| Accepts email addresses | Accepts website addresses |
| Uses `type="email"` | Uses `type="url"` |
| Validates email format | Validates URL format |
| Example: `user@example.com` | Example: `https://example.com` |

---

# Summary

The HTML5 `email` and `url` input types provide built-in validation for email addresses and website URLs. They improve data quality, enhance the user experience, and reduce the need for custom validation while making forms more reliable and user-friendly.
