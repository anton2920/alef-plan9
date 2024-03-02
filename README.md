# Alef Programming Language

This is a port of Alef Programming Language to fourth edition of Plan 9.

Alef is a concurrent programming language designed for systems software. Exception handling, process management, and synchronization primitives are implemented by the language. Programs can be written using both shared variable and message passing paradigms. Expressions use the same syntax as C, but the type system is substantially different. Alef supports object-oriented programming through static inheritance and information hiding. The language does not provide garbage collection, so programs are expected to manage their own memory.

# Documentation

There are a few pieces of documentation available:

- [Alef Language Reference Manual](sys/doc/alef.pdf) by Phil Winterbottom.
- [Alef User’s Guide](sys/doc/ug.pdf) by Bob Flandrena.
- [Man pages for Alef compiler and libraries](sys/man/).
- [8a(1) man page](https://9p.io/magic/man2html/1/8a).
- [8l(1) man page](https://9p.io/magic/man2html/1/8l).
- [ar(1) man page](https://9p.io/magic/man2html/1/ar).

# Copyright

Pavlovskii Anton, 2024 (MIT). See [LICENSE](LICENSE) file for more details.
