# Validation Messages

## Introduction

Validation messages are notifications displayed by the browser or application when user input does not satisfy specified validation rules. These messages help users understand why a form cannot be submitted and guide them in correcting invalid or incomplete input.

HTML5 provides built-in validation messages for form controls such as required fields, email addresses, URLs, numbers, dates, and pattern matching. Developers can also create custom validation messages using JavaScript for a better user experience.

Providing clear and meaningful validation messages improves usability, reduces user frustration, and increases the likelihood of successful form submissions.

---

# What are Validation Messages?

Validation messages are feedback displayed when user input fails to meet one or more validation rules.

These messages inform users about:

- Missing required values.
- Invalid email addresses.
- Incorrect URL formats.
- Values outside the allowed range.
- Pattern mismatches.
- Input length violations.
- Invalid numeric values.

---

# Common HTML5 Validation Messages

Some commonly displayed browser validation messages include:

### Required Field

```text
Please fill out this field.
```

---

### Invalid Email

```text
Please include an '@' in the email address.
```

---

### Invalid URL

```text
Please enter a URL.
```

---

### Number Out of Range

```text
Value must be greater than or equal to the minimum value.
```

or

```text
Value must be less than or equal to the maximum value.
```

---

### Pattern Mismatch

```text
Please match the requested format.
```

---

### Input Too Short

```text
Please lengthen this text.
```

---

### Input Too Long

```text
Please shorten this text.
```

---

# Example Using Built-in Validation

```html
<form>

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

    <input
        type="submit"
        value="Submit"
    >

</form>
```

If the email address is invalid or empty, the browser automatically displays an appropriate validation message.

---

# Custom Validation Messages

HTML5 allows developers to create custom validation messages using JavaScript and the `setCustomValidity()` method.

### Example

```html
<input
    type="text"
    id="username"
    required
    oninvalid="this.setCustomValidity('Username is required.')"
    oninput="this.setCustomValidity('')"
>
```

In this example, a custom message is displayed when the username field is empty.

---

# Advantages of Custom Validation Messages

- More user-friendly.
- Easier to understand.
- Can match application terminology.
- Improves accessibility.
- Enhances overall user experience.
- Provides specific guidance for correcting input.

---

# Best Practices

- Use clear and concise language.
- Explain exactly what is wrong.
- Tell users how to fix the error.
- Avoid technical jargon.
- Keep messages consistent throughout the application.
- Highlight invalid fields visually when possible.
- Combine client-side and server-side validation.

---

# Real-World Applications

Validation messages are used in:

- User Registration Forms
- Login Systems
- Banking Applications
- E-commerce Checkout Pages
- Student Admission Forms
- Employee Registration Systems
- Healthcare Portals
- Online Booking Systems
- Government Service Portals
- Customer Feedback Forms

---

# Browser Validation vs Custom Validation

| Browser Validation | Custom Validation |
|--------------------|-------------------|
| Automatically generated. | Created by developers. |
| Standard browser messages. | Fully customizable messages. |
| Easy to implement. | Requires JavaScript. |
| Limited customization. | Complete control over user feedback. |

---

# Advantages of Effective Validation Messages

- Reduce user errors.
- Improve form completion rates.
- Increase user satisfaction.
- Enhance accessibility.
- Improve application usability.
- Provide immediate feedback.
- Support better data quality.

---

# Summary

Validation messages play a vital role in creating user-friendly web forms. HTML5 provides built-in browser validation messages for common validation rules, while JavaScript enables developers to create customized messages tailored to application requirements. By using clear, informative, and consistent validation messages along with server-side validation, developers can improve usability, reduce input errors, and build professional, reliable web applications.
