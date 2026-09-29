# How to add a tool

The owner drops links; Claude files them. For each new link:

1. Open the link and work out what the tool is.
2. Pick the category. Use the owner's category if they name one. Otherwise reuse an existing section in README.md, and only create a new category when nothing fits. A new category also gets a line in the Categories list at the top.
3. Add one table row: `| [Tool name](url) | What it is |`. Keep the description to one or two plain sentences about what it does and why it is useful.
4. Skip duplicates (same URL already listed).
5. Commit with a message like `Add <tool> to <category>` and push to `main`.

Style: no em dashes, no en dashes, and no hyphenated words in the prose (URLs are fine).
