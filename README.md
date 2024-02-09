## Kimbo Programming Language Compiler
Kimbo is a simple language designed to resemble BASIC with a straightforward syntax.
Prior to this project, I had little to no knowledge about compilers, but through the process of building this compiler, I gained a solid understanding of how they work.

### Features

- **Lexer**: The lexer tokenizes the source code, breaking it down into individual tokens.
- **Parser**: The parser ensures that the code follows basic grammar rules set for the Kimbo language.
- **Code Emitter**: The emitted code is in C++, making it executable after compilation.

### Example

Here's a simple Kimbo program:

LET x = 5
LET y = 7
PRINT x + y

When compiled, it produces the following C++ code:

#include <iostream>
using namespace std;
int main() {
    int x = 5;
    int y = 7;
    cout << (x + y);
    return 0;
}


### Usage

To use the Kimbo compiler:

1. Clone this repository.
2. Navigate to the project directory.
3. Run the compiler with your Kimbo source code file as input.
4. Compile the generated C++ code using a C++ compiler.
5. Execute the compiled program.
