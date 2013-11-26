check-include-guards
====================

See if a C/C++ source file header has a well-formed #include guard.

Well-formed:

    optional-white-space-and-comments
    #ifndef symbol
    anything
    #endif
    optional-white-space-and-comments

Gcc recognizes well-formed #include guards, and does automatic reverse include
guards.
