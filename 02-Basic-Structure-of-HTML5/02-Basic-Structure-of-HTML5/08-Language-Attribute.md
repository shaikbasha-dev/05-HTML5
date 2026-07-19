# Language Attribute

## Introduction

The `lang` attribute specifies the primary language of an HTML document. It is added to the opening `<html>` tag and helps browsers, search engines, screen readers, and other assistive technologies correctly interpret the language of the webpage.

Although the language attribute does not change the visual appearance of a webpage, it plays a significant role in accessibility, Search Engine Optimization (SEO), pronunciation by screen readers, spell checking, and browser behavior.

For every HTML5 document, it is recommended to specify the correct language using the `lang` attribute.

---

# Definition

The `lang` attribute is a global HTML attribute that specifies the language of the content within an HTML document.

---

# Syntax

```html
<html lang="en">
```

---

# Purpose of the Language Attribute

The `lang` attribute is used to:

- Specify the language of the webpage.
- Improve accessibility.
- Help screen readers pronounce words correctly.
- Improve Search Engine Optimization (SEO).
- Assist browsers in language-specific rendering.
- Support translation tools.
- Enable accurate spell checking.

---

# Common Language Codes

| Language | Code |
|----------|------|
| English | `en` |
| English (United States) | `en-US` |
| English (United Kingdom) | `en-GB` |
| Hindi | `hi` |
| Telugu | `te` |
| Tamil | `ta` |
| French | `fr` |
| German | `de` |
| Spanish | `es` |
| Japanese | `ja` |
| Chinese | `zh` |
| Arabic | `ar` |

---

# Example

```html
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">

    <title>Language Attribute Example</title>

</head>

<body>

    <h1>Welcome to HTML5</h1>

    <p>
        This webpage uses English as its primary language.
    </p>

</body>

</html>
```

---

# Why is the Language Attribute Important?

The language attribute:

- Improves accessibility.
- Helps screen readers read content correctly.
- Supports browser translation.
- Improves SEO.
- Enables proper spell checking.
- Makes webpages internationally compatible.

---

# Advantages

- Better accessibility.
- Improved SEO.
- Accurate pronunciation by assistive technologies.
- Better browser compatibility.
- Improved translation support.
- Enhanced user experience.

---

# Best Practices

- Always specify the `lang` attribute.
- Use valid ISO language codes.
- Match the language code with the primary webpage language.
- Update the language attribute when creating multilingual websites.
- Keep the language declaration at the root `<html>` element.

---

# Common Mistakes

- Omitting the `lang` attribute.
- Using incorrect language codes.
- Specifying a language different from the webpage content.
- Placing the language attribute on the wrong element.
- Using non-standard language abbreviations.

---

# Interview Questions

### 1. What is the purpose of the `lang` attribute?

It specifies the language of an HTML document, helping browsers, search engines, and assistive technologies correctly interpret the webpage.

---

### 2. Where is the `lang` attribute specified?

Inside the opening `<html>` tag.

Example:

```html
<html lang="en">
```

---

### 3. Does the `lang` attribute affect webpage appearance?

No. It does not change the visual appearance of the webpage but improves accessibility, SEO, and browser behavior.

---

### 4. Which standard is followed for language codes?

ISO language codes (such as `en`, `fr`, `hi`, `te`, and `ja`).

---

### 5. Why should every HTML document include the `lang` attribute?

Because it improves accessibility, search engine optimization, translation support, spell checking, and browser interpretation.

---

# Summary

The `lang` attribute is a simple yet essential part of every HTML5 document. By specifying the document's primary language, developers improve accessibility, browser compatibility, search engine optimization, and the overall user experience. Including the `lang` attribute is considered a modern HTML5 best practice and should be followed in every webpage.
