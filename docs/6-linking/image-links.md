# Image links

[info] **Highlight:** Use root-relative URLs for image links. [/info]  

When you're including an image that is served from the same domain as your document or page, use a root-relative URL starting with `/`. Use this root-relative URL format (starting from the site root), even if you're linking to a page in the same directory as the page you're linking from.

{% codetabs %}  
{% HTML %}  
Insert the URL in the `src` attribute of the `<img>` element:
```html
<img
  src="/assets/images/wapuu.png"
  alt="The WordPress mascot Wapuu."
/>
```
{% Markdown %}
Insert the URL in parentheses after the image's alt text:
```markdown
![The WordPress mascot Wapuu.](/assets/images/wapuu.png)
```
{% end %}
