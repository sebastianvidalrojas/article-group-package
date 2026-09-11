## Node Group Package File Specification
The specification consists of the following parts:
* [Layout Structure](layout-structure.md)
* [Index Database Schema](index-database-schema.md)
* [Content and Media Assets](content-and-media-assets.md)
* [Metadata Schema](metadata-schema.md)
* [Integrity and Error Handling](integrity-and-error-handling.md)

Additionally, this index page contains some key starting information needed for understanding the scope of the file format.
## Purpose
A Node Group Package file stores units of information, called "nodes". Nodes contain information (JSON) and can also point to other multimedia files (images, sounds, videos, etc.) stored within the package. It supports node edges, and node types, which enables developers to define a set of behaviors depending on a node's type.

The idea was to create an exchangeable file format for storing dictionary-style word articles.
