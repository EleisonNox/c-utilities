# c-utilities
A collection of C utilities: aligned memory allocation with multiple backends, error handling, dynamic arrays, clamp functions, OpenGL helpers and more

# aligned_memory
Portable C library for aligned memory allocation.
Support Windows, POSIX, C11 and fallback with a malloc.

# assert_m
Flexible assert macros:
- `assert_m(condition, message)` - assertion with a string message
- `assert_mf(condition, format, ...)` - assertion with format (require C99 or GCC/clang extensions)
- `static_assert_m(condition, message)` - compile-time checks (require C11 with correct text or fallback)
Disabled when NDEBUG is defined.

License: Apache 2.0, Version 2.0
