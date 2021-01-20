# Code examples

This page explains about formatting code examples documentation. For more information about other code-related documentation, see [Code in text](), [Placeholders](), and [Command line interface syntax]().

## General guidelines for code examples

- Use spaces to indent code. Don't use tabs unless specified.
- Follow the indentation standards in the relevant [coding standards guide]().
- Wrap lines after 80 characters.
- Mark code blocks as preformatted text. In HTML, use a `<pre>` element; in Markdown, indent every line of the code block by four spaces.

For more information see [Coding standards]().

**Examples**  

[tip] **Recommended:**  
```html
<pre class="example">
function longSentence() {
  alert('This example of a sentence is very long and wraps onto a second
    line.');
}
</pre>
```
This preformatted code example renders a code block with syntax highlighting as follows:

```js
function longSentence() {
  alert('This example of a sentence is very long and wraps onto a second
    line.');
}
```  
[/tip]  
