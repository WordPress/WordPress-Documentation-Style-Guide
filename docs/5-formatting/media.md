# Media

[info] **Highlight:** Use SVG or PNG files and provide alt text for images. [/info]  

## Images, illustrations, and graphics

Use images only when they provide visual information that is otherwise difficult to express with words, examples, or other methods.

### General guidelines for images

- Don't use images of text, examples, code snippets, or other media solely comprised of text.
- Include screenshots with a full window; include the window's title bar in the screenshot.
- Maintain consistency of the operating system (OS) in screenshots - don't use a Linux OS in one and macOS in the other.
- Don't include personally identifying information (PII) in screenshots and other images.
  - If there is PII in a screenshot, redact it with a solid color with 100% opacity. Don't use blurs, pixelation, mosaic effects, or similar image-processing effects to redact PII, as these effects can be reversed to reveal the original information.
  - If you're exporting an image to a format that can include information on separate layers (for example, PDF or TIFF), flatten the image on export.
- Use drawing tools to create diagrams.
- For diagrams (such as network flows, system architectures) use vector graphic formats like SVG. SVG files stay sharp when you zoom in on the image. If you don't have an SVG image, use a PNG image as it provides better image quality than other raster image formats.
- Don't use image maps as they prove to be difficult for accessibility. Image maps are also problematic for a responsive design implementation that adapts to different viewport sizes, while also being complex. Instead, write a list of text references following the image.

### Text associated with images

In most cases, introduce an image with an introductory sentence that initiates the image that follows. If the heading of the content explains what the image is about, and no additional context is required, then don't include an introductory statement. You can introduce a image with an imperative statement.

The introductory sentence can end with a colon or a period. Use a period if the introductory content is extended, and a colon if the introductory statement is shorter and immediately precedes the image. The text preceding the colon must distinctly stand alone as a complete sentence. That is, don't introduce a image with a partial statement.

There are different types of text associated with images. Alt text is a concise description of the image that can replace the image in situations when the image isn't visible as well as accessible documentation. For example, people using screen readers, people using text-only browsers or people having a low-bandwidth internet connection can benefit from alt text. Alt text should consider the context of the image, not just its content. For more information, see [alt attribute](https://wikipedia.org/wiki/Alt_attribute).

An image caption is a short description of the image. An image description is a textual explanation of the image which can be used to convey detailed descriptions than image captions. Figure captions are optional. When using the [`<figcaption>` element](https://html.spec.whatwg.org/multipage/semantics.html#the-figcaption-element), both the `<figcaption>` and `<img>` elements must be wrapped in the [`<figure>` element](https://html.spec.whatwg.org/multipage/semantics.html#the-figure-element) to ensure that the figure caption is properly associated with the image.

**Examples**  

[tip] **Recommended (HTML):**  
```html
<figure id="wapuu">
  <img src="/assets/images/wapuu.png"
    width="70"
    alt="The WordPress mascot Wapuu."
    longdesc="#description">
  <figcaption><b>Image 1.</b> Image of WordPress mascot Wapuu.</figcaption>
</figure>
<div id="description">
<p>The official WordPress mascot - the adorable cartoon creature Wapuu, was first revealed in 2011.
</p>
</div>
```  

[/tip]  

[tip] **Recommended (Markdown):**  
```markdown
![The WordPress mascot Wapuu.](/assets/images/wapuu.png){: width="70"}

**Image 1.** Image of WordPress mascot Wapuu.

The official WordPress mascot - the adorable cartoon creature Wapuu, was first revealed in 2011.
```  

[/tip]  

#### Alt text

Use an [`alt` attribute](https://html.spec.whatwg.org/multipage/embedded-content.html#alt) to provide an alternative text for an image; the value must be an appropriate replacement for the image. Alt text is used to write accessible documentation and is used in assistive technologies such as screen readers, text-only browsers or low-bandwidth internet connections. The `alt` attribute helps support navigability in screen readers, markup validation, and search engine optimization (SEO). If the image is decorative (not informative) or it's provided only as a visual aid for information that is already expressed in text, then provide empty alternative text (`alt=""`) so it will be ignored by assistive technologies.

The `alt` attribute is required when using the `<img>` element, even if it is an empty string (`alt=""`). If you don't use the `alt` attribute, screen readers might read the filename instead.  

As per the [HTML specification](https://html.spec.whatwg.org/dev/images.html#general-guidelines), "the most general rule to consider when writing alternative text is the following: the intent is that replacing every image with the text of its alt attribute not change the meaning of the page." So if the alternative text is redundant with surrounding text or it's not useful to visually impaired readers, use the empty tag.

When writing alt text, follow these guidelines:
- Write full sentences.
- Use punctuation in alt text. When encountered with punctuation, screen readers pause before continuing.
- Don't replace alt text with image captions.
- Don't include phrases such as *Image of* or *Photo of*.
- Write consistent alt text for repeated occurrences of images.
- Avoid using all-caps in alt text. Some screen readers read capital letters as each letter individually.
- When writing alt text, consider the context of the image in addition to the content of the image.
- Whenever possible keep alt text length to 155 characters or less for better search engine optimization. If you exceed the 155 character limit, include a brief summary of the image in the `alt` attribute and also include the `longdesc` attribute to link to a more extensive description of the image. The `longdesc` attribute value should be a link, not text.

#### Captions

Captions are brief, concise summaries of an image or a figure.
When writing image captions, follow these guidelines:
- Use the form,  "<b>Figure <var><code>NUMBER</var></code>.</b> <var><code>DESCRIPTION</var></code>".
- Use punctuation in image captions.
- In general, avoid using directional language such as *the image above, top, below, left-hand side, lower-right side* in instructions to locate images or other figures. Directional language proves to be difficult for accessibility or for localization.
- Don't include the image caption in a sentence referencing the image.

#### Descriptions

A description provides a more detailed, textual explanation of information depicted by an image. Any new information should be conveyed through text, and not introduced through a figure or image.

The image description should not be confused with the [`longdesc` attribute](https://www.w3.org/TR/WCAG-TECHS/H45.html), which can be used to provide a more lengthy description of the content and context of an image than can be conveyed in the `alt` attribute's recommended 155 character limit.

When writing image descriptions, follow these guidelines:
- Write image descriptions when captions are inadequate in conveying complete information.
- Write text that is associated with the image.
- Use punctuation in image descriptions.

#### Text in figures

In most cases, avoid embedding text containing information in images, figures, or screenshots. Particularly, when a new concept is being introduced to the reader, try not to include it in figures. Text in images impedes accessibility and increases localization costs if they are localized. If you must embed text in an image, then ensure the same information is also provided in a form that people with visual disabilities can use, such as an [image description](#descriptions).

When you must include text in figures and images, use the following guidelines:
- Write concise text. Avoid complete sentences and punctuation when possible.
- Use sentence-case capitalization. Follow [capitalization](https://make.wordpress.org/docs/style-guide/language-grammar/capitalization/#capitalization-and-illustrations) guidelines.
- Don't embed image descriptions or captions in the figure or image. Instead, put figure descriptions and captions in text following the figure.
- Don't create new abbreviations to condense text.
- Use numbered callouts in figures to help you write a figure description, but don't use callouts for detailed annotations.
- Use full trademarked product names.

#### Accessibility resources

For more information about image accessibility, see the following resources:
- [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/glance/)
- [General text alternative guidelines from WCAG](https://www.w3.org/WAI/WCAG21/quickref/?showtechniques=111#text-alternatives)
- [Using `alt` attributes for `img` elements](https://www.w3.org/WAI/WCAG21/Techniques/html/H37.html)
- [Providing a long description in text near the non-text content](https://www.w3.org/WAI/WCAG21/Techniques/general/G74.html)
- [Using `longdesc`](https://www.w3.org/WAI/WCAG21/Techniques/html/H45.html)

### Image formatting and layout

- In most cases, use left-, or right-alignment for images unless specified otherwise. Don't align images in the center.
- Don't override your site's CSS or other existing styling unless required.
- Visualize and consider how the image will look when printed out.
- An image can take up the full width of a page.
- In general, don't use an image that is larger than its intended container. Resize the image if its dimensions exceed the container's specifications.
- Resize or reformat high resolution images that take up too much space.
- Don't link to the figure from within the same page unless it's a very long page and you're linking to it from quite far away on the page.
- Don't put the `<img>` inside a `<p>`.
