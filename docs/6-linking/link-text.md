# Link text

Write detailed and expressive link text that describes where the reader will be guided to, and what the reader will see after following the link. Links, by themselves, should be coherent without the surrounding text.  
Links can be of two forms:
- The exact text of the title, heading, or subheading you're linking to. For additional information about capitalizing such references, see [Capitalization in references to titles and headings]().
- A description of the linked document or page, with standard text capitalization.

For additional information about link text, see [Cross-references]().

## General guidelines for link text

- You can rewrite or rephrase a sentence to include a phrase to get well-articulated and clear link text.
- Don't use a URL as link text. Instead, use the page title or a description of the page.
- Don't use the phrase *click here* or *this document*. It impedes scannability and accessibility.
- Don't force links to open in a new tab or window. Let the reader decide how to open links. If the link needs to open in a new tab or window, notify the reader that the link will open in a new tab or window. For more information, see [Links to pages on a different domain or server]().
- Use an external link icon to indicate that the link goes to a different domain or server. For more information, see [Cross references]().
- If the link downloads a file, explicitly mention it, and the type of file being downloaded.
- If you're referencing a link with an abbreviation, include both the spelled-out term or phrase and the abbreviation in the link text. For example, link to [WordPress Command Line Interface (WP-CLI)](https://make.wordpress.org/cli/), not [WordPress Command Line Interface](https://make.wordpress.org/cli/) (WP-CLI).

**Examples**  

[warning] **Not Recommended (HTML):** Click `<a href="">here</a>`. [/warning]  
[warning] **Not Recommended (HTML):** Want more? Go to `<a href="">this page!</a>`. [/warning]  
[tip] **Recommended (HTML):** For more information, see `<a href="">Word choice</a>`. [/tip]  

[warning] **Not Recommended (Markdown):** Click `[here]()`. [/warning]  
[warning] **Not Recommended (Markdown):** Want more? Go to `[this page!]()`. [/warning]  
[tip] **Recommended (Markdown):** For more information, see `[Word choice]()`. [/tip]  

[warning] **Not Recommended (HTML):** See trademark policy at `<a href="https://wordpressfoundation.org/trademark-policy/">https://wordpressfoundation.org/trademark-policy/</a>`. [/warning]  
[tip] **Recommended (HTML):** For more information about WordPress trademarks, see the `<a href="https://wordpressfoundation.org/trademark-policy/">Trademark Policy for WordPress</a>`. [/tip]  

[warning] **Not Recommended (Markdown):** See trademark policy at `[https://wordpressfoundation.org/trademark-policy/](https://wordpressfoundation.org/trademark-policy/)`. [/warning]  
[tip] **Recommended (Markdown):** For additional information about WordPress trademarks, see the `[Trademark Policy for WordPress](https://wordpressfoundation.org/trademark-policy/)`. [/tip]  

## Punctuation with links

If you have punctuation immediately before or after a link, insert the punctuation outside the link tags where possible. For example, don't include sentence ending punctuation such as a period inside link text.

**Examples**  

[warning] **Not Recommended (HTML):** For the latest release announcements, see `<a href="https://wordpress.org/news/">News and Announcements.</a>` [/warning]  
[tip] **Recommended (HTML):** For the latest release announcements, see `<a href="https://wordpress.org/news/">News and Announcements</a>`. [/tip]  

[warning] **Not Recommended (Markdown):** For the latest release announcements, see `[News and Announcements.](https://wordpress.org/news/)` [/warning]  
[tip] **Recommended (Markdown):** For the latest release announcements, see `[News and Announcements](https://wordpress.org/news/)`. [/tip]  
