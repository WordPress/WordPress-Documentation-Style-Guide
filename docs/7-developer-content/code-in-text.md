# Code in text

In text content, use monospace code font to highlight and distinguish code content from standard text. To express code font in HTML, use the `<code>` element. In Markdown, use backticks (``` ` ```) for code font.

This page explains about formatting code in standard text sentences. For more information on other code-related documentation, see [Code samples](), [Placeholders](), and [Command line interface syntax]().

## Items to put in code font

Use monospace code font while expressing the following items, which include but are not limited to:
-  Attribute names and values.
Class names.
Command-line utility names.
Data types.
Defined (constant) values for an element or attribute.
DNS record types.
Enum (enumerator) names.
Environment variable names.
Element names (XML and HTML). Place angle brackets (<>) around the element name; you may have to escape the angle brackets to make them appear in the document.
Filenames, filename extensions (if used), and paths.
Folders and directories.
HTTP verbs.
HTTP status codes.
HTTP content-type values.
Language keywords.
Method and function names.
Namespace aliases.
Placeholder variables.
Query parameter names and values.
Text input.

## Method names

When you refer to a method name in text, omit the class name except where including it would prevent ambiguity. Insert empty parentheses at the end of the method name to indicate that it's a method.

**Examples**  

[warning] Not Recommended: To delete a file or directory, call the `WP_Filesystem_ftpsockets::delete()` method. [/warning]  
[tip] Recommended: To delete a file or directory, call the `delete()` method. [/tip]  

## Commands

## Keywords

## WordPress coding standards
