## Article Group Package File Specification
The specification consists of the following parts:
* [Layout Structure](layout-structure.md)
* [Index Database Schema](index-database-schema.md)
* [Content and Media Assets](content-and-media-assets.md)
* [Metadata Schema](metadata-schema.md)
* [Integrity and Error Handling](integrity-and-error-handling.md)

Additionally, this index page contains some key starting information needed for understanding the scope of the file format.
## Purpose
An Article Group Package file stores content units, called "nodes". Nodes can contain JSON or point to other multimedia files (images, sounds, videos, etc.) stored within the package. It supports nodes forming parent-child hierarchies, and node types, which enables developers to implement different behaviors depending on a node's type.

The idea was to create an exchangeable file format for storing dictionary-style word articles.
