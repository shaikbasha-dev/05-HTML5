# HTML5 Source Element

## Overview

The HTML5 `<source>` element is used to specify one or more media resources for the `<audio>`, `<video>`, and `<picture>` elements. It enables browsers to select the first supported media format from multiple available options, improving compatibility across different browsers, operating systems, and devices.

Using the `<source>` element is considered a best practice when embedding multimedia because different browsers may support different media formats.

---

# What is the `<source>` Element?

The `<source>` element is an HTML5 element that defines alternative media files for multimedia elements.

Rather than specifying a single media file, developers can provide multiple media sources, allowing the browser to automatically choose the first compatible format.

---

# Why Use the `<source>` Element?

The `<source>` element offers several benefits:

- Improves browser compatibility.
- Supports multiple media formats.
- Provides automatic format selection.
- Simplifies multimedia management.
- Creates more reliable web applications.

Without the `<source>` element, some browsers may fail to play multimedia content if the provided format is unsupported.

---

# Basic Syntax

## Audio

```html
<audio controls>

    <source src="audio/song.mp3" type="audio/mpeg">

</audio>
```

---

## Video

```html
<video controls>

    <source src="video/tutorial.mp4" type="video/mp4">

</video>
```

---

# Using Multiple Source Elements

One of the greatest advantages of the `<source>` element is the ability to provide multiple media formats.

Example:

```html
<audio controls>

    <source src="audio/song.mp3" type="audio/mpeg">

    <source src="audio/song.ogg" type="audio/ogg">

    <source src="audio/song.wav" type="audio/wav">

    Your browser does not support the audio element.

</audio>
```

The browser checks each source from top to bottom and plays the first supported format.

---

# Video Example

```html
<video controls
       width="700">

    <source src="video/tutorial.mp4" type="video/mp4">

    <source src="video/tutorial.webm" type="video/webm">

    <source src="video/tutorial.ogv" type="video/ogg">

    Your browser does not support the video element.

</video>
```

---

# Attributes of the `<source>` Element

| Attribute | Description |
|-----------|-------------|
| `src` | Specifies the path to the media file. |
| `type` | Specifies the MIME type of the media file. |
| `media` | Specifies a media query (commonly used with the `<picture>` element). |

---

# src Attribute

The `src` attribute specifies the location of the media file.

Example:

```html
<source src="audio/music.mp3">
```

---

# type Attribute

The `type` attribute specifies the MIME type of the media resource.

Examples:

```html
type="audio/mpeg"
```

```html
type="audio/ogg"
```

```html
type="video/mp4"
```

```html
type="video/webm"
```

Providing the correct MIME type allows browsers to determine compatibility without downloading unnecessary files.

---

# How the Browser Selects Media

When multiple `<source>` elements are provided:

1. The browser reads the first `<source>`.
2. It checks whether the format is supported.
3. If supported, playback begins.
4. Otherwise, it moves to the next `<source>`.
5. This process continues until a supported format is found.

If no supported source exists, the fallback text is displayed.

---

# Audio Example with Fallback

```html
<audio controls>

    <source src="song.mp3" type="audio/mpeg">

    <source src="song.ogg" type="audio/ogg">

    Your browser does not support HTML5 audio.

</audio>
```

---

# Video Example with Fallback

```html
<video controls>

    <source src="movie.mp4" type="video/mp4">

    <source src="movie.webm" type="video/webm">

    Your browser does not support HTML5 video.

</video>
```

---

# Advantages

Using the `<source>` element provides several benefits:

- Better browser compatibility.
- Automatic media selection.
- Cleaner HTML code.
- Easier maintenance.
- Support for multiple media formats.
- Improved user experience.
- Better performance by avoiding unsupported downloads.

---

# Best Practices

Follow these recommendations when using the `<source>` element:

- Always provide multiple media formats.
- Specify the correct MIME type.
- Include fallback text.
- Use optimized media files.
- Place the most widely supported format first.
- Test media playback across browsers.

---

# Common Mistakes

Avoid the following mistakes:

- Providing only one media format.
- Omitting the `type` attribute.
- Using incorrect MIME types.
- Forgetting fallback text.
- Using broken file paths.
- Providing unsupported media formats.

---

# Browser Support

The HTML5 `<source>` element is fully supported by all modern browsers, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

---

# Summary

The HTML5 `<source>` element is an essential part of multimedia development. It allows developers to provide multiple versions of audio and video files, enabling browsers to automatically choose the most suitable format. By improving compatibility, performance, and reliability, the `<source>` element helps create responsive and professional multimedia applications that work consistently across modern web browsers.
