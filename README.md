# Gutendown

Sample of a first few hundred titles off Gutenberg.org regenerated as clean markdown files. 


#### Rules & Assumptions

1. Markdowns contain only the Body of Work (BoW).
2. Table of Contents (ToC) has been stripped out so as to not pollute the BoW.
3. Filename starts with the `ref_id`/`folder_id` as on Gutenberg.org
4. No title, author name or subtitle is placed on the BoW.
5. First five leafs on a book are not considered a part of the BoW.
6. Last three leafs on a book are not considered a part of the BoW.

All pieces of data that aren't covered on the BoW are handled separately either through a persistent `json` or a hydratable HTML template on [Bookiza Abelone](https://bookiza.io). 


TODO: Many things.