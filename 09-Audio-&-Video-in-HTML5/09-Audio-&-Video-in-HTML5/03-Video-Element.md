# HTML5 Video Element

## Overview

The HTML5 `<video>` element is used to embed and play video content directly within a web page without requiring external plugins such as Adobe Flash. It provides native browser support for video playback and includes built-in controls for playing, pausing, adjusting volume, seeking, fullscreen viewing, and picture-in-picture (where supported).

The `<video>` element is commonly used for educational tutorials, online courses, product demonstrations, promotional videos, entertainment platforms, webinars, and multimedia applications.

---

# What is the `<video>` Element?

The `<video>` element is an HTML5 multimedia element that allows developers to embed video content directly into web pages.

It supports multiple video formats and provides native playback controls that work consistently across modern browsers.

---

# Basic Syntax

```html
<video controls>

    <source src="video/sample.mp4" type="video/mp4">

    Your browser does not support the video element.

</video>
```

---

# Basic Example

```html
<video controls width="640">

    <source src="video/tutorial.mp4" type="video/mp4">

</video>
```

The browser automatically displays built-in controls that allow users to:

- Play the video.
- Pause the video.
- Adjust volume.
- Seek forward and backward.
- View playback duration.
- Enter fullscreen mode (browser dependent).

---

# Anatomy of the Video Element

```html
<video controls width="640" height="360">

    <source
        src="video/tutorial.mp4"
        type="video/mp4">

    Your browser does not support the video element.

</video>
```

### Components

| Component | Description |
|-----------|-------------|
| `<video>` | Defines the video player. |
| `controls` | Displays built-in playback controls. |
| `width` | Specifies the width of the video player. |
| `height` | Specifies the height of the video player. |
| `<source>` | Specifies the video file. |
| `src` | Specifies the location of the video file. |
| `type` | Specifies the MIME type of the video. |
| Fallback Text | Displayed when the browser does not support HTML5 video. |

---

# Supported Video Formats

HTML5 supports several commonly used video formats.

| Format | MIME Type | Extension |
|---------|-----------|-----------|
| MP4 | video/mp4 | .mp4 |
| WebM | video/webm | .webm |
| OGG | video/ogg | .ogv |

Among these, **MP4** offers the widest browser compatibility and is the most commonly used format.

---

# Why Use the `<source>` Element?

The `<source>` element allows developers to provide multiple versions of the same video for improved browser compatibility.

Example:

```html
<video controls>

    <source src="tutorial.mp4" type="video/mp4">

    <source src="tutorial.webm" type="video/webm">

    <source src="tutorial.ogv" type="video/ogg">

    Your browser does not support HTML5 video.

</video>
```

The browser automatically plays the first supported video format.

---

# Common Video Attributes

| Attribute | Purpose |
|-----------|---------|
| `controls` | Displays playback controls. |
| `autoplay` | Starts the video automatically. |
| `loop` | Repeats the video continuously. |
| `muted` | Starts the video without sound. |
| `preload` | Specifies how the video should be loaded. |
| `poster` | Displays an image before the video starts playing. |
| `width` | Sets the width of the video player. |
| `height` | Sets the height of the video player. |

These attributes will be discussed in detail later in this module.

---

# Advantages

Using the HTML5 `<video>` element provides several benefits:

- Native browser support.
- No external plugins required.
- Built-in playback controls.
- Cross-platform compatibility.
- Mobile-friendly playback.
- Multiple video format support.
- Easy integration with JavaScript and CSS.
- Better accessibility.
- Improved security.
- Better performance.

---

# Best Practices

Follow these recommendations when using the `<video>` element:

- Always include the `controls` attribute.
- Use the `<source>` element to provide multiple formats.
- Display a meaningful `poster` image.
- Optimize video file size before uploading.
- Avoid unnecessary autoplay.
- Provide captions and subtitles using the `<track>` element.
- Test playback across browsers and devices.

---

# Common Mistakes

Avoid the following mistakes:

- Uploading excessively large video files.
- Providing only one video format.
- Omitting fallback text.
- Forgetting playback controls.
- Using autoplay with audio.
- Ignoring accessibility features.
- Not optimizing videos for web delivery.

---

# Browser Support

The HTML5 `<video>` element is supported by all modern browsers, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

To maximize compatibility, developers should provide videos in multiple supported formats.

---

# Summary

The HTML5 `<video>` element provides a powerful and standardized way to embed video content directly into web pages. With built-in playback controls, support for multiple video formats, responsive design capabilities, and accessibility features, it enables developers to deliver rich multimedia experiences without relying on third-party plugins. Mastering the `<video>` element is an essential step toward building interactive, modern, and professional web applications.
