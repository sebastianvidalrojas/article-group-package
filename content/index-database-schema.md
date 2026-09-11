## Index Database Schema
Each file has an SQLite database called `index.db`. This file contains all necessary information for keeping track of:
* "Who is this node?" (`id`),
* "Where is this node?" (`parent_id` and `path`),
* "What is this node?" (`type_id`),
* ...and finally "What **DATA** is in this node?" (`content`).

![Entity relationship diagram of the Index Database Schema](/content/assets/er_diagram_index.png)
