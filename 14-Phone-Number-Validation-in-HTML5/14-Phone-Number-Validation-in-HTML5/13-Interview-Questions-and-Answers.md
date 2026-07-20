# Interview Questions and Answers

## Introduction

Interview questions on phone number validation are commonly asked during HTML5, Frontend Development, JavaScript, and Full Stack Developer interviews. These questions assess a candidate's understanding of HTML5 form validation, regular expressions, JavaScript validation, and best practices for collecting phone numbers securely and accurately.

This document provides frequently asked interview questions with concise and professional answers.

---

# 1. What is phone number validation?

**Answer:**

Phone number validation is the process of verifying that a user enters a phone number in the expected format before the data is accepted or submitted.

---

# 2. Which HTML5 input type is used for phone numbers?

**Answer:**

The `tel` input type is used for phone number fields.

Example:

```html
<input type="tel">
```

---

# 3. Does `type="tel"` validate phone numbers automatically?

**Answer:**

No.

The `tel` input type only indicates that the field is intended for phone numbers. Developers must use attributes like `pattern`, `required`, `minlength`, and `maxlength`, or JavaScript for validation.

---

# 4. Which attribute makes a phone number mandatory?

**Answer:**

The `required` attribute.

Example:

```html
<input
    type="tel"
    required>
```

---

# 5. Which attribute is used to validate a specific phone number format?

**Answer:**

The `pattern` attribute.

Example:

```html
<input
    type="tel"
    pattern="[6-9][0-9]{9}">
```

---

# 6. What is a Regular Expression (Regex)?

**Answer:**

A Regular Expression is a pattern used to match and validate text according to predefined rules.

---

# 7. Why is JavaScript used for phone number validation?

**Answer:**

JavaScript provides advanced validation, custom validation messages, dynamic checks, and business-specific validation rules that cannot always be implemented using HTML5 attributes alone.

---

# 8. Why is server-side validation necessary?

**Answer:**

Client-side validation can be bypassed. Server-side validation ensures that submitted phone numbers are verified securely before processing or storing them.

---

# 9. What is the purpose of the `placeholder` attribute?

**Answer:**

It displays an example or hint inside the input field before the user enters data.

---

# 10. What is the purpose of the `title` attribute?

**Answer:**

It provides additional guidance and is commonly displayed by browsers when validation fails.

---

# 11. What does the `minlength` attribute do?

**Answer:**

It specifies the minimum number of characters that the user must enter.

---

# 12. What does the `maxlength` attribute do?

**Answer:**

It limits the maximum number of characters that can be entered into the input field.

---

# 13. What is `setCustomValidity()`?

**Answer:**

It is a JavaScript method that displays a developer-defined validation message instead of the browser's default validation message.

---

# 14. Which method immediately displays a validation message?

**Answer:**

The `reportValidity()` method.

---

# 15. What are the best practices for phone number validation?

**Answer:**

- Use `type="tel"`.
- Apply `required` where necessary.
- Use `pattern` for format validation.
- Provide meaningful labels and placeholders.
- Use JavaScript only when needed.
- Always perform server-side validation.
- Test across different browsers and devices.

---

# Summary

Understanding phone number validation is essential for building modern web applications. Interviewers frequently ask questions about the `tel` input type, validation attributes, regular expressions, JavaScript validation, and server-side validation. Mastering these concepts helps developers build secure, reliable, and user-friendly forms while preparing effectively for technical interviews.
