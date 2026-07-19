# Code, Keyboard, Sample Output and Variables

## Introduction

HTML provides several semantic elements for displaying programming-related content. These elements allow developers to represent source code, keyboard input, program output, variables, and preformatted text in a meaningful and standardized way.

Instead of using generic formatting elements, HTML5 provides dedicated tags such as `<code>`, `<kbd>`, `<samp>`, `<var>`, and `<pre>` to improve readability, accessibility, and semantic structure.

These elements are widely used in technical documentation, programming tutorials, API references, educational websites, and software manuals.

---

# Definition

## `<code>` Element

The `<code>` element represents a fragment of computer code.

It is commonly used for:

- Source code
- Programming statements
- Commands
- Function names
- Variables within code

---

## `<kbd>` Element

The `<kbd>` element represents user keyboard input.

It is commonly used in software documentation to display keyboard shortcuts.

---

## `<samp>` Element

The `<samp>` element represents sample output produced by a computer program.

---

## `<var>` Element

The `<var>` element represents a variable in a mathematical expression or programming statement.

---

## `<pre>` Element

The `<pre>` element preserves whitespace, indentation, tabs, and line breaks exactly as written in the HTML source code.

It is commonly used for displaying formatted code blocks.

---

# Syntax

## Code

```html
<code>System.out.println("Hello");</code>
```

---

## Keyboard Input

```html
<kbd>Ctrl + C</kbd>
```

---

## Sample Output

```html
<samp>Hello, World!</samp>
```

---

## Variable

```html
<var>x</var>
```

---

## Preformatted Text

```html
<pre>
public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello");

    }

}
</pre>
```

---

# Browser Output

```html
<p>
    <code>System.out.println("Java");</code>
</p>

<p>
    Press <kbd>Ctrl + S</kbd> to save.
</p>

<p>
    Output:
    <samp>Hello, World!</samp>
</p>

<p>
    Area = <var>π</var> × <var>r</var><sup>2</sup>
</p>
```

---

# Difference Between Formatting Elements

| Element | Purpose |
|----------|---------|
| `<code>` | Displays computer code |
| `<kbd>` | Displays keyboard input |
| `<samp>` | Displays sample program output |
| `<var>` | Displays variables |
| `<pre>` | Preserves formatting and whitespace |

---

# Complete Example

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <title>Programming Formatting Elements</title>

</head>

<body>

    <h1>Programming Elements</h1>

    <h2>Code Example</h2>

    <p>
        <code>System.out.println("Hello World");</code>
    </p>

    <h2>Keyboard Shortcut</h2>

    <p>
        Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text.
    </p>

    <h2>Sample Output</h2>

    <p>
        <samp>Hello, World!</samp>
    </p>

    <h2>Variable Example</h2>

    <p>
        Area = <var>π</var> × <var>r</var><sup>2</sup>
    </p>

    <h2>Preformatted Code</h2>

    <pre>
public class Demo {

    public static void main(String[] args) {

        System.out.println("Welcome");

    }

}
    </pre>

</body>

</html>
```

---

# Real-World Applications

These elements are commonly used in:

- Programming tutorials
- API documentation
- Software manuals
- Coding blogs
- Online learning platforms
- Technical books
- Developer documentation
- University course materials

---

# Advantages

- Improves readability.
- Represents programming content accurately.
- Supports semantic HTML.
- Enhances accessibility.
- Preserves source code formatting.
- Makes technical documentation easier to understand.

---

# Best Practices

- Use `<code>` for inline code snippets.
- Use `<pre>` for multi-line source code.
- Use `<kbd>` only for keyboard input.
- Use `<samp>` for program output.
- Use `<var>` for variables in formulas and programming examples.
- Maintain proper indentation inside `<pre>` blocks.

---

# Common Mistakes

- Using `<code>` for entire code blocks instead of `<pre>`.
- Using `<kbd>` for normal text.
- Using `<samp>` for source code.
- Ignoring indentation in code examples.
- Using CSS instead of semantic HTML elements for programming content.

---

# Interview Questions

### 1. What is the purpose of the `<code>` element?

The `<code>` element represents a fragment of computer source code.

---

### 2. What is the purpose of the `<kbd>` element?

The `<kbd>` element represents keyboard input entered by the user.

---

### 3. What does the `<samp>` element represent?

The `<samp>` element represents sample output produced by a computer program.

---

### 4. What is the purpose of the `<var>` element?

The `<var>` element represents a variable in programming or mathematical expressions.

---

### 5. Why is the `<pre>` element commonly used with `<code>`?

The `<pre>` element preserves whitespace and indentation, making multi-line source code easier to read while `<code>` identifies the content as computer code.

---

# Summary

The `<code>`, `<kbd>`, `<samp>`, `<var>`, and `<pre>` elements provide semantic ways to represent programming-related content in HTML5. These elements improve readability, accessibility, and document structure while making technical documentation, tutorials, and code examples more accurate and professional. Proper use of these formatting elements is considered a best practice in modern HTML5 development.
