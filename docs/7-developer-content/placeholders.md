# Placeholders

Placeholders in code and commands represent values that the user must input or replace. Placeholders in outputs can also represent values that differ. Generally, placeholders have a descriptive name and a value.

For example, *`POST_ID`* represents a post ID in a code example, command, and example output. In example output, *`VERSION`* represents the version of a plugin, theme, or software; the reader is not expected to set this to a specific value.

This page explains how to format placeholder variables in commands and code examples. For more information about other code-related documentation, see [Code in text](), [Code examples](), and [Command line interface syntax]().

## Placeholder variables

### Placeholder variables in inline text

When placeholder variables appear in a sentence, use the following formatting:
- In HTML, enclose inline placeholders in `<code><var>` elements.
  ```html
  <code><var>PLACEHOLDER_VARIABLE</var></code>
  ```
- In Markdown, enclose inline placeholders in backticks (``` ` ```) and use an asterisk (`*`) before the first and second backtick.
  ```markdown
  *`PLACEHOLDER_VARIABLE`*
  ```

### Placeholder variables in code blocks

When placeholder variables are in a block of code, use the following formatting:

{% codetabs %}  
{% HTML %}  

Enclose the code block in a `<pre>` element and tag placeholders with `<var>` elements.
```html
<pre class="prototype">
<img
  src="<var>IMAGE_PATH</var>"
  alt="<var>ALT_TEXT</var>"
/>
</pre>
```  
{% Markdown %}  

Enclose the code block in a code fence. You cannot apply text formatting or highlighting such as bold or italic inside a code fence.
```markdown
    ```
    *PLACEHOLDER_VARIABLE*
    ```
```  
{% end %}

### Placeholder variable text

For text in placeholder variables, use uppercase characters with underscore delimiters. If using uppercase characters with underscore delimiters, or capitalizing lowercase characters with already uppercase characters seems inconsistent, then it is acceptable to use another convention; but be consistent with that convention.

**Examples**  

{% codetabs %}  
{% HTML %}  

[warning] **Not recommended:**  
- `https://developer.wordpress.org/<var>API-name</var>`
- `https://developer.wordpress.org/<var>API_name</var>`
- `https://developer.wordpress.org/<var>API name</var>`
- `https://developer.wordpress.org/<var>api_name</var>`
- `https://developer.wordpress.org/<var>api-name</var>`
- `https://developer.wordpress.org/<var>apiName</var>`  

[/warning]  

[tip] **Recommended:**  
- `https://developers.google.com/<var>API_NAME</var>`
- `https://developers.google.com/<var>POST_TITLE</var>`

[/tip]  
{% Markdown %}  

[warning] **Not recommended:**  
- `https://developer.wordpress.org/*API-name*`
- `https://developer.wordpress.org/*API name*`
- `https://developer.wordpress.org/*API_name*`
- `https://developer.wordpress.org/*api_name*`
- `https://developer.wordpress.org/*api-name*`
- `https://developer.wordpress.org/*apiName*`  

[/warning]  

[tip] **Recommended:**  
- `https://developers.google.com/*API_NAME*`
- `https://developers.google.com/*POST_TITLE*`

[/tip]  
{% end %}

Don't use possessive pronouns in placeholder variables.

**Examples**
{% codetabs %}  
{% HTML %}  

[warning] **Not recommended:**  
- `https://developer.wordpress.org/<var>MY_API_NAME</var>`
- `https://developer.wordpress.org/<var>YOUR_API_NAME</var>`  

[/warning]  

{% Markdown %}  

[warning] **Not recommended:**  
- `https://developer.wordpress.org/*MY_API_NAME*`
- `https://developer.wordpress.org/*YOUR_API_NAME*`  

[/warning]  
{% end %}

For more information about placeholder text in commands, see [Optional arguments](), [Mutually exclusive arguments](), and [Multiple value arguments]().

## Describing placeholders

When you use a placeholder in code examples, commands, or other text, include an explanation for what the placeholder represents. Write an explanation for the first time you use the placeholder; if there are multiple placeholders or steps after the first use of that placeholder, you can explain the placeholder again.

Use the following order to describe placeholders:
- Describe what the user is doing.
- Write the code example, command, or other text.
- Explain the placeholder.
- Explain the code example, command, or other text in more detail if required.
- Show any output if required.
- Explain any output if required.

**Example**  

[tip] **Recommended:**  

```html
<pre class="prototype">
<img
  src="<var>IMAGE_PATH</var>"
  alt="The WordPress mascot Wapuu."
/>
</pre>

<p>Replace the following:</p>

<ul>
  <li><code><var>IMAGE_PATH</var></code>: the directory path of the image asset.</li>
</ul>
```  
[/tip]  

## Single placeholder

When writing a single placeholder, replace <code><var>PLACEHOLDER</var></code> *`PLACEHOLDER`* with *a description of what the placeholder represents.*

**Example**  

tip] **Recommended:**  
```shell
```  
[/tip]  

## Multiple placeholders

## Placeholders in output
