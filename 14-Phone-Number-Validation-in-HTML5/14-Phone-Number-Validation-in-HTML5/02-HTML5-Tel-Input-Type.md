# HTML5 `tel` Input Type

## Introduction

The HTML5 `tel` input type is specifically designed for collecting telephone and mobile numbers from users. Unlike the `text` input type, `tel` informs browsers that the expected input is a phone number. On many smartphones and tablets, it automatically displays a numeric keypad, making it easier and faster for users to enter phone numbers.

It is important to note that the `tel` input type does **not** automatically validate the phone number format. To enforce specific formats or restrictions, developers should combine it with attributes such as `required`, `pattern`, `minlength`, and `maxlength`.

---

# What is the `tel` Input Type?

The `tel` input type is an HTML5 form control used for accepting telephone or mobile numbers.

Syntax:

```html
<input type="tel">
```

It provides a semantic way to indicate that the input field is intended for phone numbers.

---

# Why Use the `tel` Input Type?

Using `type="tel"` offers several advantages:

- Indicates that the field is meant for telephone numbers.
- Displays a numeric keypad on most mobile devices.
- Improves user experience.
- Enhances form accessibility.
- Can be combined with validation attributes.
- Works well with JavaScript validation.

---

# Basic Example

```html
<label for="phone">

    Mobile Number

</label>

<input
    type="tel"
    id="phone"
    name="phone">
```

---

# Example with Required Validation

```html
<label for="phone">

    Mobile Number

</label>

<input
    type="tel"
    id="phone"
    name="phone"
    required>
```

The browser prevents form submission if the field is left empty.

---

# Example with Pattern Validation

```html
<label for="phone">

    Mobile Number

</label>

<input
    type="tel"
    id="phone"
    name="phone"
    pattern="[0-9]{10}"
    title="Enter a valid 10-digit mobile number."
    required>
```

This example accepts only a 10-digit numeric phone number.

---

# Common Validation Attributes

The `tel` input type is commonly used with:

| Attribute | Purpose |
|-----------|---------|
| `required` | Makes the field mandatory |
| `pattern` | Validates using a regular expression |
| `minlength` | Specifies the minimum number of characters |
| `maxlength` | Specifies the maximum number of characters |
| `placeholder` | Displays example input |
| `title` | Shows a custom validation hint |

---

# Advantages

- Mobile-friendly input.
- Better accessibility.
- Improved user experience.
- Easy integration with HTML5 validation.
- Supports custom validation rules.
- Compatible with all modern browsers.

---

# Real-World Applications

The `tel` input type is commonly used in:

- Registration Forms
- Contact Forms
- Online Shopping Websites
- Banking Applications
- Healthcare Systems
- Job Application Portals
- Educational Websites
- Customer Support Forms
- Government Portals
- Enterprise Applications

---

# Best Practices

- Always use `type="tel"` for phone number fields.
- Combine it with the `required` attribute.
- Use the `pattern` attribute for format validation.
- Provide a helpful `placeholder`.
- Display clear validation messages.
- Validate phone numbers again on the server.

---

# Summary

The HTML5 `tel` input type provides a semantic and user-friendly way to collect phone numbers in web forms. While it does not automatically validate the entered number, it works effectively with HTML5 validation attributes such as `required`, `pattern`, `minlength`, and `maxlength`. When combined with JavaScript and server-side validation, it helps developers build reliable, accessible, and professional web forms.
