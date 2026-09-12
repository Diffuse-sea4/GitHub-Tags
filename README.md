# GitHub-Tags
All the GitHub Tags<br>
We have all the GitHub Tags right here in this<br>
next line we will show them<br>

# Comprehensive Guide to Supported HTML Tags in GitHub Markdown

GitHub Flavored Markdown (GFM) filters out unsafe elements (like `<script>`, `<iframe>`, `<style>`, and form elements) to prevent cross-site scripting (XSS) attacks. Below is the complete, exhaustive list of all standard HTML tags that GitHub safely renders in `.md` files.

---

## 📂 1. Structural, Layout & Structural Division

*   `<div>`: Groups block-level content. Frequently used with `align="center"` or `align="right"` to position elements.
*   `<span>`: Groups inline content for minor adjustments.
*   `<p>`: Defines individual text paragraphs.
*   `<br>`: Forces a line break within a block of text.
*   `<hr>`: Renders a horizontal divider line across the page.

---

## 🔤 2. Text Formatting & Inline Typographic Semantics

### Bold & Emphasis
*   `<b>`: Applies bold styling without semantic weight.
*   `<strong>`: Applies bold styling indicating strong importance.
*   `<i>`: Applies italicized styling for an alternative voice or mood.
*   `<em>`: Applies italicized styling emphasizing the enclosed text.

### Corrections & Highlights
*   `<u>`: Renders text with an underline.
*   `<s>`: Strikethrough for text that is no longer accurate.
*   `<strike>`: Alternative tag for rendering a strikethrough.
*   `<del>`: Represents deleted text (typically rendered as a strikethrough).
*   `<ins>`: Represents inserted text (often rendered with an underline or background tint).

### Subscripts, Superscripts & Technical Display
*   `<sub>`: Formats content as a low-positioned subscript (e.g., H<sub>2</sub>O).
*   `<sup>`: Formats content as a high-positioned superscript (e.g., E = mc<sup>2</sup>).
*   `<kbd>`: Simulates keyboard input button styles (e.g., press <kbd>Ctrl</kbd> + <kbd>C</kbd>).
*   `<q>`: Wraps text in inline quotation marks.
*   `<samp>`: Represents sample output from a computer program.

---

## 💻 3. Code & Preformatted Text

*   `<code>`: Wraps short, inline fragments of monospaced programming syntax.
*   `<pre>`: Encloses preformatted monospaced text, preserving whitespace, tabs, and line breaks exactly as typed.

---

## 🗂 4. Collapsible Disclosures & Interactive Accordions

*   `<details>`: Wrapper tag creating an interactive dropdown container that can be toggled open or closed.
*   `<summary>`: Sets the visible label or heading text that users click on to expand the `<details>` block.

---

## 🖼 5. Images, Vector Graphics & Responsive Media

*   `<img>`: Renders standard web images. Supports custom `width`, `height`, `alt`, and alignment attributes.
*   `<picture>`: Container used to switch images dynamically (crucial on GitHub for providing separate light-mode and dark-mode assets using `<source media="(prefers-color-scheme: dark)">`).
*   `<source>`: Specifies alternative media resources inside a `<picture>` element.
*   `<svg>`: Embeds scalable vector graphic code directly.
*   `<g>`: Groups related vector shapes together within an `<svg>` wrapper.
*   `<path>`: Defines vector shapes, lines, and complex paths inside an `<svg>`.

---

## 📊 6. Complex Tables

*   `<table>`: Root tag that initializes a data chart/table.
*   `<thead>`: Groups header row content at the top of the table.
*   `<tbody>`: Groups the main body row data inside the table.
*   `<tr>`: Generates an individual row element.
*   `<th>`: Defines a header cell (automatically bolded and centered).
*   `<td>`: Houses standard data cells inside a row.

---

## 📜 7. Lists (Ordered, Unordered & Description)

### Standard Bullet & Number Lists
*   `<ul>`: Generates an unordered, bulleted list container.
*   `<ol>`: Generates a sequential, numbered list container.
*   `<li>`: Defines an individual list item within a `<ul>` or `<ol>`.

### Description & Glossary Lists
*   `<dl>`: Initializes a description or definition list structure.
*   `<dt>`: Specifies the term or name being defined in a description list.
*   `<dd>`: Provides the detailed description or definition for the preceding `<dt>`.
