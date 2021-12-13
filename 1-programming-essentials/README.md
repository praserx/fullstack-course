# Programming Essentials Course

## Course Plan

### Lesson 1 (7 hours)

#### Lesson Plan

1. Training environment preparation
   1. Download and installation of Go compiler
   2. Download and installation of VS Code editor
   3. Hello world example
   4. Command line usage
2. Functions, arguments and `fmt` package
   1. `main` function
   2. Function definition and function call
   3. Printing text to console (`Print`, `Println`, `Printf`)
   4. Scanning text from console (`Scan`, `Scanln`)
   5. Program comments (`//`, `/* */`)
   6. Multiple return values
3. Variables and data types
   1. Variable declaration and definition
   2. Variable assignment (`=`, `:=`)
   3. `string`, `int`, `float32`/`float64`, `bool`, `pointer`
   4. Operators (`+`, `-`, `*`, `/`, `%`, `&&`, `||`, `!`, `==`, `!=`, `<`, `>`, `<=`, `>=`)
4. Pointers (`*`, `&`)
5. Function arguments pass by value vs. pass by pointer
6. Flow controls
   1. If-Else
   2. If-ElseIf-Else
   3. For loop
   4. Switch
7. Error handling

#### Lesson Resources

- [golang.org, go.dev](https://go.dev/)
- [code.visualstudio.com](https://code.visualstudio.com/)
- [gobyexample.com](https://gobyexample.com/)

- [standard library](https://pkg.go.dev/std)
- [package fmt](https://pkg.go.dev/fmt)
- [package os](https://pkg.go.dev/os)
- [package math/rand](https://pkg.go.dev/math/rand)
- [package time](https://pkg.go.dev/time)

#### Simple tasks

- Print your name console
- Read your name from console and print your name to console with some additional text
- Print current date and time in some fancy format
- `*` magic with for loop (triangle, pyramid, etd)
- Create chess board with for loop (`x` as black and `_` as white)
- Create random password of variable length

### Lesson 2 (7 hours)

#### Lesson Plan

1. Go documentation
   1. [Language specification](https://go.dev/ref/spec)
   2. [Effective Go](https://go.dev/doc/effective_go)
2. Arrays, Slices, Maps and memory management
   1. Array declaration and definition
   2. Slice declaration and definition
   3. Go memory management and garbage collector (Go vs. C vs. Rust vs. Python)
   4. Memory management and security
3. Functions and program flow, scopes, global and local variables
   1. Function declaration and definition, how to properly comment a function
   2. Program flow a scopes
   3. Global and local variables (why unexperienced programmer should not use global variables)
   4. Global constants and `iota`
4. How program compilation works
   1. [Lexical analysis](https://en.wikipedia.org/wiki/Lexical_analysis)
   2. [Syntax analysis and AST](#)
   3. [Semantic analysis](#)
   4. Code generation (intermediate code and final code)
5. Assembly, instructions, multi platform applications
   1. Assembly language
      1. [x86](https://www.cs.virginia.edu/~evans/cs216/guides/x86.html)
      2. `go tool compile -S main.go > main.asm`
      3. `go tool compile -S -N file.go > file.asm`
      4. `go tool objdump EXECUTABLE_FILE > ASSEMBLY_FILE`
   2. Instruction sets (x86, x64, ARM)
   3. ELF binary vs. PE binary
      1. [ELF](https://en.wikipedia.org/wiki/Executable_and_Linkable_Format)
      2. [PE](https://en.wikipedia.org/wiki/Portable_Executable)
6. Simple debugging
7. Range construct
8. Defer construct
9. Recursion
10. Structures

#### Lesson Resources

- [go doc](https://go.dev/doc/)
- [slices intro](https://go.dev/blog/slices-intro)
- [slices explanation](https://golangbyexample.com/slice-in-golang/)
- [go tools compiler](https://medium.com/martinomburajr/go-tools-the-compiler-part-1-assembly-language-and-go-ffc42cbf579d)

#### Simple tasks

- Write a function that returns the largest element in a list.
- Write function that reverses a list, preferably in place.
- Write a function that checks whether an element occurs in a list.
- Write a function that tests whether a string is a palindrome.
- Write a function that concatenates two lists. [a,b,c], [1,2,3] → [a,b,c,1,2,3]
- Write a function that merges two sorted lists into a new sorted list. [1,4,6],[2,3,5] → [1,2,3,4,5,6]. You can do this quicker than concatenating them followed by a sort.
- Write program that guess original password from md5 hash

### Lesson 3 (7 hours)

*TODO*

- file processing
- flags and program inputs (configs)
- software security

### Lesson 4 (7 hours)

*TODO*

- 

### Lesson 5 (4 hours)

*TODO*
