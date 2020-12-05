# Headings and titles

Headings provide proper content structure and visual points for readers to scan and navigate through content on any page. The heading hierarchy, along with other formatting such as spacing, lists, and illustrations helps break up long walls of text into a readable structure. It is also easier to jump between sections or pages if the headings and titles stand out.

In general, use consistent and descriptive headings and titles in any type of content.

## Formatting headings

- Use sentence case capitalization for headings and titles. For more information, see [Capitalization in titles and headings](/docs/3-language-and-grammar/capitalization.md#capitalization-in-titles-and-headings).
- When using abbreviations in headings, spell out and declare the abbreviation in the succeeding body text. For more information, see [Abbreviations](/docs/3-language-and-grammar/abbreviations.md).
- Don't end headings with a period. Avoid using other punctuation at the end of headings unless absolutely necessary.  
  **Examples**  

  [tip] Sometimes okay: Still have questions? [/tip]  

- Tag headings using heading elements. For HTML use `<h1>`, `<h2>`, and so on. In markdown use `#`, `##`, and so on.
- Use proper heading hierarchy.
  - Use a level-1 heading for the page title or heading of the main content. A level-1 heading is built into heading styles in many web pages and site themes.
  - Don't skip the heading levels of the heading hierarchy.  
  **Examples**  

  [warning] Not Recommended:  
  ```md
  # Design Decisions
  This page lists a number of important design decisions that come up frequently.
  ### Absolute versus relative URLs
  ```
  [/warning]  

  [tip] Recommended:  
  ```md
  # Design Decisions
  This page lists a number of important design decisions that come up frequently.
  ## Absolute versus relative URLs
  ```
  [/tip]  


- Use CSS to alter the style, formatting, or irregular heading hierarchy rather than altering the heading elements or creating new formatting.
- Avoid using code items in headings when possible. If using a code item in a heading is absolutely necessary, add a descriptive noun to the item in code font. For more information, see [Code in text - Keywords]().
- Break two-line headings carefully. In a non-responsive design, when the heading exceeds one line, break it so that the text is appropriately balanced. In responsive designs, the content is dynamically fit to the screen.
  - Break the line at the end of a phrase, if possible.
  - Break the line after punctuation.
  - Keep prepositions and adjectives on the same line, along with the words they modify.
  - Keep hyphenated words and multiple-word proper nouns (such as *Sunset Beach*) on the same line.
  - If none of these alternatives work, rewrite or rephrase the headline to the proper specifications.
- Ensure that your headings stand out with vertical spacing. Heading typically have more vertical space and less space below them. This helps distinguish the heading and associate it with the following text or content. Heading spacing is built into heading styles in most web pages and site themes; use those styles to control the spacing in a consistent manner.
- Don't use extra line breaks or other formatting to increase heading spacing. Doing so may cause difficulties while viewing responsive webpages, specifically on mobile devices - where the layout is adjusted to the screen size automatically.




## Writing headings
