# Obsolete content

[info] **Highlight:** Use a warning notice type to mark content as outdated. [/info]  

As WordPress develops and evolves systematically, some methods and technologies change, which may outdate documentation. Accurately identifying and marking outdated content is beneficial for updating and maintaining up-to-date documentation for readers.

## Types of obsolete content

Obsolete content can be determined by the following contexts:  
- A whole page or article is outdated.
- A section from a page or article is outdated.
- A specific part of a section, page, or article is outdated.

## Marking content as obsolete

### Outdated page

Use a **Warning** [notice type](https://make.wordpress.org/docs/style-guide/formatting/notices/#cautions-warnings-notes-and-other-notices) to mark a page as obsolete, by enclosing the following phrase inside the `[warning][/warning]` short code:  
*__Warning:__ This page is outdated as of WordPress <code><var>VERSION</code></var>. It is maintained for archival purposes only.*

Replace <code><var>VERSION</code></var> with the WordPress version since the page was marked obsolete.

**Example**  
[tip] **Recommended (Markdown):** `[warning] **Warning:** This page is outdated as of WordPress 5.5.2. It is maintained for archival purposes only. [/warning]` [/tip]  

### Outdated section from a page or article

Use a **Warning** [notice type](https://make.wordpress.org/docs/style-guide/formatting/notices/#cautions-warnings-notes-and-other-notices) to mark a section from a page as obsolete, by enclosing the following phrase inside the `[warning][/warning]` short code:  
*__Warning:__ The <code><var>SECTION_NAME</code></var> section is outdated as of WordPress <code><var>VERSION</code></var>. It is maintained for archival purposes only.*  

Replace <code><var>SECTION_NAME</code></var> with the title, heading, subheading, or description of the outdated section. Replace <code><var>VERSION</code></var> with the WordPress version since the page was marked obsolete.

**Example**  
[tip] **Recommended (Markdown):** `[warning] **Warning:** The *Installation* section is outdated as of WordPress 4.3. It is maintained for archival purposes only. [/warning]` [/tip]  

### Outdated part of a section, page, or article

Use a **Warning** [notice type](https://make.wordpress.org/docs/style-guide/formatting/notices/#cautions-warnings-notes-and-other-notices) to mark specific content of a section as obsolete, by enclosing the following phrase inside the `[warning][/warning]` short code:  
*__Warning:__ The following content on <code><var>SECTION_NAME</code></var> is outdated as of WordPress <code><var>VERSION</code></var>. It is maintained for archival purposes only.*  

Replace <code><var>SECTION_NAME</code></var> with the title, heading, subheading, or description of the outdated part. Replace <code><var>VERSION</code></var> with the WordPress version since the page was marked obsolete.

**Example**  
[tip] **Recommended (Markdown):** `[warning] **Warning:** The following content on *i18n in JavaScript* is outdated as of WordPress 5.0. It is maintained for archival purposes only. [/warning]` [/tip]  

## Adding updated documentation

Use an **Info** notice type and add a URL of updated documentation, if any.  
- If the updated information can be found on another page, enclose the following notice inside the `[info][/info]` short code:  
  *__Note:__ Updated information can be found on <code><var>PAGE_URL</code></var>.*  
  Replace <code><var>PAGE_URL</code></var> with the URL of the updated documentation.
- If the page was moved to another destination, enclose the following notice inside the `[info][/info]` short code:  
  *__Note:__ This page was moved to <code><var>PAGE_URL</code></var>.*  
  Replace <code><var>PAGE_URL</code></var> with the URL of the new destination.

**Examples**  
[tip] **Recommended (Markdown):**  
`[warning] **Warning:** The following content on *i18n in JavaScript* is outdated as of WordPress 5.0. It is maintained for archival purposes only. [/warning]`  
`[info] **Note:** Updated information can be found on https://developer.wordpress.org/block-editor/developers/internationalization/#how-to-use-i18n-in-javascript. [/info]` [/tip]  
[tip] **Recommended (Markdown):**  
`[warning] **Warning:** This page is outdated as of WordPress 5.5.2. It is maintained for archival purposes only. [/warning]`  
`[info] **Note:** This page was moved to http://developer.wordpress.org/reference. [/info]` [/tip]  
