# Ndexcode-Binaries
Ndexcode - the Ndebele programming language binaries

What: Ndebele based programming language
Why: Because I can, you and what army gone stop me?

Ndexcode is a Ndebele programming language, based on the Pinecode Programming language (https://github.com/wmww/Pinecone).
I decided to fork Pinecone and rebuild it incorporating a Southern Ndebele spin on it.

##Sabona Zimbawe (We don't do Hello World Here)
1. Download the binary, be it for Windows or MacOS and exctract it somewhere.

2. Save the following in a ".ndx" source file:
    bhala: "Sabona Zimbabwe"
   
3. Open a terminal window and navigate to where you extracted the Ndexcode binary.
4. Run it as follows in a terminal window:

Windows:
ndexcode \PathToSourceFile\hello_sourceFileName.ndx

or for MacOS
./ndexcode \PathToSourceFile\hello_sourceFileName.ndx

Check out these images if you need further guidance:



## For more code examples and an introduction to the language, check out the tutorials folder in the repository.

##The source code will be available once this mess becomes clean enough to share I promise

## Current State
The features that are currently implemented are as follows:

* Primitive data types `Bool`, `Int` and `Dub`
* All the operators you would expect (`+`, `*`, `%`, `:`, `=`, `>`, `<=`, `&&`, etc.)
* Single and multi line comments
* Flow control (if, if/else, while loop, for loop)
* Constants
* Data structs
* Qoqa aka Tuples
* Inani arrays aka Int Arrays
* Functions
* Amabala and various Amabala operations aka String
* User input
* Running system commands
* Interpreter for rapid development and simplicity
* Transpiler to C++ for max performance
