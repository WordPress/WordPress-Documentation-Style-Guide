# Headings and titles

Headings provide proper content structure and visual points for readers to scan and navigate through content on any page. The heading hierarchy, along with other formatting such as spacing, lists, and illustrations helps break up long walls of text into a readable structure. It is also easier to jump between sections or pages if the headings and titles stand out.

In general, use consistent and descriptive headings and titles in any type of content.

## Formatting headings

- Use sentence case capitalization for headings and titles. For more information, see [Capitalization in titles and headings](https://make.wordpress.org/docs/style-guide/language-grammar/capitalization/#capitalization-in-titles-and-headings).
- When using abbreviations in headings, spell out and declare the abbreviation in the succeeding body text. For more information, see [Abbreviations](https://make.wordpress.org/docs/style-guide/language-grammar/abbreviations/#spelling-out-and-declaring-abbreviations).
- Don't end headings with a period. Avoid using other punctuation at the end of headings unless absolutely necessary.  
  **Examples**  

  [tip] **Sometimes okay:** Still have questions? [/tip]  

- Tag headings using heading elements. For HTML use `<h1>`, `<h2>`, and so on. In markdown use `#`, `##`, and so on.
- Use proper heading hierarchy.
  - Use a level-1 heading for the page title or heading of the main content. A level-1 heading is built into heading styles in many web pages and site themes.
  - Don't skip the heading levels of the heading hierarchy.  
    **Examples**  

    [warning] **Not recommended:**  
    ```markdown
    # Design Decisions
    This page lists a number of important design decisions that come up frequently.
    ### Absolute versus relative URLs
    ```
    [/warning]  

    [tip] **Recommended:**  
    ```markdown
    # Design Decisions
    This page lists a number of important design decisions that come up frequently.
    ## Absolute versus relative URLs
    ```
    [/tip]  

  - Don't use empty headings or headings with no associated content.  
    **Examples**  

    [warning] **Not recommended:**  
    ```markdown
    # Design Decisions
    ## Absolute versus relative URLs
    ```
    [/warning]  

    [tip] **Recommended:**  
    ```markdown
    # Design Decisions
    This page lists a number of important design decisions that come up frequently.
    ## Absolute versus relative URLs
    ```
    [/tip]  

- Use CSS to alter the style, formatting, or irregular heading hierarchy rather than altering the heading elements or creating new formatting. Ensure that heading markup is not used for presentational purposes.
- Avoid using code items in headings when possible. If using a code item in a heading is absolutely necessary, add a descriptive noun to the item in code font. For more information, see [Keywords](https://make.wordpress.org/docs/style-guide/developer-content/code-in-text/#keywords).
- Don’t add extra functionality inside a heading, like links or buttons.
- Break two-line headings carefully. In a non-responsive design, when the heading exceeds one line, break it so that the text is appropriately balanced. In responsive designs, the content is dynamically fit to the screen.
  - Break the line at the end of a phrase, if possible.
  - Break the line after punctuation.
  - Keep prepositions and adjectives on the same line, along with the words they modify.
  - Keep hyphenated words and multiple-word proper nouns (such as *Sunset Beach*) on the same line.
  - If none of these alternatives work, rewrite or rephrase the headline to the proper specifications.
- Ensure that your headings stand out with vertical spacing. Heading typically have more vertical space and less space below them. This helps distinguish the heading and associate it with the following text or content. Heading spacing is built into heading styles in most web pages and site themes; use those styles to control the spacing in a consistent manner.
- Don't use extra line breaks or other formatting to increase heading spacing. Doing so may cause difficulties while viewing responsive webpages, specifically on mobile devices - where the layout is adjusted to the screen size automatically.

## Writing headings

- Consider headings as an outline of its succeeding content. If the readers don't read the headings, they probably won't read the accompanying content.
- Level-1 headings are supposed to convey the principal essence of the topic being discussed in the following body content.
- If there is a lot of content to include in the primary heading, consider using secondary-level headings to break up content.
- Ensure that every new heading introduces a different and specific topic than earlier headings in a heading hierarchy.
- Write short and succinct headings and put the most important idea at the beginning. Focus on the information that the readers need to know.
- Be specific with your headings. You can write more specific headings as you move further down the heading hierarchy.
- Consider using phrases in action + object form and gerund form in headings. Examples of such phrases include *Write about genders, Writing about genders, Use diverse examples*, and *Using diverse examples*.
- Avoid using hyphens (-), ampersands (&), and other symbols in headings.

## Referring to subsections

While referring to subheadings or subsections in a document or a page, use phrases such as *in the following section* or *in the aforementioned section*. Don't use ambiguous phrases such as *in these sections* or *in this section*.
