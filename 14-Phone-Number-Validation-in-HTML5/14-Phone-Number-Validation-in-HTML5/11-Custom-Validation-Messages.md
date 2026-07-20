# Custom Validation Messages

## Introduction

HTML5 provides built-in validation messages whenever a user enters invalid data or leaves a required field empty. While these default browser messages are useful, they may differ between browsers and may not match the tone or requirements of a web application.

Custom validation messages allow developers to display meaningful, user-friendly, and application-specific error messages. Using JavaScript together with the HTML5 Constraint Validation API, developers can provide clear instructions that help users correct invalid phone numbers quickly.

---

# What are Custom Validation Messages?

Custom validation messages are developer-defined error messages that replace the browser's default validation messages.

These messages provide:

- Better user guidance.
- Consistent validation across browsers.
- Improved user experience.
- Application-specific instructions.
- Professional-looking forms.

---

# Why Use Custom Validation Messages?

Custom validation messages help developers:

- Explain validation errors clearly.
- Improve accessibility.
- Reduce user confusion.
- Guide users to correct mistakes.
- Enhance overall usability.
- Maintain consistent messaging throughout the application.

---

# Using `setCustomValidity()`

HTML5 provides the `setCustomValidity()` method to display custom validation messages.

Syntax:

```javascript
element.setCustomValidity("Your custom validation message.");
```

To remove the custom validation message:

```javascript
element.setCustomValidity("");
```

---

# Basic Example

```html
<form id="phoneForm">

    <input
        type="tel"
        id="phone"
        required>

    <input
        type="submit"
        value="Submit">

</form>

<script>

const phone =
    document.getElementById("phone");

phone.addEventListener("input", function () {

    if (phone.value.length !== 10) {

        phone.setCustomValidity(
            "Phone number must contain exactly 10 digits."
        );

    }
    else {

        phone.setCustomValidity("");

    }

});

</script>
```

---

# Using `reportValidity()`

The `reportValidity()` method immediately displays the validation message.

Example:

```javascript
phone.reportValidity();
```

This method checks the input and displays either the default or custom validation message.

---

# Browser Behavior

When validation fails:

- The browser prevents form submission.
- The custom validation message is displayed.
- The user corrects the input.
- The custom message is removed after successful validation.

---

# Advantages

- Provides meaningful error messages.
- Improves user experience.
- Reduces confusion.
- Supports complex validation logic.
- Works with HTML5 validation.
- Easy to implement.

---

# Best Practices

- Keep messages short and clear.
- Explain how to correct the error.
- Remove custom messages after successful validation.
- Combine with HTML5 validation attributes.
- Validate data again on the server.
- Test validation messages across browsers.

---

# Real-World Applications

Custom validation messages are commonly used in:

- Banking Applications
- User Registration Systems
- E-Commerce Websites
- Healthcare Portals
- Student Admission Systems
- Government Service Portals
- Customer Support Forms
- CRM Applications
- Online Booking Systems
- Enterprise Applications

---

# Summary

Custom validation messages improve the usability and professionalism of HTML5 forms by replacing generic browser messages with clear, application-specific instructions. Using the HTML5 Constraint Validation API and JavaScript methods such as `setCustomValidity()` and `reportValidity()`, developers can provide consistent validation feedback while improving accessibility, user experience, and data quality. These techniques should always be combined with server-side validation to ensure secure and reliable applications.
