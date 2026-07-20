# Image Element (`<img>`) in HTML5

## Overview

The `<img>` element is one of the most frequently used elements in HTML5. It is used to embed images into a webpage without storing the image inside the HTML document itself. Instead, the browser loads the image from the location specified by the **src** attribute.

Images improve the visual appeal of webpages, communicate information effectively, support branding, and enhance the overall user experience.

---

# What is the `<img>` Element?

The `<img>` element is an HTML5 element used to display images such as photographs, icons, logos, illustrations, banners, screenshots, diagrams, and graphics on a webpage.

Unlike most HTML elements, the `<img>` element is an **empty (void) element**, which means it does not require a closing tag.

---

# Syntax

```html
<img src="image.jpg" alt="Sample Image">
```

---

# Basic Example

```html
<!DOCTYPE html>
<html>

<head>
    <title>Image Example</title>
</head>

<body>

    <h1>HTML5 Image Example</h1>

    <img src="nature.jpg" alt="Beautiful Nature">

</body>

</html>
```

---

# Anatomy of the `<img>` Element

```html
<img
    src="flower.jpg"
    alt="Red Flower"
    width="400"
    height="250">
```

| Attribute | Description |
|-----------|-------------|
| `src` | Specifies the location (path) of the image. |
| `alt` | Displays alternative text if the image cannot be loaded. |
| `width` | Specifies the image width. |
| `height` | Specifies the image height. |

---

# How the `<img>` Element Works

The browser performs the following steps:

1. Reads the `<img>` element.
2. Reads the `src` attribute.
3. Locates the image file.
4. Downloads the image.
5. Displays the image.
6. If the image cannot be found, displays the `alt` text instead.

---

# Common Image Sources

The `src` attribute can reference different image locations.

## Local Image

```html
<img src="images/logo.png" alt="Company Logo">
```

---

## Image from Another Folder

```html
<img src="../assets/banner.jpg" alt="Website Banner">
```

---

## Online Image

```html
<img src="https://example.com/image.jpg"
     alt="Online Image">
```

---

# Why the `alt` Attribute is Important

The `alt` attribute provides alternative text when:

- The image cannot be loaded.
- The user is using a screen reader.
- The internet connection is slow.
- Images are disabled in the browser.
- Search engines index webpage content.

Example:

```html
<img src="student.jpg"
     alt="Student Learning HTML5">
```

---

# Common Uses of the `<img>` Element

The `<img>` element is used for displaying:

- Company logos
- Product images
- User profile pictures
- Blog images
- Website banners
- Icons
- Infographics
- Charts
- Diagrams
- Illustrations
- Advertisements
- Portfolio images

---

# Advantages

- Easy to use.
- Supported by all modern browsers.
- Improves webpage appearance.
- Enhances user engagement.
- Supports responsive web design.
- Improves accessibility using `alt`.
- Supports multiple image formats.

---

# Limitations

- Requires an external image file.
- Large images increase loading time.
- Missing `alt` text affects accessibility.
- Broken image paths prevent image display.

---

# Best Practices

Follow these recommendations when using the `<img>` element:

- Always provide the `alt` attribute.
- Use descriptive image file names.
- Optimize image sizes before uploading.
- Specify image dimensions whenever appropriate.
- Use responsive images for different devices.
- Store images in organized folders.
- Avoid oversized images.
- Test image paths before deployment.

---

# Browser Support

The `<img>` element is supported by all major modern browsers, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

---

# Summary

The `<img>` element is the standard HTML5 element used for displaying images on webpages. It is simple, efficient, and supported by all modern browsers. Understanding how to use the `<img>` element correctly, along with its attributes and best practices, is essential for building attractive, accessible, responsive, and professional websites.
