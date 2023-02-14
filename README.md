# Gutenmark

Stripped down Gutenberg.org titles turned into clean markdown files before conversion into Superbooks. 

## Specifications

1. Filename starts with the `ref_id`/`folder_id` as on Gutenberg.org
2. Table of Contents (ToC) or physical Page Numbering has been deleted. 
3. Markdown contains _only_ the **Body of Work** (BOW).
4. No title, author name, or subtitle is allowed on the BOW.
5. First Five (FF) leaves, i.e., ten pages on a Superbook, are not considered a part of the BOW.
6. Last three leaves on a Superbook are also not considered a part of the BOW.

All pieces of the long-form that are not covered under the BOW or the FFs are handled separately either through a persistent `json` or a hydratable HTML template on [Bookiza Abelone](https://bookiza.io). 

### Character Encoding

Some text or markdown files may display a � replacement character in the absence of the appropriate charset or character encoding. PRs are welcome for manual fixes of such characters on file.
