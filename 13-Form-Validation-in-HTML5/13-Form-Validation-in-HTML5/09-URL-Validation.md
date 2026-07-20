# URL Validation

## Introduction

URL (Uniform Resource Locator) validation is the process of verifying whether a user has entered a correctly formatted website address. HTML5 provides built-in support for URL validation through the `url` input type, allowing browsers to automatically check the entered value before submitting a form.

Using HTML5 URL validation helps developers collect properly formatted website addresses without writing additional JavaScript code. It improves user experience, reduces invalid submissions, and ensures better data quality.

However, HTML5 URL validation only verifies the format of the URL. It does not check whether the website actually exists or is accessible. Therefore, server-side validation is always recommended for production applications.

---

# What is URL Validation?

URL validation ensures that the entered value follows the standard format of a web address.

A valid URL generally contains:

- Protocol (`http://` or `https://`)
- Domain name
- Top-level domain (TLD)

Example:

```text
https://www.example.com
```

---

# HTML5 URL Input Type

HTML5 provides the `url` input type specifically for validating website addresses.

## Syntax

```html
<input
    type="url"
>
```

---

# Basic Example

```html
<label for="website">

    Website

</label>

<input
    type="url"
    id="website"
    name="website"
    required
>
```

If the entered value is not a valid URL, the browser displays a validation message and prevents form submission.

---

# Using Placeholder

```html
<input
    type="url"
    placeholder="https://www.example.com"
    required
>
```

The placeholder helps users understand the expected input format.

---

# Complete Example

```html
<form>

    <label for="company">

        Company Name

    </label>

    <input
        type="text"
        id="company"
        name="company"
        required
    >

    <br><br>

    <label for="website">

        Company Website

    </label>

    <input
        type="url"
        id="website"
        name="website"
        placeholder="https://www.example.com"
        required
    >

    <br><br>

    <input
        type="submit"
        value="Submit"
    >

</form>
```

---

# Common Invalid URL Examples

The following examples are not considered valid URLs:

```text
www.example.com
```

(Missing protocol)

```text
example
```

(Not a valid web address)

```text
https://
```

(Missing domain name)

```text
http:/example.com
```

(Incorrect protocol format)

---

# Advantages

- Built-in browser validation.
- Easy to implement.
- Improves data quality.
- Reduces invalid submissions.
- Requires minimal code.
- Enhances user experience.
- Supported by modern browsers.

---

# Best Practices

- Use `type="url"` for website address fields.
- Combine with the `required` attribute for mandatory fields.
- Use descriptive placeholders.
- Provide meaningful labels.
- Validate URLs again on the server.
- Check website accessibility when required.
- Never rely solely on client-side validation.

---

# Real-World Applications

URL validation is commonly used in:

- User Profile Forms
- Company Registration Forms
- Business Directories
- Portfolio Websites
- Social Media Profile Forms
- Job Application Forms
- Vendor Registration Systems
- Freelancing Platforms
- Content Management Systems
- Developer Portfolios

---

# Difference Between URL Validation and Website Verification

| URL Validation | Website Verification |
|----------------|----------------------|
| Checks the format of the URL. | Checks whether the website actually exists and is reachable. |
| Performed by the browser. | Usually performed by the server or external services. |
| Fast and automatic. | May require network requests. |
| Does not verify accessibility. | Confirms that the website is available. |

---

# Summary

The HTML5 `url` input type provides an easy and effective way to validate website addresses using built-in browser functionality. It ensures that URLs follow the correct format before form submission, improving data quality and user experience. Since format validation alone cannot verify the existence or accessibility of a website, HTML5 URL validation should always be combined with server-side validation and verification techniques in real-world applications.
