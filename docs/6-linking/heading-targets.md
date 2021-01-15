# Headings as link targets

Heading anchors are useful for document sections that are frequently linked to. To make headings into link targets, add an anchor. To avoid breaking existing heading links in published content, create an anchor that uses the same ID string as the published page. You can also create a custom anchor for a heading; for example, you can create a short anchor for a long heading. A custom anchor decreases the possibility of breaking existing links if the heading text changes.

## Adding an anchor

[info] For content published on wordpress.org, WordPress may automatically create a link target for headings by default. For additional information about creating heading anchors on WordPress, see [Page jumps](https://wordpress.org/support/article/page-jumps/). [/info]

{% codetabs %}  
{% HTML %}  
To add an anchor to a heading in HTML, do the following:
- Add a `<section>` element with an `id` attribute. Don't use `<a name>`.
- Use lowercase for `id` values.
- Insert hyphens between words.

**Examples**  

[warning] Not Recommended:  
```html
<h2><a name="Determining_Plugin_And_Content_Directories">Determining plugin and content directories</a></h2>
```
[/warning]  
[warning] Not Recommended:  
```html
<a name="Determining_Plugin_And_Content_Directories"></a>
<h2>Determining plugin and content directories</h2>
 ```
[/warning]  
[tip] Acceptable:  
```html
<h2 id="determining-plugin-and-content-directories">Determining plugin and content directories</h2>
```
[/tip]  
[tip] Recommended:  
```html
<section id="determining-plugin-and-content-directories">
<h2>Determining plugin and content directories</h2>
...
</section>
```
[/tip]  
{% Markdown %}  
To add an anchor to a heading in Markdown, do the following:  
- Add `{:#ID_OF_ANCHOR}` after the heading, to the end of the line that the heading is on. Replace *`ID_OF_ANCHOR`* with the ID for this heading.
- Use lowercase for `id` values.
- Insert hyphens between words.

**Examples**  

[warning] Not Recommended:  
```markdown
## Determining plugin and content directories  {: id="ID_OF_ANCHOR" }
```
[/warning]  
[warning] Not Recommended: (Note single quotation marks)  
```markdown
## Determining plugin and content directories {: id='ID_OF_ANCHOR' }
```
[/warning]  
[warning] Not Recommended:  
```markdown
## Determining plugin and content directories  
{:#ID_OF_ANCHOR}  
```
[/warning]  
[tip] Acceptable:  
```markdown
## Determining plugin and content directories {: id="determining-directories" }
```
[/tip]  
[tip] Recommended:  
```markdown
## Determining plugin and content directories {:#determining-plugin-and-content-directories}
```
[/tip]  
[tip] Recommended:  
```markdown
## Determining plugin and content directories {:#determining-plugin-content-directories}
```
[/tip]  
{% end %}

## Changing an anchor

[info] For content published on wordpress.org, WordPress may automatically create a link target for headings by default. For additional information about creating heading anchors on WordPress, see [Page jumps](https://wordpress.org/support/article/page-jumps/). [/info]

To change an anchor, you need to create a custom anchor that uses the older ID string. A custom anchor decreases the possibility of breaking existing links if the heading text changes. You can find the ID string by inspecting the heading.

{% codetabs %}  
{% HTML %}  

If you change a heading from *Custom template files* to *Custom post type template files*, then add a custom anchor that uses the older ID string and formatting.

**Example**  

[tip] Recommended:  
```html
<section id="custom_template_files">
<h2>Custom post type template files</h2>
...
</section>
```
[/tip]  
{% Markdown %}  

If you change a heading from *Custom template files* to *Custom post type template files*, then add a custom anchor that uses the older ID string and formatting.

**Example**  

[tip] Recommended:  
```markdown
## Custom post type template files {:#custom_template_files}
```
[/tip]  
{% end %}
