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

To create multiple paragraphs, use the `<p>` element rather than using the `<br>` element. See the [HTML specification]() for more information on which uses of `<br>` are correct and which ones aren't.

**Example**  

| Function | Type | Default value | Description |
|----------|------|---------------|-------------|
| `anchor` | boolean | false | Lets you link directly to a specific block on a page.  |
| a
