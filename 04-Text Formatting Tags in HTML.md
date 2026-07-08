# Text Formatting Tags in HTML

## Introduction

Text Formatting Tags are used to **format and display text in different styles** on a webpage.

HTML provides various formatting tags to make content:

* Bold
* Italic
* Underlined
* Highlighted
* Strikethrough
* Preformatted

These tags improve the readability and appearance of web pages.

---

## Example Program

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Text Formatting Tags</title>
</head>
<body>

    <p>
        <b>HTML5</b> is the fifth and final major version of the <i>Hypertext Markup Language (HTML)</i> used for structuring and presenting content on the World Wide Web. <br>It is now maintained as the "HTML Living Standard," which is <mark>continually updated</mark> by <u>major browser vendors</u>.
    </p>

    <p>
        <s>Old Note: HTML revisions used to take years to release.</s>
    </p>

    <pre>
        Technical Specification:
            - Version: HTML5 (Living Standard)
            - Type   : Markup Language
            - Scope  : Client-Side Web Architecture
    </pre>

</body>
</html>
```

---

## Text Formatting Tags Used

### 1. `<b></b>` - Bold Tag

#### Definition

The `<b>` tag is used to display text in **bold format**.

#### Syntax

```html
<b>Text</b>
```

#### Example

```html
<b>HTML5</b>
```

Output:

**HTML5**

---

### 2. `<i></i>` - Italic Tag

#### Definition

The `<i>` tag is used to display text in **italic format**.

#### Syntax

```html
<i>Text</i>
```

#### Example

```html
<i>Hypertext Markup Language</i>
```

Output:

*Hypertext Markup Language*

---

### 3. `<u></u>` - Underline Tag

#### Definition

The `<u>` tag is used to **underline text**.

#### Syntax

```html
<u>Text</u>
```

#### Example

```html
<u>major browser vendors</u>
```

Output:

<u>major browser vendors</u>

---

### 4. `<mark></mark>` - Highlight Tag

#### Definition

The `<mark>` tag is used to **highlight or mark important text**.

By default, browsers display highlighted text with a yellow background.

#### Syntax

```html
<mark>Text</mark>
```

#### Example

```html
<mark>continually updated</mark>
```

Output:

<mark>continually updated</mark>

---

### 5. `<s></s>` - Strikethrough Tag

#### Definition

The `<s>` tag displays text with a line through it.

It is used to represent content that is **no longer accurate or relevant.**

#### Syntax

```html
<s>Text</s>
```

#### Example

```html
<s>Old Note: HTML revisions used to take years to release.</s>
```

Output:

~~Old Note: HTML revisions used to take years to release.~~

---

### 6. `<br>` - Line Break Tag

#### Definition

The `<br>` tag inserts a **line break**.

It is an **unpaired tag**, meaning it does not require a closing tag.

#### Syntax

```html
Line 1<br>
Line 2
```

#### Example

```html
HTML is easy.<br>
HTML is powerful.
```

Output:

HTML is easy.
HTML is powerful.

---

### 7. `<pre></pre>` - Preformatted Text Tag

#### Definition

The `<pre>` tag displays text exactly as written in the HTML source code.

It preserves:

* Spaces
* Tabs
* Line breaks

#### Syntax

```html
<pre>
Text
</pre>
```

#### Example

```html
<pre>
Technical Specification:
    Version : HTML5
    Type    : Markup Language
</pre>
```

Output:

```text
Technical Specification:
    Version : HTML5
    Type    : Markup Language
```

---

## Explanation of the Program

### Paragraph Tag

```html
<p>
...
</p>
```

The `<p>` tag is used to define a **paragraph**.

---

### Bold Text

```html
<b>HTML5</b>
```

Displays HTML5 in bold.

---

### Italic Text

```html
<i>Hypertext Markup Language (HTML)</i>
```

Displays the text in **italic style**.

---

### Line Break

```html
<br>
```

Moves the remaining content to the next line.

---

### Highlighted Text

```html
<mark>continually updated</mark>
```

Highlights important text.

---

### Underlined Text

```html
<u>major browser vendors</u>
```

Underlines the text.

---

### Strikethrough Text

```html
<s>Old Note...</s>
```

Displays text with a line through it.

---

### Preformatted Block

```html
<pre>
...
</pre>
```

Preserves the original formatting of the content.

---

## Important Points

* `<b>` displays bold text.
* `<i>` displays italic text.
* `<u>` underlines text.
* `<mark>` highlights text.
* `<s>` displays strikethrough text.
* `<br>` inserts a line break.
* `<pre>` preserves spaces and line breaks.
* `<br>` is an unpaired tag.
* Most formatting tags are paired tags.

---

## Summary

HTML Text Formatting Tags are used to improve the appearance and readability of text on webpages. Tags such as `<b>`, `<i>`, `<u>`, `<mark>`, `<s>`, `<br>`, and `<pre>` help developers present content in a structured and visually appealing manner. These tags are widely used in modern web development and are fundamental concepts for every Front-end Developer.
