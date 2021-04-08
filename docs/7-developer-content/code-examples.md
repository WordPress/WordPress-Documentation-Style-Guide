# Code examples

[info] **Highlight:** Use code blocks, preformatted text, and code fences to write code examples. [/info]  

In documentation, mark a block of code such as a lengthy command or a code example to distinguish it from standard text. To express code examples in HTML, use the `<pre>` element. In Markdown, use a code fence (` ``` `).

This page explains how to format code examples in documentation. For more information about other code-related documentation, see [Code in text](https://make.wordpress.org/docs/style-guide/developer-content/code-in-text/), [Placeholders](https://make.wordpress.org/docs/style-guide/developer-content/placeholders/), and [Command-line syntax](https://make.wordpress.org/docs/style-guide/developer-content/command-line-syntax/).

For more information about adding code blocks in the Gutenberg block editor, see [Code block](https://wordpress.org/support/article/code-block/) and [Preformatted block](https://wordpress.org/support/article/preformatted-block/).

## General guidelines for code examples

- Use spaces to indent code. Don't use tabs unless specified.
- Follow the indentation standards in the relevant [coding standards guide](https://make.wordpress.org/docs/style-guide/developer-content/coding-standards/).
- Wrap lines after 80 characters.
- Mark code blocks as preformatted text. In HTML, use a `<pre>` element; in Markdown, indent every line of the code block by four spaces.

For more information see [Coding standards](https://make.wordpress.org/docs/style-guide/developer-content/coding-standards/).

**Example**  
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

## Introductory sentences

In most cases, introduce a code example with an introductory sentence that initiates the example that follows. If the heading of the content explains what the code example is about, and no additional context is required, then don't include an introductory statement. You can introduce a code example with an imperative statement.

The introductory sentence can end with a colon or a period. Use a period if the introductory content is extended, and a colon if the introductory statement is shorter and immediately precedes the code example. The text preceding the colon must distinctly stand alone as a complete sentence. That is, don't introduce a code example with a partial statement.

**Examples**  
[warning] **Not recommended (ending with a colon):** The following code example shows how to use the `post` method. For information on other methods, refer the [Code reference](https://developer.wordpress.org/reference/methods/): [Code example] [/warning]  
[tip] **Recommended (ending with a period):** The following code example shows how to use the `post` method. For information on other methods, refer the [Code reference](https://developer.wordpress.org/reference/methods/). [Code example] [/tip]  
[tip] **Recommended:** The following code example shows how to use the `post` method: [Code example] For information on other methods, see the [Code reference](https://developer.wordpress.org/reference/methods/). [/tip]  
