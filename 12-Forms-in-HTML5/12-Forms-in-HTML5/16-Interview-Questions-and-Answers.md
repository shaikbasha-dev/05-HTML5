# Interview Questions and Answers

## Introduction

This section contains frequently asked HTML5 Forms interview questions along with concise and practical answers. These questions help learners revise important concepts and prepare for technical interviews, coding assessments, and certification examinations.

---

# 1. What is an HTML Form?

**Answer:**

An HTML Form is a container used to collect user input and submit it to a server for processing. It is created using the `<form>` element.

---

# 2. Which HTML element is used to create a form?

**Answer:**

The `<form>` element.

Example:

```html
<form>

</form>
```

---

# 3. What is the purpose of the `action` attribute?

**Answer:**

The `action` attribute specifies the URL where the form data will be sent after submission.

Example:

```html
<form action="register.php">
```

---

# 4. What is the purpose of the `method` attribute?

**Answer:**

It specifies the HTTP method used to send form data.

Common values:

- GET
- POST

---

# 5. What is the difference between GET and POST?

| GET | POST |
|------|------|
| Data is appended to the URL | Data is sent in the request body |
| Less secure | More secure |
| Limited data size | Supports larger data |
| Suitable for searching | Suitable for registration and login |

---

# 6. Which input type is used for email addresses?

**Answer:**

```html
<input type="email">
```

---

# 7. Which input type is used for passwords?

**Answer:**

```html
<input type="password">
```

---

# 8. What is the purpose of the `required` attribute?

**Answer:**

The `required` attribute makes a form field mandatory before the form can be submitted.

---

# 9. What is the purpose of the `<label>` element?

**Answer:**

The `<label>` element provides a descriptive label for a form control and improves accessibility.

---

# 10. What is the purpose of the `placeholder` attribute?

**Answer:**

It displays hint text inside an input field until the user enters a value.

---

# 11. What is the difference between radio buttons and checkboxes?

| Radio Buttons | Checkboxes |
|--------------|------------|
| Single selection | Multiple selections |
| Circular control | Square control |
| Same `name` attribute | Independent selections |

---

# 12. What is the purpose of the `<textarea>` element?

**Answer:**

The `<textarea>` element is used to collect multi-line text input from users.

---

# 13. What is the purpose of the `<select>` element?

**Answer:**

The `<select>` element creates a dropdown list containing predefined options.

---

# 14. What is the purpose of `<fieldset>`?

**Answer:**

`<fieldset>` groups related form controls into a logical section.

---

# 15. What is the purpose of `<legend>`?

**Answer:**

`<legend>` provides a caption or title for a `<fieldset>`.

---

# 16. Which attribute allows multiple selections in a dropdown?

**Answer:**

```html
multiple
```

---

# 17. Which input type displays a slider?

**Answer:**

```html
<input type="range">
```

---

# 18. Which input type displays a calendar picker?

**Answer:**

```html
<input type="date">
```

---

# 19. What is the purpose of the `autocomplete` attribute?

**Answer:**

It allows browsers to automatically fill previously entered values.

---

# 20. Why are HTML5 Forms important?

**Answer:**

HTML5 Forms enable interactive user input, provide built-in validation, improve accessibility, enhance user experience, and simplify data collection for modern web applications.

---

# Quick Revision Points

- `<form>` creates a form.
- `<input>` collects user input.
- `<label>` improves accessibility.
- `<textarea>` accepts multi-line text.
- `<select>` creates dropdown lists.
- `<option>` defines dropdown items.
- `<fieldset>` groups related controls.
- `<legend>` provides a group title.
- `GET` retrieves data.
- `POST` submits data securely.
- `required` makes fields mandatory.
- `placeholder` displays hint text.
- `checked` selects options by default.
- `multiple` enables multiple selections.
- HTML5 provides built-in validation.

---

# Summary

Understanding HTML5 Forms is essential for front-end and full-stack web development. These interview questions cover the most important concepts, including form structure, input controls, validation, accessibility, form attributes, and semantic elements. Regular revision of these questions helps build confidence for interviews and practical web development tasks.
