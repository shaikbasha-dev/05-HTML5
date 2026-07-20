# Regular Expressions (Regex) Basics

## Introduction

Regular Expressions, commonly known as **Regex**, are patterns used to match, validate, and search text. In HTML5, regular expressions are primarily used with the `pattern` attribute to validate user input such as phone numbers, email addresses, usernames, postal codes, and passwords.

Regex provides a flexible and efficient way to define acceptable input formats without writing JavaScript. Understanding the basics of regular expressions is essential for implementing accurate client-side validation in modern web applications.

---

# What is a Regular Expression?

A Regular Expression (Regex) is a sequence of characters that defines a search or validation pattern.

When used with the HTML5 `pattern` attribute, the browser compares the user's input against the specified regular expression before allowing form submission.

---

# Why Use Regex?

Regular expressions help developers:

- Validate user input.
- Restrict invalid characters.
- Enforce specific input formats.
- Improve data accuracy.
- Reduce server-side validation errors.
- Simplify client-side validation.

---

# HTML5 Syntax

```html
<input
    type="tel"
    pattern="[0-9]{10}"
    required>
```

The browser validates the entered value against the regular expression before submitting the form.

---

# Common Regex Symbols

| Symbol | Meaning |
|---------|---------|
| `[]` | Character set |
| `[0-9]` | Any digit from 0 to 9 |
| `[A-Z]` | Uppercase letters |
| `[a-z]` | Lowercase letters |
| `[A-Za-z]` | Alphabetic characters |
| `+` | One or more occurrences |
| `*` | Zero or more occurrences |
| `?` | Zero or one occurrence |
| `{n}` | Exactly *n* occurrences |
| `{n,m}` | Between *n* and *m* occurrences |
| `^` | Beginning of the input |
| `$` | End of the input |

---

# Regex for Indian Mobile Numbers

```text
[0-9]{10}
```

Matches:

```text
9876543210
```

Does Not Match:

```text
987654321
98765432101
98765AB210
```

---

# Regex with Country Code

```text
(\+91)?[6-9][0-9]{9}
```

Matches:

```text
9876543210
+919876543210
```

This pattern allows an optional `+91` country code followed by a valid Indian mobile number.

---

# Using Regex in HTML5

```html
<input
    type="tel"
    pattern="(\+91)?[6-9][0-9]{9}"
    title="Enter a valid Indian mobile number."
    required>
```

---

# Advantages of Regex

- Powerful validation mechanism.
- Reduces JavaScript code.
- Built into HTML5 forms.
- Improves data quality.
- Supports complex validation rules.
- Easy to reuse.

---

# Best Practices

- Keep regular expressions simple.
- Add meaningful `title` messages.
- Test multiple valid and invalid inputs.
- Combine Regex with the `required` attribute.
- Validate again on the server.
- Document complex regular expressions.

---

# Real-World Applications

Regular expressions are widely used for validating:

- Mobile Numbers
- Telephone Numbers
- Email Addresses
- Passwords
- Usernames
- Postal Codes
- Product Codes
- Employee IDs
- Student IDs
- Government Identification Numbers

---

# Summary

Regular Expressions (Regex) are a fundamental tool for validating user input in HTML5 forms. When used with the `pattern` attribute, Regex enables developers to define precise input formats for phone numbers and many other types of data. Mastering basic regular expressions helps build secure, reliable, and user-friendly web applications while reducing invalid form submissions.
