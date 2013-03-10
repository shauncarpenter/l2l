Lisp to Lua Compiler
====================

Description
-----------
A object-oriented, unicode-enabled lisp that compiles to and runs as fast as Lua. Equipped with macros and compile-time compiler manipulation. Comes with all built-in Lua functions. 

Requires Lua JIT 2.0.1!

Warning
-------
If input file is named foo.lsp, foo.lua will be replaced with the compiler output! 

Example 
-------
To compile all the examples:

./l2l sample01.lsp sample02.lsp sample03.lsp

To run a particular example:

lua sample01.lua

Quickstart
----------
    # cd into l2l directory
    # Requires Lua JIT 2.0.1! (Or modify l2l's header to point to Lua JIT 2.0.1 executable)
    ./l2l sample01.lsp sample02.lsp sample03.lsp
    lua sample01.lua

