# Using the Pattern Attribute

## Introduction

The `pattern` attribute is one of the most powerful HTML5 validation features. It allows developers to validate user input using **Regular Expressions (Regex)**. When validating phone numbers, the `pattern` attribute ensures that users enter numbers in the required format before the form is submitted.

Unlike the `required` attribute, which only checks whether a field is empty, the `pattern` attribute verifies whether the entered value matches a predefined format.

---

# What is the `pattern` Attribute?

The `pattern` attribute specifies a regular expression that the input value must match.

If the entered value does not satisfy the pattern, the browser prevents form submission and displays a validation message.

---

# Syntax

```html
<input
    type="tel"
    pattern="regular-expression">
```

---

# Basic Example

```html
<input
    type="tel"
    pattern="[0-9]{10}"
    required>
```

This pattern allows only **exactly 10 numeric digits**.

---

# Understanding the Pattern

Example:

```html
pattern="[0-9]{10}"
```

Explanation:

| Expression | Meaning |
|------------|---------|
| `[0-9]` | Any digit from 0 to 9 |
| `{10}` | Exactly 10 occurrences |

Valid Input:

```text
9876543210
```

Invalid Inputs:

```text
987654321
98765432101
98765AB210
98-7654-3210
```

---

# Example with Custom Validation Message

```html
<input
    type="tel"
    pattern="[0-9]{10}"
    title="Enter a valid 10-digit mobile number."
    required>
```

The `title` attribute provides a helpful message when validation fails.

---

# Browser Behavior

When the form is submitted:

- The browser checks the entered value.
- The value is compared with the regular expression.
- If the value matches the pattern, validation succeeds.
- If the value does not match, submission is prevented.
- The browser displays a validation message.

---

# Advantages

- No JavaScript required.
- Built-in browser validation.
- Improves data quality.
- Reduces invalid submissions.
- Easy to implement.
- Supports custom input formats.

---

# Real-World Applications

The `pattern` attribute is commonly used for validating:

- Mobile Numbers
- Telephone Numbers
- Postal Codes
- PIN Codes
- Usernames
- Employee IDs
- Student IDs
- Product Codes
- License Numbers
- Identification Numbers

---

# Best Practices

- Always combine `pattern` with `type="tel"` for phone numbers.
- Use the `required` attribute for mandatory fields.
- Provide meaningful `title` messages.
- Keep regular expressions simple and readable.
- Test validation in multiple browsers.
- Always perform server-side validation.

---

# Summary

The HTML5 `pattern` attribute enables developers to validate phone numbers using regular expressions without writing JavaScript. By combining `pattern` with the `tel` input type, `required`, and `title` attributes, developers can create reliable, user-friendly, and professional phone number validation while improving data accuracy and user experience.
