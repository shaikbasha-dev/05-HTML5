# HTML5 Hyperlinks Interview Questions and Answers

## Introduction

Hyperlinks are one of the most frequently asked topics in HTML5 interviews because they are essential for website navigation and user interaction. Interviewers often assess a candidate's understanding of the Anchor (`<a>`) element, hyperlink attributes, URL types, bookmarks, email links, telephone links, accessibility, and best practices.

This document provides commonly asked interview questions along with concise and accurate answers to help learners prepare for technical interviews.

---

# Beginner Level Questions

## 1. What is a hyperlink?

A hyperlink is a clickable reference that connects one resource to another. It allows users to navigate between webpages, websites, documents, media files, email addresses, telephone numbers, and sections within a webpage.

---

## 2. Which HTML element is used to create hyperlinks?

The **Anchor (`<a>`)** element is used to create hyperlinks.

Example:

```html
<a href="https://www.example.com">Visit Website</a>
```

---

## 3. Which attribute specifies the destination of a hyperlink?

The **href (Hypertext Reference)** attribute specifies the destination of the hyperlink.

Example:

```html
<a href="about.html">About Us</a>
```

---

## 4. What does the `href` attribute stand for?

`href` stands for **Hypertext Reference**.

---

## 5. Can hyperlinks connect to external websites?

Yes.

Example:

```html
<a href="https://www.google.com">Google</a>
```

---

## Intermediate Level Questions

## 6. What is the difference between an Internal Link and an External Link?

| Internal Link | External Link |
|---------------|---------------|
| Connects pages within the same website | Connects to another website |
| Usually uses Relative URLs | Usually uses Absolute URLs |
| Improves internal navigation | Provides access to external resources |

---

## 7. What is a Relative URL?

A Relative URL specifies the location of a resource relative to the current webpage.

Example:

```html
<a href="contact.html">Contact</a>
```

---

## 8. What is an Absolute URL?

An Absolute URL specifies the complete address of a resource, including the protocol and domain name.

Example:

```html
<a href="https://developer.mozilla.org">
    MDN Web Docs
</a>
```

---

## 9. Which attribute opens a hyperlink in a new browser tab?

The **target** attribute.

Example:

```html
<a href="https://example.com" target="_blank">
    Open Website
</a>
```

---

## 10. Why should `rel="noopener noreferrer"` be used with `target="_blank"`?

It improves security by preventing the newly opened webpage from accessing the original webpage through the `window.opener` object. It also enhances performance and protects against certain security vulnerabilities.

---

# Advanced Level Questions

## 11. What is a Bookmark in HTML5?

A bookmark is a named location within a webpage created using the `id` attribute. It allows users to jump directly to a specific section of the page.

Example:

```html
<h2 id="services">Services</h2>

<a href="#services">Go to Services</a>
```

---

## 12. How do you create an Email Link?

Using the `mailto:` protocol.

Example:

```html
<a href="mailto:support@example.com">
    Send Email
</a>
```

---

## 13. How do you create a Telephone Link?

Using the `tel:` protocol.

Example:

```html
<a href="tel:+919876543210">
    Call Us
</a>
```

---

## 14. What is the purpose of the `download` attribute?

The `download` attribute instructs the browser to download the linked resource instead of opening it.

Example:

```html
<a href="resume.pdf" download>
    Download Resume
</a>
```

---

## 15. Which attribute displays additional information when hovering over a hyperlink?

The **title** attribute.

Example:

```html
<a href="about.html" title="Learn More About Us">
    About Us
</a>
```

---

# Scenario-Based Questions

## 16. When should Relative URLs be used?

Relative URLs should be used when linking resources within the same website, such as HTML pages, CSS files, JavaScript files, images, and other internal resources.

---

## 17. When should Absolute URLs be used?

Absolute URLs should be used when linking to external websites or resources outside the current domain.

---

## 18. Why are descriptive hyperlink texts important?

Descriptive hyperlink text:

- Improves accessibility.
- Helps users understand the destination.
- Improves Search Engine Optimization (SEO).
- Enhances user experience.

Example:

**Good**

```html
<a href="courses.html">View HTML5 Course</a>
```

**Poor**

```html
<a href="courses.html">Click Here</a>
```

---

## 19. What are some common mistakes while creating hyperlinks?

Common mistakes include:

- Missing the `href` attribute.
- Using broken URLs.
- Using vague link text.
- Opening every link in a new tab unnecessarily.
- Forgetting `rel="noopener noreferrer"` when using `target="_blank"`.
- Using HTTP instead of HTTPS.

---

## 20. What are the best practices for creating hyperlinks?

Some recommended best practices are:

- Use meaningful link text.
- Use HTTPS whenever possible.
- Test hyperlinks regularly.
- Use Relative URLs for internal pages.
- Use Absolute URLs for external websites.
- Improve accessibility.
- Keep navigation consistent.
- Avoid broken hyperlinks.

---

# Quick Revision

- Hyperlinks are created using the `<a>` element.
- `href` specifies the destination.
- `target="_blank"` opens links in a new tab.
- `rel="noopener noreferrer"` improves security.
- Relative URLs are used for internal resources.
- Absolute URLs are used for external resources.
- `mailto:` creates email links.
- `tel:` creates telephone links.
- `download` downloads linked files.
- Bookmarks use the `id` attribute and `#` fragment identifier.

---

# Summary

Understanding HTML5 hyperlinks is essential for both web development and technical interviews. Candidates should be familiar with the Anchor (`<a>`) element, hyperlink attributes, URL types, bookmarks, email and telephone links, security practices, accessibility guidelines, and common interview questions. Mastering these concepts enables developers to create secure, user-friendly, and standards-compliant websites.
