# Relative vs Absolute URLs in HTML5

## Introduction

A URL (Uniform Resource Locator) specifies the location of a resource on the internet or within a website. Whenever a hyperlink is created using the Anchor (`<a>`) element, the destination is provided through the **href** attribute, which contains a URL.

HTML5 supports two main types of URLs:

- Relative URLs
- Absolute URLs

Understanding the difference between these two URL types is essential for creating maintainable, portable, and well-structured websites.

---

# What is a Relative URL?

A **Relative URL** specifies the location of a resource relative to the current webpage. It does not include the complete website address or domain name.

Relative URLs are mainly used for linking resources within the same website.

---

# Syntax

```html
<a href="about.html">About Us</a>
```

---

# Example 1

Suppose the project structure is:

```text
Website/
│
├── index.html
├── about.html
├── contact.html
└── images/
    └── logo.png
```

To navigate from **index.html** to **about.html**:

```html
<a href="about.html">
    About Us
</a>
```

---

# Example 2

To display an image stored inside the **images** folder:

```html
<img src="images/logo.png" alt="Company Logo">
```

---

# Advantages of Relative URLs

- Short and easy to write.
- Easy to maintain.
- Works well within the same website.
- Simplifies project portability.
- Does not require the domain name.
- Ideal for local development.

---

# Limitations of Relative URLs

- Cannot directly access external websites.
- May break if the folder structure changes.
- Depends on the current file location.

---

# What is an Absolute URL?

An **Absolute URL** specifies the complete address of a resource, including the protocol and domain name.

Absolute URLs are commonly used for linking to external websites.

---

# Syntax

```html
<a href="https://www.example.com">
    Visit Example
</a>
```

---

# Example

```html
<a href="https://developer.mozilla.org">
    MDN Web Docs
</a>
```

When clicked, the browser opens the official MDN website.

---

# Components of an Absolute URL

Example:

```text
https://www.example.com/products/index.html
```

| Component | Description |
|-----------|-------------|
| https | Protocol |
| www.example.com | Domain Name |
| /products/ | Directory |
| index.html | Resource |

---

# Advantages of Absolute URLs

- Always points to the correct resource.
- Can access external websites.
- Independent of the current webpage.
- Useful for sharing links.
- Preferred for external references.

---

# Limitations of Absolute URLs

- Longer to write.
- More difficult to maintain if the domain changes.
- Less portable for local development.

---

# Relative URL vs Absolute URL

| Feature | Relative URL | Absolute URL |
|----------|--------------|--------------|
| Domain Name | Not Included | Included |
| Protocol | Not Included | Included |
| URL Length | Short | Long |
| Used For | Internal Resources | External Resources |
| Portability | High | Low |
| Maintenance | Easy | Moderate |

---

# When to Use Relative URLs

Use Relative URLs when:

- Linking pages within the same website.
- Linking images.
- Linking CSS files.
- Linking JavaScript files.
- Working on local development projects.

---

# When to Use Absolute URLs

Use Absolute URLs when:

- Linking external websites.
- Linking third-party resources.
- Sharing webpages publicly.
- Referencing online documentation.
- Connecting to resources outside the current domain.

---

# Best Practices

- Use Relative URLs for internal navigation.
- Use Absolute URLs for external websites.
- Always use HTTPS instead of HTTP.
- Avoid broken URLs.
- Organize project folders logically.
- Test hyperlinks before deployment.

---

# Common Mistakes

- Using Relative URLs for external websites.
- Incorrect folder paths.
- Missing protocol in Absolute URLs.
- Broken hyperlinks.
- Incorrect capitalization in file names.

---

# Interview Questions

### 1. What is a Relative URL?

A Relative URL specifies the location of a resource relative to the current webpage.

---

### 2. What is an Absolute URL?

An Absolute URL specifies the complete address of a resource, including the protocol and domain name.

---

### 3. Which URL type is commonly used for internal navigation?

Relative URLs.

---

### 4. Which URL type is commonly used for external websites?

Absolute URLs.

---

### 5. Which URL type is easier to maintain within the same website?

Relative URLs.

---

# Summary

Relative URLs and Absolute URLs are essential concepts in HTML5 navigation. Relative URLs are best suited for linking resources within the same website, while Absolute URLs are used for accessing resources located on different domains. Choosing the appropriate URL type improves website maintainability, navigation, portability, and overall user experience.
