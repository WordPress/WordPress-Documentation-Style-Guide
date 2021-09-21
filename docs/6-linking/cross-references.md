# Cross-references

[info] **Highlight:** Use cross-references to guide readers to related information. [/info]  

Cross-references guide the reader to information related to the content. For additional information about internal and external references, see [Link text](https://make.wordpress.org/docs/style-guide/linking/link-text/) and [Capitalization in titles and headings](https://make.wordpress.org/docs/style-guide/language-grammar/capitalization/#capitalization-in-titles-and-headings).

## References to other documents

Write relevant and meaningful link text.

**Examples**  
[warning] **Not recommended:** Click [here](https://wordpress.org/news/). [/warning]  
[warning] **Not recommended:** See [documentation](https://wordpress.org/support/). [/warning]  
[tip] **Recommended:** For the latest release announcements, see [News and Announcements](https://wordpress.org/news/). [/tip]  

If the link text doesn't clearly specify as to why you're referring the reader to related information, then provide explanatory information. Make the explanation specific, but don't repeat the information text.

**Examples**  
[warning] **Not recommended:** For more information, see [WP-CLI Commands](https://developer.wordpress.org/cli/commands/). [/warning]  
[tip] **Recommended:** For more information about all the available commands, see [WP-CLI Commands](https://developer.wordpress.org/cli/commands/). [/tip]  

If the link downloads a file, explicitly mention it, and the type of file being downloaded.

**Example**  
[tip] **Recommended:** Get started with the installation process by [downloading the latest WordPress ZIP file](https://wordpress.org/latest.zip). [/tip]  

Don't include multiple links to the same document or article within a page. However, you can add a secondary link, if you're linking to a particular section of the document or if the page you're linking from is long. It is also acceptable to use a secondary link if there are multiple entry points to the document you're linking from.

## Cross-references within generated reference documents

In generated reference documents, while linking from one reference topic to another, use the standard linking syntax rather than hard-coding links within the reference, so that the links will change appropriately when the reference docs change.

## Writing cross-references

While writing descriptions for what the cross-references link to, use *about* instead of *on*.

**Examples**  
[warning] **Not recommended:** For more information on procedural steps that provide instructions to achieve a particular task, see [Procedures and instructions](https://make.wordpress.org/docs/style-guide/formatting/procedures/). [/warning]  
[tip] **Recommended:** For more information about procedural steps that provide instructions to achieve a particular task, see [Procedures and instructions](https://make.wordpress.org/docs/style-guide/formatting/procedures/). [/tip]  

## Formatting cross-references

- Don't enclose cross-references that are links in quotation marks.
- In case the cross-reference isn't a link, use italics or quotation marks as appropriate.
  - Use italics for cross-references that are titles of full-length works such as a movie, book, or paper that are unlinked.  
    **Example**<br>
    [tip] **Recommended:** For more information, see the *American Heritage Dictionary*. [/tip]  
  - Use quotation marks for cross-references that are short works such as a blog post or a TV episode, and document sections.  
    **Example**<br>
    [tip] **Recommended:** For more information, see "Compound modifiers". [/tip]  

### Links to sections in the same page

When you're linking to another section in the same page, mention that the link guides you to a different section on the same page.

**Example**  
[tip] **Recommended:** In this document, see [References to other documents](#). [/tip]  

### Links to pages on the same server

When you're linking to another page on the same server, use root-relative URLs starting with `/`, even if you're linking to a page in the same directory as the page you're linking from.

### Links to pages on a different domain or server

- When you're linking to pages on a different domain or server, use absolute URLs. Start the URL with `https` if the server you're linking to supports HTTPS. If the server doesn't support HTTPS, start the URL with `http`.
- Don't force links to open in a new tab or window. Let the reader decide how to open links. If the link needs to open in a new tab or window, notify the reader that the link will open in a new tab or window.  
  **Example**<br>
  [tip] **Recommended:** For more information, see the [American Heritage Dictionary (opens in a new tab)](https://ahdictionary.com/). [/tip]  
- Use an external link icon to indicate that the link goes to a different domain or server. Examples of internal links are, a link from *make.wordpress.org* to *developer.wordpress.org* or a link from *wordpress.org/news* to the *make.wordpress.org/docs* subdomain. A link from *developer.wordpress.org* to *github.com/WordPress* is an example of an external link.  
  **Example**<br>
  [tip] **Recommended:** For more information, see the [Gutenberg project repository](https://github.com/WordPress/gutenberg). [/tip]  
