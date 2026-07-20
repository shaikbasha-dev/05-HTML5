# Required Attribute

## Introduction

The `required` attribute is one of the most commonly used HTML5 validation attributes. It ensures that a user cannot submit a form until the specified form field contains a value.

By using the `required` attribute, developers can prevent incomplete form submissions without writing additional JavaScript code. HTML5 browsers automatically validate required fields and display an appropriate validation message if the user attempts to submit the form without entering a value.

The `required` attribute is a Boolean attribute, meaning that its presence alone enables the validation rule.

---

# What is the Required Attribute?

The `required` attribute specifies that an input field must be filled before the form can be submitted.

If the field is left empty, the browser prevents form submission and displays a built-in validation message.

---

# Syntax

```html
<input
    type="text"
    required
>
```

---

# Basic Example

```html
<form>

    <label for="username">

        Username

    </label>

    <input
        type="text"
        id="username"
        name="username"
        required
    >

    <input
        type="submit"
        value="Submit"
    >

</form>
```

---

# Supported Form Controls

The `required` attribute can be used with many HTML5 form controls, including:

- Text Input
- Password Input
- Email Input
- URL Input
- Number Input
- Date Input
- Time Input
- Search Input
- Telephone Input
- Textarea
- Select Dropdown
- Radio Buttons
- Checkboxes (when at least one selection is required)
- File Upload

---

# How the Required Attribute Works

1. User opens the form.
2. Required fields are displayed.
3. User leaves a required field empty.
4. User clicks the submit button.
5. Browser checks the required fields.
6. Validation fails if any required field is empty.
7. Browser displays a validation message.
8. Form submission is blocked until all required fields are completed.

---

# Complete Example

```html
<form>

    <label for="fullname">

        Full Name

    </label>

    <input
        type="text"
        id="fullname"
        name="fullname"
        required
    >

    <br><br>

    <label for="email">

        Email Address

    </label>

    <input
        type="email"
        id="email"
        name="email"
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
        minlength="8"
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

- Prevents empty form submissions.
- Improves data quality.
- Provides instant validation.
- Reduces JavaScript code.
- Enhances user experience.
- Easy to implement.
- Supported by all modern browsers.

---

# Best Practices

- Use the `required` attribute only for mandatory fields.
- Combine `required` with suitable input types.
- Provide clear labels for required fields.
- Display meaningful instructions to users.
- Always perform server-side validation as well.
- Test validation across different browsers.
- Avoid making every field mandatory unless necessary.

---

# Real-World Applications

The `required` attribute is widely used in:

- User Registration Forms
- Login Forms
- Contact Forms
- College Admission Forms
- Job Application Forms
- Banking Applications
- Healthcare Portals
- E-commerce Checkout Pages
- Feedback Forms
- Survey Forms

---

# Summary

The HTML5 `required` attribute provides a simple and effective way to ensure that mandatory form fields are completed before submission. It improves user experience by offering immediate feedback and reduces the need for custom validation scripts. However, since client-side validation can be bypassed, the `required` attribute should always be used together with server-side validation to ensure complete data integrity and security.
