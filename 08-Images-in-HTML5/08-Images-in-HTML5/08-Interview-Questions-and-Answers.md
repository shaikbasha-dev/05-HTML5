# HTML5 Images Interview Questions and Answers

## Overview

This document contains frequently asked interview questions on HTML5 Images. These questions range from beginner to advanced level and are useful for technical interviews, viva examinations, certification exams, and revision.

---

# 1. What is the purpose of the `<img>` element in HTML5?

### Answer

The `<img>` element is used to embed and display images on a webpage. It is an empty (void) element and requires the `src` attribute to specify the image location.

**Example**

```html
<img src="logo.png" alt="Company Logo">
```

---

# 2. Is the `<img>` element a container element?

### Answer

No.

The `<img>` element is a **void (empty) element**, meaning it does not have a closing tag or contain any content.

---

# 3. What is the purpose of the `src` attribute?

### Answer

The `src` (source) attribute specifies the location or path of the image file that the browser should display.

**Example**

```html
<img src="images/photo.jpg" alt="Photo">
```

---

# 4. What is the purpose of the `alt` attribute?

### Answer

The `alt` attribute provides alternative text for an image.

It is displayed when:

- The image cannot be loaded.
- Images are disabled.
- Screen readers are used.
- Search engines index the webpage.

---

# 5. Why is the `alt` attribute important?

### Answer

Benefits include:

- Improves accessibility.
- Helps visually impaired users.
- Improves SEO.
- Displays fallback text when images fail to load.

---

# 6. What is the difference between Relative and Absolute Image Paths?

### Answer

| Relative Path | Absolute Path |
|---------------|---------------|
| Refers to images within the project. | Refers to images using a complete URL. |
| Portable. | Depends on external resources. |
| No domain name required. | Includes protocol and domain name. |

---

# 7. Which image format is best for photographs?

### Answer

**JPEG (.jpg/.jpeg)**

Reason:

- Smaller file size
- Good image quality
- Ideal for photographs

---

# 8. Which image format supports transparency?

### Answer

The following formats support transparency:

- PNG
- SVG
- WebP

GIF provides limited transparency.

---

# 9. Which image format supports animation?

### Answer

Animation is supported by:

- GIF
- WebP

---

# 10. Which image format is best for logos?

### Answer

SVG is generally the best choice because:

- It is scalable.
- It maintains quality at any size.
- It has a small file size.

PNG is also commonly used for logos requiring transparency.

---

# 11. What is the purpose of the `width` and `height` attributes?

### Answer

These attributes specify the image dimensions.

Benefits:

- Reserve layout space.
- Reduce layout shifts.
- Improve page rendering.

---

# 12. What is Lazy Loading?

### Answer

Lazy Loading delays loading images until they are close to entering the viewport.

Example:

```html
<img
    src="gallery.jpg"
    alt="Gallery"
    loading="lazy">
```

Benefits:

- Faster loading.
- Reduced bandwidth usage.
- Better performance.

---

# 13. What are Responsive Images?

### Answer

Responsive images automatically adapt to different screen sizes and device resolutions.

Methods include:

- CSS (`max-width: 100%`)
- `srcset`
- `sizes`
- `<picture>` element

---

# 14. What is the purpose of the `<picture>` element?

### Answer

The `<picture>` element allows developers to provide multiple image sources for different screen sizes, resolutions, or formats.

---

# 15. What is the `srcset` attribute?

### Answer

The `srcset` attribute provides multiple image versions so that the browser can select the most appropriate image for the user's device.

---

# 16. What is the purpose of the `sizes` attribute?

### Answer

The `sizes` attribute tells the browser how much space an image is expected to occupy in different viewport sizes, helping it choose the most suitable image from the `srcset`.

---

# 17. Which image format is recommended for modern websites?

### Answer

**WebP**

Advantages:

- Smaller file size
- Excellent image quality
- Supports transparency
- Supports animation
- Improves website performance

---

# 18. How can image performance be improved?

### Answer

Performance can be improved by:

- Compressing images.
- Using modern formats.
- Using responsive images.
- Enabling lazy loading.
- Optimizing image dimensions.
- Avoiding unnecessary large images.

---

# 19. What are some common mistakes when using images?

### Answer

Common mistakes include:

- Missing `alt` attributes.
- Broken image paths.
- Using oversized images.
- Choosing the wrong image format.
- Stretching images.
- Ignoring responsive design.
- Not optimizing images.

---

# 20. What are the best practices for using images in HTML5?

### Answer

Best practices include:

- Always use the `alt` attribute.
- Optimize image file sizes.
- Choose the correct image format.
- Use responsive images.
- Use lazy loading when appropriate.
- Use descriptive file names.
- Organize images into dedicated folders.
- Test images on different devices.
- Use HTTPS for external resources.

---

# Summary

Understanding HTML5 image concepts is essential for creating professional, accessible, and high-performance websites. Interview questions commonly focus on image elements, attributes, file formats, image paths, responsive images, accessibility, optimization techniques, and best practices. Mastering these topics prepares developers for technical interviews and real-world web development projects.
