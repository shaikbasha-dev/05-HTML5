# DOCTYPE Declaration

## Introduction

The DOCTYPE declaration is the very first line of an HTML document. It informs the web browser about the version of HTML used to create the webpage. In HTML5, the DOCTYPE declaration is simple and standardized, allowing browsers to render web pages in standards mode.

Although the DOCTYPE declaration is not an HTML tag, it is an essential part of every HTML5 document.

---

# Definition

The DOCTYPE declaration is a special instruction placed at the beginning of an HTML document that tells the browser the document type and HTML version being used.

---

# Syntax

```html
<!DOCTYPE html>
```

---

# Explanation

- `<!DOCTYPE>` is the declaration keyword.
- `html` specifies that the document follows the HTML5 standard.
- It must always be the first line of an HTML document.
- It is not enclosed within the `<html>` element.
- It is not case-sensitive, but the lowercase form is the recommended standard.

---

# Why is DOCTYPE Important?

The DOCTYPE declaration:

- Enables standards mode in browsers.
- Prevents browsers from entering Quirks Mode.
- Ensures consistent rendering across browsers.
- Improves compatibility with modern HTML5 features.
- Helps developers follow web standards.

---

# Example

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>DOCTYPE Example</title>
</head>

<body>

    <h1>Welcome to HTML5</h1>

</body>

</html>
```

---

# DOCTYPE in HTML5 vs Older HTML Versions

| HTML Version | DOCTYPE Declaration |
|--------------|---------------------|
| HTML5 | `<!DOCTYPE html>` |
| HTML 4.01 | Long and complex declaration |
| XHTML 1.0 | XML-based lengthy declaration |

HTML5 simplifies the declaration to a single line, making it easier to remember and use.

---

# Advantages

- Simple syntax.
- Easy to remember.
- Ensures browser compatibility.
- Activates standards mode.
- Supports all HTML5 features.
- Recommended for every HTML document.

---

# Best Practices

- Always place the DOCTYPE declaration at the very beginning of the document.
- Use the HTML5 declaration: `<!DOCTYPE html>`.
- Do not place comments or blank lines before the DOCTYPE.
- Include it in every HTML page.

---

# Common Mistakes

- Omitting the DOCTYPE declaration.
- Placing comments before the DOCTYPE.
- Using outdated HTML4 or XHTML declarations unnecessarily.
- Writing the DOCTYPE after the `<html>` tag.

---

# Interview Questions

### 1. What is the purpose of the DOCTYPE declaration?

It tells the browser which version of HTML the document uses and enables standards mode.

---

### 2. Is the DOCTYPE declaration an HTML tag?

No. It is a declaration, not an HTML element.

---

### 3. Where should the DOCTYPE declaration be written?

It should always be the first line of the HTML document.

---

### 4. What is the HTML5 DOCTYPE declaration?

```html
<!DOCTYPE html>
```

---

# Summary

The DOCTYPE declaration is the starting point of every HTML5 document. It ensures browsers interpret the webpage using modern web standards, resulting in consistent rendering, improved compatibility, and better support for HTML5 features. Every HTML document should begin with the HTML5 DOCTYPE declaration.
