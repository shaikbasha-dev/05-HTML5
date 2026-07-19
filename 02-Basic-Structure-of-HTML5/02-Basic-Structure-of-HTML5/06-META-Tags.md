# META Tags

## Introduction

META tags provide metadata about an HTML document. Metadata is information about the webpage that is not displayed directly to users but is used by web browsers, search engines, and other web services to understand and process the webpage correctly.

META tags are placed inside the `<head>` section of an HTML document. They define information such as character encoding, viewport settings, page description, author details, keywords, and other document-related properties.

Using appropriate META tags improves browser compatibility, search engine optimization (SEO), accessibility, and the overall user experience.

---

# Definition

META tags are HTML elements that provide metadata describing various properties of a webpage. They help browsers, search engines, and external applications interpret the document correctly.

---

# Syntax

```html
<meta attribute="value">
```

Example:

```html
<meta charset="UTF-8">
```

---

# Common META Tags

| META Tag | Purpose |
|----------|---------|
| `<meta charset="UTF-8">` | Specifies character encoding |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | Makes webpages responsive |
| `<meta name="description" content="...">` | Provides page description for search engines |
| `<meta name="keywords" content="...">` | Specifies webpage keywords |
| `<meta name="author" content="...">` | Specifies the document author |
| `<meta http-equiv="refresh" content="5">` | Refreshes or redirects the webpage |

---

# Example

```html
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Learning HTML5 META Tags">

    <meta name="keywords"
          content="HTML5, META Tags, Web Development">

    <meta name="author"
          content="Shaik Mahaboob Basha">

    <title>META Tags Example</title>

</head>

<body>

    <h1>HTML5 META Tags</h1>

    <p>
        This webpage demonstrates commonly used META tags in HTML5.
    </p>

</body>

</html>
```

---

# Why are META Tags Important?

META tags:

- Provide document metadata.
- Improve Search Engine Optimization (SEO).
- Configure responsive web design.
- Define character encoding.
- Help browsers correctly interpret webpages.
- Improve accessibility.
- Support social media sharing and web services.

---

# Advantages

- Improves browser compatibility.
- Enhances SEO.
- Supports responsive design.
- Defines document information.
- Improves webpage accessibility.
- Makes webpages easier for search engines to understand.

---

# Best Practices

- Always specify UTF-8 character encoding.
- Include the viewport META tag for responsive websites.
- Write meaningful page descriptions.
- Keep META descriptions concise and relevant.
- Specify the document author when appropriate.
- Avoid excessive or irrelevant keywords.

---

# Common Mistakes

- Forgetting the character encoding META tag.
- Missing the viewport META tag.
- Writing duplicate META descriptions.
- Using excessive keywords.
- Placing META tags outside the HEAD section.

---

# Interview Questions

### 1. What are META tags?

META tags provide metadata about an HTML document that is used by browsers, search engines, and external applications.

---

### 2. Where are META tags placed?

Inside the `<head>` section.

---

### 3. Which META tag makes webpages responsive?

```html
<meta name="viewport"
      content="width=device-width, initial-scale=1.0">
```

---

### 4. Which META tag specifies character encoding?

```html
<meta charset="UTF-8">
```

---

### 5. Why are META tags important?

They improve browser compatibility, SEO, accessibility, responsiveness, and provide important information about the webpage.

---

# Summary

META tags are essential components of every HTML5 document. Although they are not visible to users, they provide valuable information that helps browsers, search engines, and web services understand and process webpages correctly. Proper use of META tags results in responsive, accessible, SEO-friendly, and standards-compliant websites.
