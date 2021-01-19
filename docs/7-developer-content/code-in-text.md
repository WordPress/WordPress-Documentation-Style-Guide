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

For more information, see [Code text preceding colon]().

## Method names

When you refer to a method name in text, omit the class name except where including it would prevent ambiguity. Insert empty parentheses at the end of the method name to indicate that it's a method.

**Examples**  

[warning] Not Recommended: To delete a file or directory, call the `WP_Filesystem_ftpsockets::delete()` method. [/warning]  
[tip] Recommended: To delete a file or directory, call the `delete()` method. [/tip]  

## Commands

To mark a block of code such as a lengthy command or a code sample, use the following formatting:
- In HTML, use the `<pre>` element.
- In Markdown, use a code fence (` ``` ``).

Formatting a command with multiple elements:
- When a line exceeds 100 characters, you can safely add a line break before some characters, such as a single hyphen, double hyphen, underscore, or quotation marks. After the first line, indent each line by four spaces to vertically align each line that follows a line break.
- If you split a command line with a line break, each line except the last line must end with the command-continuation character. Commands that don't have the command-continuation character don't work. Command-continuation characters are:
  - Linux or shell: A backslash preceded with a space (` \`)
  - Windows: A caret preceded with a space (` ^`)
- Use placeholder text with [placeholder variables]().
- Write a descriptive list of the placeholder variables used in the command line succeeding the command line. For additional information, see [Explaining placeholders]().

## Keywords

Avoid using technical keywords as verbs or nouns. If you have to, don't change the word form of the keywords; don't make plurals from keywords, change tense, or convert them to possessive form. It's acceptable to use lowercase, plain text *string* in a general discussion of the `STRING` data type.

## Coding standards

For more information about coding standards for WordPress, see [Coding standards]().
