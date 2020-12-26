# Tables

Tables are useful to present lengthy and complex pieces of data that are related, in a well-structured format that is easy to read and scan for readers. Generally a table consists of two or more rows and two or more columns in addition to the header row.

## Choosing between a list or table

Sometimes to represent data, it could be confusing as to what would be ideal - a list or a table. Refer the following table to select between a list or a table:

| Item type | Example | List or table |
|-----------|---------|---------------|
| Each item is a single unit. | A procedure with instructions. | Use a [bulleted list](), [numbered list](), or [lettered list](). |
| Each item consists of a two related pieces of data. | A glossary with term and description pairs. | Use a [description list](). |
| Each item consists of three or more related pieces of data. | A set of parameters with multiple values, data, categories, and descriptions. | Use a table. |  

### When not to use tables

- If you only have a single row of content, a table might not be the best way to present it, with exceptions such as reference docs.
- If you only have a single column in your table, convert the table to a list.
- Don't use a table to present a list of similar items.
- Don't split tables with long columns in half and present one half next to another.
- Don't use a table to present code examples.
- Avoid tables in the middle of a numbered procedure.

## Multiple paragraph table cells

A table cell can contain more than one paragraph.

To create multiple paragraphs, use the `<p>` element rather than using the `<br>` element. See the [HTML specification](https://html.spec.whatwg.org/multipage/semantics.html#the-br-element) for more information on which uses of `<br>` are correct and which ones aren't.

**Example**  

| Function | Type | Default value | Description |
|----------|------|---------------|-------------|
| `anchor` | boolean | false | Lets you link directly to a specific block on a page. This property adds a field to define an id for the block and a button to copy the direct link. |
| `defaultStylePicker` | boolean | true | When the style picker is shown, a dropdown is displayed so the user can select a default style for this block type. <p> If you prefer not to show the dropdown, set this property to false. |  

## Introductory sentences

In most cases, introduce a table with an introductory sentence that initiates the table that follows. If the heading of the content explains what the table is about, and no additional context is required, then don't include an introductory statement. You can introduce a table with an imperative statement.

The introductory sentence can end with a colon or a period. Use a period if the introductory content is extended, and a colon if the introductory statement is shorter and immediately precedes the table. The text preceding the colon must distinctly stand alone as a complete sentence. That is, don't introduce a table with a partial statement.

## Capitalization and punctuation

Use sentence case capitalization for the table title and each column heading. For text inside table cells, use sentence case capitalization; with exceptions. For example, some values, keywords, or strings are written in lowercase.

For text inside table cells, use periods or other end punctuation only if the sentences contain complete sentences or a combination of phrases and sentences.

## Table placement

- When introducing a table, use a complete sentence while referring to the table's position, such as *the following table*, or *the preceding table*.
- Don't insert a table in the middle of a sentence.
- If your table has any references such as footnotes, insert them immediately following the table.

## Table formatting

## Table column headings

## Linking to tables

Avoid linking to tables whenever possible. Instead refer to them by table number, or link to its parent heading or subheading link targets.
