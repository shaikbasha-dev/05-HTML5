# Required Phone Number Validation

## Introduction

In many web applications, providing a phone number is mandatory. Applications such as banking systems, e-commerce platforms, educational portals, healthcare services, and user registration systems rely on valid phone numbers for communication, authentication, and verification.

HTML5 simplifies this requirement through the `required` attribute. When applied to a phone number input field, the browser automatically prevents form submission if the field is left empty.

---

# What is the `required` Attribute?

The `required` attribute is an HTML5 boolean attribute that makes an input field mandatory.

When a required field is empty and the user attempts to submit the form, the browser displays a validation message and stops the submission.

---

# Syntax

```html
<input
    type="tel"
    required>
```

---

# Basic Example

```html
<form>

    <label for="phone">

        Mobile Number

    </label>

    <input
        type="tel"
        id="phone"
        name="phone"
        required>

    <input
        type="submit"
        value="Submit">

</form>
```

If the user leaves the phone number field empty, the browser automatically displays a validation message.

---

# Example with Placeholder

```html
<input
    type="tel"
    placeholder="Enter your mobile number"
    required>
```

The placeholder provides guidance while the `required` attribute ensures that the field cannot be left blank.

---

# Example with Pattern Validation

```html
<input
    type="tel"
    pattern="[0-9]{10}"
    title="Enter a valid 10-digit mobile number."
    required>
```

In this example:

- `required` ensures the field is not empty.
- `pattern` ensures the number contains exactly 10 digits.
- `title` displays a helpful validation message.

---

# Browser Behavior

When the form is submitted:

- If the field is empty, submission is prevented.
- The browser highlights the field.
- A built-in validation message is displayed.
- After entering a value, the form can be validated further using other attributes.

---

# Advantages

- Easy to implement.
- No JavaScript required.
- Improves user experience.
- Prevents incomplete form submissions.
- Supported by all modern browsers.
- Works seamlessly with other validation attributes.

---

# Real-World Applications

The `required` attribute is commonly used in:

- User Registration Forms
- Contact Forms
- Banking Applications
- Online Shopping Websites
- Student Registration Systems
- Employee Registration Forms
- Healthcare Portals
- Government Applications
- Customer Support Forms
- Enterprise Web Applications

---

# Best Practices

- Always use `required` for mandatory phone number fields.
- Combine it with `type="tel"` for semantic correctness.
- Use `pattern` to enforce phone number formats.
- Provide clear placeholders and labels.
- Validate the phone number again on the server.
- Display user-friendly validation messages.

---

# Summary

The `required` attribute is the simplest and most effective way to ensure that users provide a phone number before submitting a form. When combined with the `tel` input type and additional validation attributes such as `pattern`, it helps developers build reliable, user-friendly, and professional HTML5 forms while improving data quality and reducing incomplete submissions.
