# Gutendown

Samples of first few hundred titles off Gutenberg.org regenerated as markdown files. 


#### Rules & Assumptions

1. Markdowns contain only the Body of Work (BoW).
2. Table of Contents (ToC) has been stripped out so as to not pollute the BoW.
3. Filename starts with the `ref_id`/`folder_id` as on Gutenberg.org
4. No title, author name or subtitle is placed on the BoW.
5. First five leafs on a book are not considered a part of the BoW.
6. Last three leafs on a book are not considered a part of the BoW.

* All pieces that aren't covered on BoW are handled separately either through persistent `json` or dynamically generated using a hydratable template on [Bookiza Abelone](https://bookiza.io). 


TODO: Many things.