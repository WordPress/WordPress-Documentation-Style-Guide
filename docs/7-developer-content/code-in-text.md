# Code in text

In text content, use monospace code font to highlight and distinguish code content from standard text. To express code font in HTML, use the `<code>` element. In Markdown, use backticks (``` ` ```) for code font.

This page explains about formatting code in standard text sentences. For more information on other code-related documentation, see [Code samples](), [Placeholders](), and [Command line interface syntax]().

## Items to put in code font

Use monospace code font while expressing the following items, which include but are not limited to:
-  Attribute names and values.
- Class names.
- [Command-line utility names]().
- Data types.
- Defined (constant) values for an element or attribute.
- [DNS record types](https://wikipedia.org/wiki/List_of_DNS_record_types).
- Enum (enumerator) names.
- Environment variable names.
- Element names in XML and HTML. Place angle brackets (`<>`) around the element name; you may have to escape the angle brackets to make them appear in the document.
- [Filenames](), [filename extensions](), and paths.
- Folders and directories.
- HTTP verbs, status codes, and content-type values.
- Language keywords.
- Method and function names.
- Namespace aliases.
- [Placeholder variables]().
- Query parameter names and values.
- Text input.
- [UI elements]() that implement previously entered text input. For example, if the user was instructed to enter a name for a UI element as `post-name`, then when you tell them to click the element, use code font and bold: *Click __`post-name`__*.

## Method names

When you refer to a method name in text, omit the class name except where including it would prevent ambiguity. Insert empty parentheses at the end of the method name to indicate that it's a method.

**Examples**  

[warning] Not Recommended: To delete a file or directory, call the `WP_Filesystem_ftpsockets::delete()` method. [/warning]  
[tip] Recommended: To delete a file or directory, call the `delete()` method. [/tip]  

## Commands

To mark a block of code such as a lengthy command or a code sample, use the following formatting:
- In HTML, use the `<pre>` element.
- In Markdown, use a code fence (` ``` `).

## Keywords

## Coding standards

For more information about coding standards for WordPress, see [Coding standards]().
