# Custom Validation

## Introduction

While HTML5 provides built-in validation for many common scenarios, some applications require validation rules that cannot be achieved using standard HTML attributes alone. In such cases, developers can use JavaScript to implement custom validation.

Custom validation allows developers to define their own validation logic, display personalized error messages, and enforce complex business rules before a form is submitted.

HTML5 provides the `setCustomValidity()` method through the Constraint Validation API, enabling developers to create meaningful validation messages while still using the browser's validation mechanism.

---

# What is Custom Validation?

Custom validation is the process of validating user input using developer-defined rules instead of relying solely on built-in HTML5 validation.

It is useful when validation depends on:

- Business rules
- Multiple input fields
- Password confirmation
- Age restrictions
- Username availability
- Custom formats
- Application-specific requirements

---

# Why Use Custom Validation?

Custom validation helps developers:

- Implement complex validation rules.
- Display meaningful error messages.
- Improve user experience.
- Reduce incorrect submissions.
- Enforce business requirements.
- Validate relationships between multiple fields.
- Provide consistent validation behavior.

---

# HTML5 Constraint Validation API

HTML5 provides several methods and properties for custom validation.

Common methods include:

- `setCustomValidity()`
- `checkValidity()`
- `reportValidity()`

Common properties include:

- `validity`
- `validationMessage`
- `willValidate`

---

# Using `setCustomValidity()`

The `setCustomValidity()` method defines a custom validation message.

## Syntax

```javascript
element.setCustomValidity("Custom validation message");
```

To remove the custom message:

```javascript
element.setCustomValidity("");
```

---

# Basic Example

```html
<input
    type="text"
    id="username"
    required
>

<script>

const username = document.getElementById("username");

username.addEventListener("input", function () {

    if (this.value.length < 5) {

        this.setCustomValidity("Username must contain at least 5 characters.");

    } else {

        this.setCustomValidity("");

    }

});

</script>
```

---

# Password Confirmation Example

```html
<input
    type="password"
    id="password"
    placeholder="Password"
    required
>

<input
    type="password"
    id="confirmPassword"
    placeholder="Confirm Password"
    required
>

<script>

const password = document.getElementById("password");
const confirmPassword = document.getElementById("confirmPassword");

function validatePassword() {

    if (password.value !== confirmPassword.value) {

        confirmPassword.setCustomValidity("Passwords do not match.");

    } else {

        confirmPassword.setCustomValidity("");

    }

}

password.oninput = validatePassword;
confirmPassword.oninput = validatePassword;

</script>
```

---

# Age Validation Example

```javascript
const age = document.getElementById("age");

age.addEventListener("input", function () {

    if (this.value < 18) {

        this.setCustomValidity("Minimum age should be 18 years.");

    } else {

        this.setCustomValidity("");

    }

});
```

---

# Advantages

- Supports complex validation rules.
- Provides personalized error messages.
- Improves user experience.
- Integrates with HTML5 validation.
- Reduces invalid submissions.
- Highly flexible.
- Supports business-specific requirements.

---

# Best Practices

- Use built-in HTML5 validation whenever possible.
- Keep validation messages simple and meaningful.
- Clear custom messages after valid input.
- Validate data on both the client and server.
- Avoid unnecessary JavaScript complexity.
- Test validation across multiple browsers.
- Ensure accessibility for all users.

---

# Real-World Applications

Custom validation is commonly used in:

- User Registration Systems
- Banking Applications
- Password Confirmation Forms
- Employee Registration
- Student Admission Portals
- Online Shopping Websites
- Healthcare Systems
- Government Service Portals
- Booking Applications
- Enterprise Business Systems

---

# Built-in Validation vs Custom Validation

| Built-in Validation | Custom Validation |
|---------------------|-------------------|
| Uses HTML5 attributes. | Uses JavaScript. |
| Easy to implement. | Supports complex logic. |
| Limited customization. | Fully customizable. |
| Standard browser messages. | Personalized validation messages. |
| Suitable for common validation. | Suitable for business-specific validation. |

---

# Summary

Custom validation extends the capabilities of HTML5 form validation by allowing developers to create application-specific validation rules using JavaScript. Through the Constraint Validation API and methods such as `setCustomValidity()`, developers can provide meaningful feedback, enforce complex business logic, and improve the overall user experience. For secure web applications, custom client-side validation should always be combined with server-side validation.
