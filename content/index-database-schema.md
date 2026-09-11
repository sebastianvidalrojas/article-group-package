## Index Database Schema
Each file has an SQLite database called `index.db`. This file contains all necessary information for keeping track of:
* "Who is this node?" (`id`),
* "How is this node related to other nodes?" (`edge`),
* "What is this node?" (`node_type_id`),
* ...and finally "What **DATA** is in this node?" (`content`).

![Entity relationship diagram of the Index Database Schema](/content/assets/er_diagram_index.png)
