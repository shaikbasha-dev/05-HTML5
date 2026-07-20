# Lang Attribute

## Introduction

The `lang` attribute is a global HTML5 attribute used to specify the natural language of an HTML document or a specific HTML element. It helps web browsers, search engines, screen readers, translation tools, and other assistive technologies correctly interpret the language of the content.

Using the `lang` attribute improves accessibility, enhances search engine optimization (SEO), supports automatic translation services, and provides a better experience for users across different regions and languages.

Although the `lang` attribute can be applied to any HTML element, it is most commonly used in the `<html>` element to define the primary language of the entire web page.

---

# What is the `lang` Attribute?

The `lang` attribute specifies the language of an HTML document or an individual HTML element.

Syntax:

```html
<element lang="language-code">
    Content
</element>
```

Example:

```html
<html lang="en">
```

Here:

- `lang` is the attribute.
- `en` is the language code representing English.

---

# Why Use the `lang` Attribute?

The `lang` attribute is used to:

- Specify the language of content.
- Improve accessibility for screen readers.
- Help search engines understand page language.
- Support browser translation features.
- Improve pronunciation by assistive technologies.
- Enhance multilingual websites.

---

# Basic Example

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <title>HTML5 Tutorial</title>

</head>

<body>

    <h1>

        Welcome to HTML5

    </h1>

</body>

</html>
```

The entire document is identified as English.

---

# Using Different Languages

The `lang` attribute can also be applied to individual elements.

Example:

```html
<p lang="fr">

    Bonjour tout le monde

</p>

<p lang="es">

    Hola Mundo

</p>

<p lang="te">

    నమస్తే ప్రపంచం

</p>
```

Each paragraph is identified using its respective language.

---

# Common Language Codes

| Language | Code |
|----------|------|
| English | `en` |
| Hindi | `hi` |
| Telugu | `te` |
| Tamil | `ta` |
| Kannada | `kn` |
| French | `fr` |
| German | `de` |
| Spanish | `es` |
| Japanese | `ja` |
| Chinese | `zh` |

---

# Advantages

- Improves accessibility.
- Supports screen readers.
- Helps automatic translation.
- Improves SEO.
- Enhances multilingual support.
- Follows HTML5 standards.

---

# Best Practices

- Always specify the language on the `<html>` element.
- Use valid ISO language codes.
- Apply different `lang` values for multilingual content.
- Keep language information accurate.
- Test with accessibility tools.
- Follow HTML5 recommendations.

---

# Real-World Applications

The `lang` attribute is widely used in:

- Educational Websites
- Government Portals
- Banking Applications
- E-Commerce Websites
- News Portals
- Blogging Platforms
- Documentation Websites
- Multilingual Applications
- Healthcare Systems
- Enterprise Web Applications

---

# Summary

The HTML5 `lang` attribute identifies the language of an HTML document or individual elements, enabling browsers, search engines, translation services, and assistive technologies to process content correctly. Proper use of the `lang` attribute improves accessibility, SEO, multilingual support, and the overall user experience, making it an essential part of standards-compliant web development.
