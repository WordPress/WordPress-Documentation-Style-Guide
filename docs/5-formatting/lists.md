# Lists

Lists are useful to present lengthy and complex content in a clear, well-structured format that is easy to read and scan for readers. Use a parallel syntax for all lists and its items.

For more information about procedural steps that provide instructions to achieve a particular task, see [Procedures]().

[info] **Note:** Don't use a list to express just one item; a single item isn't really a list. If you want to distinguish a single item from other text, use a different type of formatting.  
For additional information on whether lists or tables are ideal, see [Choosing between a list or table](). [/info]

## Types of lists

### Bulleted lists

Use a bulleted list for items that don't need to appear in order or sequence and items that aren't options.

**Example**  

[tip] Recommended:  
With this theme, you can do the following:
- Customize the header and footer.
- Modify the post format.
- Add a custom site logo.  

[/tip]  

### Numbered lists

Use a numbered list for sequential items in order (such as a sequence of steps) or prioritized items (such as a countdown list).

**Example**  

[tip] Recommended:  
To set up your development environment, follow these steps:  
1. Download and install Node Version Manager (nvm).
2. Download, install, and start Docker Desktop following the instructions for your OS.
3. Install the WordPress environment tool.
4. Start the environment from an existing plugin or theme directory, or a new working directory.
5. Set up your code editor.

[/tip]  

For more information on nested procedures, see [Sub-steps in numbered procedures]().

### Lettered list

Use a lettered list to denote options to choose among. In many instances, a lettered list has mutually exclusive options.

**Example**  

[tip] Recommended:  
Select a theme to install:
A. Twenty Twenty-One
B. Twenty Twenty
C. Twenty Nineteen
D. Twenty Eighteen

[/tip]  

### Description list

Use a description list for listing down items with their descriptions, definitions, or explanations. A description list is generally used to emphasize multiple items with their descriptions (such as a glossary).

**Example**  

[tip] Recommended:  

**Backlink**  
Incoming links to a web page.

**bbPress**  
Free, open-source software built on top of WordPress for easily creating forums on sites.

**CLI**  
Command Line Interface. Terminal (Bash) in Mac, Command Prompt in Windows, or WP-CLI for WordPress.

**DNS**  
Domain Name System – how you assign a human readable address to a website’s exact numeric coded location.

[/tip]  

### Description lists that use run-in headings

Use a bulleted description list with run-in headings for listing down items with their descriptions, definitions, or explanations where space is limited.

**Example**  

[tip] Recommended:  
- **Backlink.** Incoming links to a web page.
- **bbPress.** Free, open-source software built on top of WordPress for easily creating forums on sites.
- **CLI.** Command Line Interface. Terminal (Bash) in Mac, Command Prompt in Windows, or WP-CLI for WordPress.
- **DNS.** Domain Name System – how you assign a human readable address to a website’s exact numeric coded location.

[/tip]  

## Multiple paragraph list items

A list item can contain more than one paragraph.  

To create multiple paragraphs, use the `<p>` element rather than using the `<br>` element. See the [HTML specification](https://html.spec.whatwg.org/multipage/semantics.html#the-br-element) for more information on which uses of `<br>` are correct and which ones aren't.

**Example**  

[tip] Recommended:  
To transfer files onto your site, you can do the following:  
- Use the file manager provided in your host’s control panel.  
- Use an FTP client.  
  FTP or “File Transfer Protocol” has been the most widely used transfer protocol for over thirty years.
- Use an SFTP client.  
[/tip]  

## Introductory sentences

In most cases, introduce a list with an introductory sentence that initiates the list that follows. If the heading of the content explains what the list is about, and no additional context is required, then don't include an introductory statement. You can introduce a list with an imperative statement.

The introductory sentence can end with a colon or a period. Use a period if the introductory content is extended, and a colon if the introductory statement is shorter and immediately precedes the list. The text preceding the colon must distinctly stand alone as a complete sentence. That is, don't introduce a list with a partial statement.

For information regarding punctuation and capitalization of lists, see [Capitalization and end punctuation]().

**Examples**  

[warning] Not Recommended: To set up your development environment: [/warning]  
[tip] Recommended: To set up your development environment, follow these steps: [/tip]  
[tip] Recommended: Set up your development environment: [/tip]  


[warning] Not Recommended: The settings are: [/warning]  
[tip] Recommended: The settings that can be changed are as follows: [/tip]  

## Sub-steps in numbered procedures

For additional information about sub-steps in numbered procedures, refer [Procedures]().

## Capitalization and punctuation

### Bulleted, numbered, and lettered lists

In most contexts, capitalize each list item. End each list item with a period or corresponding sentence-ending punctuation.

Don't add end punctuation in the following cases:
- If the item consists of a single word or fewer than three words.
- If the item doesn't include a verb.
- If the item is entirely link text, a title, heading, subheading, or a string.
- If the item is entirely in code font or a UI label.

[info] **Note:** These exceptions apply to individual list items, so it may happen that a list might have some items with end punctuation, and some without end punctuation. To avoid this, use a parallel syntax for all items such that all items either have or don't have end punctuation. [/info]  

**Examples**  

[tip] Recommended:  
With this theme you can modify the following header values:
- Length
- Width
- Color
- Transparency and opacity
- Font

[/tip]  
[tip] Recommended:  
With this theme, you can do the following:
- Customize the header and footer.
- Modify the post format.
- Add a custom site logo.

[/tip]  

### Description lists

In some cases, an explanation for a list item may be useful, but this can affect the punctuation. Rather than writing the descriptions, definitions, or explanations for a singular item, use a description list and write the descriptions for all the items in the list. In most contexts, capitalize each list item.

Don't end the term with a period or other end punctuation, but do end the description with a period or relevant end punctuation.

**Examples**  

[warning] Not Recommended:  
Word reference:  
- **Backlink**  
- **bbPress** - Free, open-source software built on top of WordPress for easily creating forums on sites.  
- **CLI**  
- **DNS**  

[/warning]  
[tip] Recommended:  
Word reference:  
**Backlink**  
Incoming links to a web page.

**bbPress**  
Free, open-source software built on top of WordPress for easily creating forums on sites.

**CLI**  
Command Line Interface. Terminal (Bash) in Mac, Command Prompt in Windows, or WP-CLI for WordPress.

**DNS**  
Domain Name System – how you assign a human readable address to a website’s exact numeric coded location.

[/tip]  

### Description lists that use run-in headings

End the introductory term or phrase with a period or colon. If a description follows a period, end the description with a period. If it follows a colon; then don't include a period if it's a list of items, phrases without verbs, or a list of items.

In most contexts, capitalize each list item. For the item descriptions, write text that follows a colon in lowercase and capitalize text that follows a period.

Don't use a dash or hyphen to set off an item description in a description list. For additional information, see [Colons instead of dashes in lists]().

**Examples**  

[tip] Recommended:  
Abbreviation glossary:
- **API:** Application Programming Interface
- **FTP:** File Transfer Protocol
- **CGI:** Common Gateway Interface
- **URI:** Uniform Resource Identifier
- **XML:** Extensible Markup Language

[/tip]  
[tip] Recommended:  
There are two ways of getting files onto your site, and once there, changing them:  
- **By using the file manager provided in your host’s control panel.** Popular file managers include cPanel, DirectAdmin, Plesk and....
- **By using an FTP or SFTP client.** File Transfer Protocol has been the most widely used transfer protocol....

[/tip]  
[tip] Recommended:  
The user-level privileges are as follows:  
- **Can modify:** posts, pages, media, user settings
- **Cannot modify:** password, email, username, user accounts, site settings

[/tip]  
