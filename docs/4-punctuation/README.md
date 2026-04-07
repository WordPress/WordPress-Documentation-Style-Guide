# Punctuation

This section provides punctuation guidelines for writing WordPress documentation.

## A note on rendered output

The recommendations in this section apply to **source text** — what authors type into editors, code, and documentation files. They are intended to keep source consistent, accessible, and easy to edit.

Note that WordPress core automatically transforms certain punctuation characters in rendered post content via the [`wptexturize()`](https://developer.wordpress.org/reference/functions/wptexturize/) function. This filter is applied by default to post titles, content, excerpts, and comments, and converts straight punctuation to typographic equivalents:

- Straight apostrophes (`'`) become typographic apostrophes (`’`)
- Straight quotation marks (`"`, `'`) become curly quotation marks (`“`, `”`, `‘`, `’`)
- Double hyphens (`--`) become em dashes (`—`)
- Three periods (`...`) become ellipses (`…`)

This means readers will see typographically correct punctuation in most user-facing content even when authors write straight characters in the source. Authors should follow the recommendations in this section regardless — `wptexturize()` handles the rendered output.
