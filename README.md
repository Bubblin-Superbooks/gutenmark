# Gutendown

Samples of first few hundred titles off Gutenberg.org regenerated as markdown files. 


#### Rules

1. The files contain only the body of work (BoW).
2. Table of Contents (ToC) have been stripped out so as to not pollute the BoW.
3. Filename starts with the `ref_id`/`folder_id` on Gutenberg.
4. No title, author name or subtitle is placed on the BoW.
5. First five leafs on a book are not considered a part of the BoW.
6. Last three leafs on a book are not considered a part of the BoW.

* All pieces that aren't covered on BoW are handled separately either through persistent `json` or dynamically generated using a hydratable template on [Bookiza Abelone](https://bookiza.io). 


TODO: This is just a start.