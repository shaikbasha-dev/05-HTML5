# Minlength and Maxlength

## Introduction

Phone numbers usually have a fixed or limited number of digits depending on the country's numbering plan. HTML5 provides the `minlength` and `maxlength` attributes to restrict the minimum and maximum number of characters that users can enter into an input field.

These attributes help improve data quality by preventing users from entering phone numbers that are too short or too long. They are commonly used with the `tel` input type and are often combined with the `required` and `pattern` attributes for complete client-side validation.

---

# What are `minlength` and `maxlength`?

The `minlength` attribute specifies the minimum number of characters that must be entered.

The `maxlength` attribute specifies the maximum number of characters allowed.

Together, they define the acceptable length of user input.

---

# Syntax

```html
<input
    type="tel"
    minlength="10"
    maxlength="10">
```

---

# Basic Example

```html
<label for="phone">

    Mobile Number

</label>

<input
    type="tel"
    id="phone"
    name="phone"
    minlength="10"
    maxlength="10"
    required>
```

In this example:

- Users must enter at least 10 characters.
- Users cannot enter more than 10 characters.

---

# Example with Pattern Validation

```html
<input
    type="tel"
    id="phone"
    name="phone"
    minlength="10"
    maxlength="10"
    pattern="[6-9][0-9]{9}"
    title="Enter a valid 10-digit Indian mobile number."
    required>
```

This example combines:

- `type="tel"`
- `required`
- `minlength`
- `maxlength`
- `pattern`

to provide more reliable client-side validation.

---

# Browser Behavior

When validation occurs:

- If fewer than the minimum characters are entered, validation fails.
- If more than the maximum characters are entered, additional characters cannot be typed.
- If the input does not match the specified pattern, form submission is prevented.
- The browser displays an appropriate validation message.

---

# Advantages

- Restricts input length.
- Improves data accuracy.
- Reduces user mistakes.
- Enhances user experience.
- Works without JavaScript.
- Easy to implement.

---

# Best Practices

- Use `minlength` and `maxlength` together when the phone number length is fixed.
- Combine them with the `pattern` attribute.
- Provide helpful `placeholder` and `title` values.
- Validate phone numbers again on the server.
- Test validation across multiple browsers.

---

# Real-World Applications

Length validation is commonly used in:

- User Registration Forms
- Banking Applications
- Online Shopping Websites
- Student Admission Portals
- Employee Registration Systems
- Healthcare Applications
- Government Service Portals
- Customer Support Forms
- CRM Systems
- Enterprise Applications

---

# Comparison

| Attribute | Purpose |
|-----------|---------|
| `minlength` | Specifies the minimum number of characters required |
| `maxlength` | Specifies the maximum number of characters allowed |

---

# Summary

The HTML5 `minlength` and `maxlength` attributes provide a simple and effective way to control the length of phone number input. When combined with the `tel` input type, the `required` attribute, and regular expressions using the `pattern` attribute, they help developers build reliable, user-friendly, and professional phone number validation for modern web applications.
