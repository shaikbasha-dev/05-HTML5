# Image Attributes in HTML5

## Overview

HTML5 provides several attributes for the `<img>` element that control how an image is displayed, loaded, described, and presented on a webpage. These attributes improve accessibility, responsiveness, performance, and user experience.

Understanding image attributes is essential for developing professional, responsive, and SEO-friendly websites.

---

# What are Image Attributes?

Image attributes provide additional information about an image and define how the browser should display or process it.

Example:

```html
<img src="nature.jpg"
     alt="Beautiful Nature"
     width="500"
     height="300">
```

In the above example:

- `src` specifies the image location.
- `alt` provides alternative text.
- `width` defines the image width.
- `height` defines the image height.

---

# Common Image Attributes

| Attribute | Description |
|-----------|-------------|
| `src` | Specifies the location of the image file. |
| `alt` | Displays alternative text if the image cannot be loaded. |
| `width` | Specifies the width of the image. |
| `height` | Specifies the height of the image. |
| `title` | Displays additional information as a tooltip. |
| `loading` | Controls when the browser loads the image. |

---

# 1. src Attribute

The **src (Source)** attribute specifies the location of the image file.

### Syntax

```html
<img src="flower.jpg">
```

### Example

```html
<img src="images/logo.png"
     alt="Company Logo">
```

---

# 2. alt Attribute

The **alt (Alternative Text)** attribute provides a textual description of the image.

It is displayed when:

- The image cannot be loaded.
- Images are disabled.
- A screen reader is used.
- Search engines index the webpage.

### Example

```html
<img src="student.jpg"
     alt="Student Learning HTML5">
```

### Benefits

- Improves accessibility.
- Supports SEO.
- Provides fallback text.
- Enhances usability.

---

# 3. width Attribute

The **width** attribute specifies the width of the image.

### Example

```html
<img src="flower.jpg"
     width="400">
```

---

# 4. height Attribute

The **height** attribute specifies the height of the image.

### Example

```html
<img src="flower.jpg"
     height="250">
```

---

# 5. width and height Together

Both attributes can be used together to define the image dimensions.

### Example

```html
<img src="flower.jpg"
     width="400"
     height="250">
```

Specifying both dimensions helps browsers reserve space before the image loads, reducing layout shifts.

---

# 6. title Attribute

The **title** attribute displays additional information when the user places the mouse pointer over the image.

### Example

```html
<img src="flower.jpg"
     alt="Flower"
     title="Beautiful Red Flower">
```

---

# 7. loading Attribute

The **loading** attribute controls when the browser loads an image.

### Values

| Value | Description |
|--------|-------------|
| `lazy` | Loads the image only when it approaches the viewport. |
| `eager` | Loads the image immediately. |

### Example

```html
<img src="landscape.jpg"
     alt="Landscape"
     loading="lazy">
```

---

# Complete Example

```html
<img src="nature.jpg"
     alt="Beautiful Nature"
     width="500"
     height="300"
     title="Nature Image"
     loading="lazy">
```

---

# Advantages of Image Attributes

- Improve webpage accessibility.
- Enhance SEO.
- Improve user experience.
- Reduce layout shifts.
- Optimize page loading.
- Improve website performance.
- Provide meaningful image descriptions.

---

# Best Practices

- Always use the `alt` attribute.
- Use meaningful alternative text.
- Specify image dimensions whenever appropriate.
- Use the `loading="lazy"` attribute for non-critical images.
- Keep image file names descriptive.
- Avoid stretching images by using incorrect dimensions.
- Optimize image size before uploading.
- Use responsive techniques for different screen sizes.

---

# Common Mistakes

- Omitting the `alt` attribute.
- Using vague alternative text like "image".
- Using very large image dimensions.
- Ignoring image optimization.
- Distorting images with incorrect width and height values.

---

# Browser Support

All commonly used image attributes are supported by modern browsers such as:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

---

# Summary

Image attributes provide essential information that controls how images are displayed and interpreted by browsers, search engines, and assistive technologies. Proper use of attributes such as `src`, `alt`, `width`, `height`, `title`, and `loading` results in more accessible, responsive, high-performance, and user-friendly HTML5 webpages.
