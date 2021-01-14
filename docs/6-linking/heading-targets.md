# Headings as link targets

Heading anchors are useful for document sections that are frequently linked to. To make headings into link targets, add an anchor. To avoid breaking existing heading links in published content, create an anchor that uses the same ID string as the published page. You can also create a custom anchor for a heading; for example, you can create a short anchor for a long heading. A custom anchor decreases the possibility of breaking existing links if the heading text changes.

## Adding an anchor

For content published on wordpress.org, WordPress may automatically create a link target for headings by default. For additional information about creating heading anchors on WordPress, see [Page jumps](https://wordpress.org/support/article/page-jumps/).  

{% codetabs %}  
{% HTML %}  
To add an anchor to a heading in HTML, do the following:
- Add a `<section>` element with an `id` attribute. Don't use `<a name>`.
- Use lowercase for `id` values.
- Insert hyphens between words.

[warning] Not Recommended:  
```html

```
[/warning]  

{% Markdown %}
To add an anchor to a heading in Markdown, do the following:  
- Add `{:#ID_OF_ANCHOR}` to the end of the line that the heading is on. Replace *`ID_OF_ANCHOR`* with the ID for this heading.
- Use lowercase for `id` values.
- Insert hyphens between words.

```markdown
```
{% end %}
