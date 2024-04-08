luacensor - redacting sensitive information with Lua

version: 1.1.1

luacensor is a package that takes advantage of Lua to securely redact documents, both by hiding all characters and by slightly varying the length of strings to prevent jigsaw identification. It also is friendly to screen readers by adding alt-text indicating redacted content.

See the documentation (luacensor.pdf) for examples and instructions for
installation and usage.

This work may be distributed and/or modified under the conditions of the
LaTeX Project Public License (LPPL), version 1.3 or later. 


For suggestions, feature requests, and bug reports, please use the project's
GitHub site:  https://github.com/ezgranet/luacensor

Version history:
07/04/2024: fixed issue with luaotfload

 23/02/2022: new `warning' option added to allow for printing a warning with redacted text
