# TypeScript Grammar Extended

Currently, this extension only does one thing: variable and function names written in PascalCase will be tokenized as class names, following ubiquitous TypeScript/JavaScript naming conventions. This is a workaround for VS Code's current lack of support for semantic syntax highlighting, and hopefully will become obsolete in the near future.

The existing TextMate grammar for TypeScript is already quite robust and is otherwise unmodified here, but I was tired of seeing class names (in import statements and elsewhere) tokenized as ordinary variables.