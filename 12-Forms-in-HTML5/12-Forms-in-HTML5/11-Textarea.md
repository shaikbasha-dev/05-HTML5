# Textarea

## Introduction

The `<textarea>` element is an HTML form control used to collect multi-line text input from users. Unlike the `<input>` element, which accepts only a single line of text, a textarea allows users to enter paragraphs, comments, descriptions, messages, and other lengthy content.

It is commonly used in contact forms, feedback forms, review sections, support requests, and applications where users need to provide detailed information.

---

# What is a Textarea?

A textarea is an HTML form element that provides a large text box for entering multiple lines of text.

---

# Syntax

```html
<textarea>

</textarea>
```

---

# Basic Example

```html
<label for="message">

    Message

</label>

<textarea
    id="message"
    name="message"
>

</textarea>
```

---

# Common Attributes

## rows

Specifies the visible number of text lines.

Example:

```html
<textarea rows="5">

</textarea>
```

---

## cols

Specifies the visible width of the textarea.

Example:

```html
<textarea cols="40">

</textarea>
```

---

## placeholder

Displays hint text inside the textarea.

Example:

```html
<textarea
    placeholder="Enter your feedback"
>

</textarea>
```

---

## maxlength

Limits the maximum number of characters.

Example:

```html
<textarea
    maxlength="500"
>

</textarea>
```

---

## minlength

Specifies the minimum number of characters required.

Example:

```html
<textarea
    minlength="20"
>

</textarea>
```

---

## required

Makes the textarea mandatory.

Example:

```html
<textarea
    required
>

</textarea>
```

---

## readonly

Allows users to view the content but prevents editing.

Example:

```html
<textarea
    readonly
>

Sample Text

</textarea>
```

---

## disabled

Disables the textarea.

Example:

```html
<textarea
    disabled
>

</textarea>
```

---

# Complete Example

```html
<form>

    <label for="feedback">

        Feedback

    </label>

    <br><br>

    <textarea
        id="feedback"
        name="feedback"
        rows="6"
        cols="50"
        placeholder="Enter your valuable feedback..."
        minlength="20"
        maxlength="500"
        required
    >

    </textarea>

    <br><br>

    <input
        type="submit"
        value="Submit Feedback"
    >

</form>
```

---

# Advantages

- Supports multi-line text input.
- Easy to use and implement.
- Suitable for lengthy information.
- Supports HTML5 validation.
- Easily styled using CSS.
- Compatible with JavaScript.
- Fully supported by modern browsers.

---

# Best Practices

- Always provide a descriptive label.
- Use meaningful placeholder text.
- Set appropriate `rows` and `cols` values.
- Use `maxlength` to limit excessive input.
- Apply the `required` attribute when necessary.
- Avoid making the textarea unnecessarily large.
- Validate user input on the server side.

---

# Real-World Applications

- Contact Forms
- Feedback Forms
- Customer Reviews
- Product Reviews
- Support Requests
- Job Applications
- Complaint Forms
- Project Descriptions
- Blog Comments
- Survey Responses

---

# Differences Between Input and Textarea

| Input Element | Textarea |
|--------------|----------|
| Single-line input | Multi-line input |
| Uses the `<input>` element | Uses the `<textarea>` element |
| Suitable for short text | Suitable for long text |
| Cannot display multiple lines | Displays multiple lines |

---

# Summary

The HTML5 `<textarea>` element is an essential form control for collecting multi-line user input. It is widely used wherever detailed information is required, such as feedback, comments, reviews, and descriptions. By using appropriate attributes and following best practices, developers can create accessible, user-friendly, and efficient forms.
