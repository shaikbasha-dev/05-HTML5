# Email Validation

## Introduction

Email validation is one of the most commonly used HTML5 form validation techniques. It ensures that users enter an email address in a valid format before submitting a form. HTML5 simplifies this process through the `email` input type, eliminating the need for complex JavaScript validation for basic email format checking.

Using HTML5 email validation improves data quality, enhances user experience, and reduces invalid form submissions. However, while HTML5 validates the structure of an email address, it does not verify whether the email address actually exists. Therefore, server-side validation and email verification are still required for production applications.

---

# What is Email Validation?

Email validation is the process of checking whether the entered email address follows the standard email format.

A valid email address generally contains:

- A username (local part)
- The `@` symbol
- A domain name
- A valid domain extension

Example:

```text
username@example.com
```

---

# HTML5 Email Input Type

HTML5 provides the `email` input type specifically for validating email addresses.

### Syntax

```html
<input
    type="email"
>
```

---

# Basic Example

```html
<label for="email">

    Email Address

</label>

<input
    type="email"
    id="email"
    name="email"
    required
>
```

If the user enters an invalid email format, the browser displays a validation message and prevents form submission.

---

# Multiple Email Addresses

The `multiple` attribute allows users to enter more than one email address.

```html
<input
    type="email"
    multiple
>
```

Example input:

```text
john@example.com, jane@example.com
```

Each email address must follow the correct format.

---

# Using Placeholder

```html
<input
    type="email"
    placeholder="example@domain.com"
    required
>
```

A placeholder provides users with an example of the expected input format.

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
        placeholder="example@domain.com"
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

# Common Invalid Email Examples

The following email addresses are invalid:

```text
userexample.com
```

(Missing `@` symbol)

```text
user@
```

(Missing domain name)

```text
@example.com
```

(Missing username)

```text
user@domain
```

(Missing valid domain extension)

---

# Advantages

- Built-in browser validation.
- Easy to implement.
- Improves data quality.
- Reduces invalid submissions.
- Enhances user experience.
- Requires minimal code.
- Supported by all modern browsers.

---

# Best Practices

- Always use `type="email"` for email fields.
- Combine with the `required` attribute for mandatory email addresses.
- Use meaningful placeholders.
- Provide clear labels.
- Perform email validation again on the server.
- Verify email ownership using confirmation emails when necessary.
- Never rely solely on client-side validation.

---

# Real-World Applications

Email validation is widely used in:

- User Registration Forms
- Login Systems
- Contact Forms
- Newsletter Subscription Forms
- Banking Applications
- E-commerce Websites
- Educational Portals
- Job Application Forms
- Customer Support Forms
- Online Booking Systems

---

# Difference Between Format Validation and Email Verification

| Email Format Validation | Email Verification |
|--------------------------|--------------------|
| Checks whether the email follows the correct format. | Confirms that the email address actually exists. |
| Performed by the browser. | Usually performed by the server or email service. |
| Fast and automatic. | Requires additional verification methods. |
| Does not confirm ownership. | Can confirm ownership through verification emails. |

---

# Summary

The HTML5 `email` input type provides an efficient way to validate the format of email addresses using built-in browser functionality. It enhances user experience by preventing incorrectly formatted email addresses from being submitted. However, format validation alone does not guarantee that an email address exists or belongs to the user. For secure and reliable applications, HTML5 email validation should always be combined with server-side validation and email verification techniques.
