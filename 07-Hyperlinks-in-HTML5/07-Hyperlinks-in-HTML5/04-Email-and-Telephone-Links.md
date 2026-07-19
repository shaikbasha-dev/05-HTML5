# Email and Telephone Links in HTML5

## Introduction

HTML5 provides special hyperlink schemes that allow users to directly send emails or make phone calls from a webpage. These hyperlinks improve user convenience by enabling quick communication without requiring users to manually copy contact information.

The Anchor (`<a>`) element is used with the `mailto:` and `tel:` protocols to create email and telephone links.

These types of hyperlinks are commonly used on contact pages, company websites, portfolios, business directories, customer support portals, and mobile applications.

---

# Email Links

## Definition

An **Email Link** is a hyperlink that opens the user's default email application with the recipient's email address automatically filled in.

Email hyperlinks use the **mailto:** protocol.

---

# Syntax

```html
<a href="mailto:example@example.com">Send Email</a>
```

---

# Basic Example

```html
<a href="mailto:support@example.com">
    Contact Support
</a>
```

### Output

When the user clicks **Contact Support**, the default email application opens with the recipient set to:

```text
support@example.com
```

---

# Email Link with Subject

The subject line can also be predefined.

```html
<a href="mailto:support@example.com?subject=Website Inquiry">
    Send Inquiry
</a>
```

---

# Email Link with Subject and Message

You can pre-fill both the subject and the email body.

```html
<a href="mailto:support@example.com?subject=Feedback&body=Hello Team,">
    Send Feedback
</a>
```

---

# Telephone Links

## Definition

A **Telephone Link** is a hyperlink that allows users to directly call a phone number on supported devices.

Telephone hyperlinks use the **tel:** protocol.

These links are especially useful for smartphones and tablets.

---

# Syntax

```html
<a href="tel:+919876543210">Call Us</a>
```

---

# Basic Example

```html
<a href="tel:+919876543210">
    Call Customer Support
</a>
```

### Output

On supported devices, clicking the link opens the phone dialer with the specified number.

---

# Real-World Applications

Email and telephone links are widely used in:

- Contact Us pages
- Company websites
- Business portfolios
- Hospital websites
- Educational institutions
- Government portals
- Customer support pages
- Restaurant websites
- Hotel booking websites
- Freelance portfolios

---

# Advantages

## Email Links

- Easy communication.
- Saves time.
- Opens the default email client automatically.
- Reduces manual typing errors.
- Improves user experience.

---

## Telephone Links

- One-click calling.
- Mobile-friendly.
- Convenient for users.
- Faster customer support.
- Ideal for responsive websites.

---

# Best Practices

- Use valid email addresses.
- Use international phone number formats.
- Clearly label email and telephone links.
- Test links on different browsers and devices.
- Keep contact information up to date.
- Avoid using misleading link text.

---

# Common Mistakes

- Typographical errors in email addresses.
- Incorrect phone numbers.
- Forgetting the `mailto:` protocol.
- Forgetting the `tel:` protocol.
- Using invalid international dialing codes.
- Not testing hyperlinks after deployment.

---

# Interview Questions

### 1. Which protocol is used to create an email hyperlink?

The `mailto:` protocol.

---

### 2. Which protocol is used to create a telephone hyperlink?

The `tel:` protocol.

---

### 3. Can an email hyperlink include a predefined subject?

Yes. The subject can be specified using the `subject` query parameter.

Example:

```html
mailto:example@example.com?subject=Feedback
```

---

### 4. On which devices are telephone hyperlinks most useful?

Smartphones, tablets, and devices that support telephone dialing.

---

### 5. Which HTML element is used for email and telephone hyperlinks?

The Anchor (`<a>`) element.

---

# Summary

Email and telephone hyperlinks simplify communication by allowing users to send emails or initiate phone calls directly from a webpage. Using the `mailto:` and `tel:` protocols with the Anchor (`<a>`) element improves accessibility, enhances user experience, and provides quick access to contact information across desktop and mobile devices.
