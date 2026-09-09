## Index Database Schema
Each file has an SQLite database called `index.db`. This file contains all necessary information for keeping track of:
* "Who is this article?" (`id`),
* "Where is this article?" (`parent_id` and `path`),
* "What is this article?" (`type_id`),
* ...and finally "What is **IN** this article?" (`content`).

![Entity relationship diagram of the Index Database Schema](/content/assets/er_diagram_agpk.png)
