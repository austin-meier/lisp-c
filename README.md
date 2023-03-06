# LISP-C
### WIP

This is a LISP implementation written in pure C. I began this project in an attempt to develop a deeper understanding of LISP and the workings of programming languages in general. I believe a LISP implementation is the easiest first step.

I am still learning C, one area I am largely lacking in is tooling (although I get the feeling all C/C++ developers are). Therefore, this project does not use a build system at the moment. I am simply building from source with GCC.
```
gcc main.c data.c lexer.c parser.c printer.c eval.c -o lisp
```

### 📌 Progress
- Data Structures
  - Atoms 
    - Nil ✅
    - Integer literals ✅
    - Symbol ✅
    - Pair ✅
  - Manipulation
    - Cons ✅
  - Lists 
    - Creating ✅
    - Get 🚧
    - Set 🚧
    - Reverse 🚧
    - Copy 🚧
- Lexical Analysis
  - Basic tokenization ✅
- Paring
  - Parsing a basic expression ✅
  - Parsing a list ✅
- Printing
  - Basic expression printing ✅
- Environments
  - Creating environments ✅
  - Getting symbols from an environment ✅
  - Setting/Adding a symbol in an environment ✅
- Arithmetic 🚧
- Lambda Expressions 🚧
- Variadic Functions 🚧
- Macros 🚧
- Tail Recursion
- Garbage Collection 🚧
