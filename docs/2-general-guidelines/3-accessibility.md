# Accessibility guidelines

The WordPress community and the open source WordPress project is committed to being as inclusive and accessible as possible. This means ensuring users, regardless of device or ability, to be able to publish content and maintain a website or application built with WordPress.

## General guidelines

- Emphasize the reader rather than underlining their inconveniences.
  - Don't refer a person with a disability as a disabled person (such as referring a *visually impaired person* as *blind* or *handicapped*).
  - Use approved terminology for people with specific disabilities; such as *Person with limited mobility* (rather than a person who is *crippled*). For more information, see [Writing inclusive documentation](https://make.wordpress.org/docs/style-guide/general-guidelines/inclusivity/).
- Maintain a uniform structure for your document. Emphasize important points both stylistically and visually.
- Consider multi-platform accessibility for all types of devices and operating systems.
- Document all types of input devices such as voice and gesture based devices, controllers, mice, and keyboards. Avoid conventional verbs like *click*, *type*, and *touch/swipe* for interaction. Use inclusive verbs like *input*, *select*, etc.
- Don't use ableist language. Be inclusive and unbiased while writing about accessibility and disability.
- Take a pragmatic approach to HTML semantics. Don’t add semantics purely for the sake of semantics; but if there is an HTML structure that clearly matches the content, use that element. For example, if you have a group of links, it should most likely use a list element.
- Use simple tables and tabular formats. Avoid span tags (such as `rowspan` and `colspan`). Tables prove to be difficult for screen readers.

## Text accessibility

- Use concise and simple sentences.
- Avoid camel case and all caps text; follow [capitalization](https://make.wordpress.org/docs/style-guide/language-grammar/capitalization/) guidelines.
- Don't format fonts unnecessarily. For more information, see [Text formatting](https://make.wordpress.org/docs/style-guide/formatting/text/).
- Use proper heading hierarchy. The H1 is the main heading representing the page title on every page or post (article). For subsections, use a correct HTML, Markdown, or relevant heading structure — including the use of heading elements for page subsections. Heading markup should not be used for presentational purposes.
  - Use H2 through H6 to give internal structure to the page.
  - Don’t skip heading levels.
  - Don’t add extra functionality inside a heading, like links or buttons.
- Don't use colored or shaded backgrounds, images, or watermarks behind text. Low contrast hinders screen readers.
- Avoid a screen full of continued text; rather break up your content in paragraphs and make use of headings, lists, bullet points, etc.
- Define and spell out symbols, abbreviations or acronyms.
- Don't limit the reader to forcefully open links in a new tab. When a link opens in a new tab, the user may lose the ability to go back in the browser. If the links do open in a new tab, indicate it using text or an icon.

## Media accessibility

- Provide clear alternative descriptions for images.
  - Anything that the reader needs to know or do, must be in text as well.
  - Include `alt` and `figure` attributes/tags for images and illustrations.
  - Limit the alt text to 50 characters.
  - Use actual text rather than images of text.
- Provide transcripts, closed-captions and descriptions for audio and video content.
- Avoid auto-playing media. Provide controls to start, stop, and pause media.
- Don't use flickering or flashing elements. Using them can cause seizures and/or motion sickness.

## UI accessibility

- Don't use direction-based guidelines solely, for navigating user interfaces (for example, '*Click the __Publish__ button on the right sidebar*'; rather than '*Go to the top and click the button.*').
-  Clearly state error descriptions and ways to fix them.
- Ensure that correct terminology is used for UI elements. Additional information about UI Elements.
- Identify and inspect the regions of a page for their `aria-label`. Refer these UI elements by their terminology or by their `aria-label`. More on [aria-label]().

## Document rendering

- Consider that your document will be used on a multitude of devices.
- Use proper color combinations and contrast ratios, with a minimum ratio of 4.5:1. Certain colors and patterns may cause problems for some people.
- Don't rely on color solely to convey documentation.
- Similarly, ensure that  the document conveys all the information you intended when you view it in the following contexts:
  - Without sound
  - Using only sound
  - Without color
  - Using a keyboard
  - With screen magnification
  - Without punctuation

## Additional resources

- [WordPress Accessibility About page](https://wordpress.org/about/accessibility/)
- [WordPress Accessibility Team Homepage](https://make.wordpress.org/accessibility/)
- [WordPress Accessibility Coding Standards](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/accessibility/)
- [WordPress Accessibility-ready themes](https://wordpress.org/themes/tags/accessibility-ready/)
- [WordPress Accessibility Handbook](https://make.wordpress.org/accessibility/handbook/)
- [Development Tools for creating accessible resources](https://make.wordpress.org/accessibility/handbook/which-tools-can-i-use/useful-tools/)
- [WordPress Core issues with "accessibility" focus](https://core.trac.wordpress.org/focus/accessibility)
- [Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/)
- [Authoring Tool Accessibility Guidelines (ATAG) 2.0](https://www.w3.org/TR/ATAG20/)
- [Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/WAI/WCAG20/glance/)
