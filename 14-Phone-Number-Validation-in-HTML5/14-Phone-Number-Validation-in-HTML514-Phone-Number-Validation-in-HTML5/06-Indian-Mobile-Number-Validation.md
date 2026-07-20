# Indian Mobile Number Validation

## Introduction

India has one of the largest mobile user bases in the world. Many web applications require users to provide a valid Indian mobile number for registration, authentication, OTP verification, customer support, online transactions, and communication.

HTML5 allows developers to validate Indian mobile numbers using the `tel` input type together with the `pattern` attribute and Regular Expressions (Regex). This approach improves data quality and prevents users from entering invalid phone numbers before form submission.

---

# Indian Mobile Number Format

A standard Indian mobile number has:

- Exactly **10 digits**
- Starts with **6, 7, 8, or 9**
- Contains only numeric digits
- May optionally include the country code **+91**

Examples:

```text
9876543210
8765432109
7654321098
6543210987
```

Examples with country code:

```text
+919876543210
+918765432109
```

---

# HTML5 Validation Without Country Code

The following regular expression validates a 10-digit Indian mobile number.

```html
<input
    type="tel"
    pattern="[6-9][0-9]{9}"
    title="Enter a valid 10-digit Indian mobile number."
    required>
```

Pattern Explanation:

| Pattern | Meaning |
|---------|---------|
| `[6-9]` | First digit must be 6, 7, 8, or 9 |
| `[0-9]{9}` | Remaining 9 digits must be numbers |

---

# HTML5 Validation With Country Code

To allow an optional **+91** country code:

```html
<input
    type="tel"
    pattern="(\+91)?[6-9][0-9]{9}"
    title="Enter a valid Indian mobile number."
    required>
```

The country code is optional.

Accepted Examples:

```text
9876543210
+919876543210
```

---

# Valid Examples

```text
9876543210
9123456789
8765432109
7654321098
6543210987
+919876543210
```

---

# Invalid Examples

```text
5876543210
1234567890
987654321
98765432101
98A6543210
98765-43210
```

Reasons:

- Starts with an invalid digit.
- Contains fewer than 10 digits.
- Contains more than 10 digits.
- Contains alphabetic characters.
- Contains special characters.

---

# Advantages

- Improves data accuracy.
- Prevents invalid phone numbers.
- Supports OTP verification.
- Enhances user experience.
- Reduces server-side validation errors.
- Easy to implement.

---

# Best Practices

- Use `type="tel"` for phone number fields.
- Combine `required` and `pattern`.
- Provide meaningful `title` messages.
- Allow country code only when required.
- Validate again on the server.
- Test multiple valid and invalid inputs.

---

# Real-World Applications

Indian mobile number validation is commonly used in:

- User Registration Systems
- Banking Applications
- UPI Payment Platforms
- E-Commerce Websites
- Healthcare Portals
- Educational Institutions
- Government Services
- Delivery Applications
- Customer Support Systems
- Enterprise Applications

---

# Summary

Indian mobile number validation ensures that users provide correctly formatted mobile numbers before submitting a form. By combining the HTML5 `tel` input type with the `pattern` attribute and Regular Expressions, developers can validate both standard 10-digit mobile numbers and numbers with the optional `+91` country code. This approach improves user experience, enhances data quality, and supports reliable communication in modern web applications.
