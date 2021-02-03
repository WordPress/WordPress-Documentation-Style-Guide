# Obsolete content

As WordPress develops and evolves systematically, some methods and technologies change, which may outdate documentation. Accurately identifying and marking outdated content is beneficial for updating and maintaining up-to-date documentation for readers.

## Types of obsolete content

Obsolete content can be determined by the following contexts:  
- A whole page or article is outdated.
- A section from a page or article is outdated.
- A specific part of a section, page, or article is outdated.

## Marking content as obsolete

- Use a **Warning** [notice type]() to mark content as obsolete, by enclosing the following phrase inside the `[warning]` short code:  
  *__Warning:__ This content has been marked as outdated.*
- Use an **Info** notice type and add a URL of updated documentation, if any.
  - If the updated information can be found on another page, enclose the following notice inside the `[info]` short code:  
   *__Note:__ Updated information can be found on <code><var>PAGE_URL</code></var>.*  
   Replace <code><var>PAGE_URL</code></var> with the URL of the updated documentation.
  - If the page was moved to another destination, enclose the following notice inside the `[info]` short code:  
   *__Note:__ This page was moved to <code><var>PAGE_URL</code></var>.*  
   Replace <code><var>PAGE_URL</code></var> with the URL of the new destination.

**Examples**  

[tip] **Recommended (Markdown):**  
`[warning] **Warning:** This content has been marked as outdated. [/warning]`  
`[info] **Note:** Updated information can be found on https://wordpress.org/support/article/using-permalinks. [/info]` [/tip]  

[tip] **Recommended (Markdown):**  
`[warning] **Warning:** This content has been marked as outdated. [/warning]`  
`[info] **Note:** This page was moved to http://developer.wordpress.org/reference. [/info]` [/tip]  
