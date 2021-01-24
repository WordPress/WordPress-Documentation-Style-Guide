# Placeholders

Placeholders in code and commands represent values that the user must input or replace. Placeholders in outputs can also represent values that differ. Generally, placeholders have a descriptive name and a value.

For example, *`POST_ID`* represents a post ID in a code example, command, and example output. In example output, *`VERSION`* represents the version of a plugin, theme, or software; the reader is not expected to set this to a specific value.

This page explains how to format placeholder variables in commands and code examples. For more information about other code-related documentation, see [Code in text](), [Code examples](), and [Command line interface syntax]().

## Placeholder variables

### Placeholder variables in inline text

### Placeholder variables in code blocks

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
