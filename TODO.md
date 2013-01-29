
## TODO list

Parsing of:
* (anonymous) sub structs
* Balanced brackets/braces (Convert clang::BalancedDelimiterTracker)
* ...

AST Generation for:
* type definitions
* substructs
* ellipsis (...) arguments
* For loops
* Binary Expressions
* Unary Expressions
* (proper) numeric values 
* (proper) Identifiers (with package qualifier)
* cast expression
* ...

Analysis of:
* symbol usages (Types, Vars, Functions)
* Type comparisons
* string parsing (\n\0 etc)
* labels (redefinition)
* ...

IR generation of:
* almost everything...

Generic:
* improve Makefile for header dependencies and .o location in subdir
* saving package info to cache
* saving recipe info to cache
* passing defines from recipe to Preprocessor
* parsing ansi-C headers into Package

Tooling:
* create c2find that only greps in files in recipe/target
* create c2style, astyle for C2
* create c2tags/c2scope that only includes files from recipe/target
* create graphical (Qt?) refactor tool to view files/packages/target symbols
    and allows project-wide renaming and drag-n-drop var/type/function definition
    reordering within files or within package.
