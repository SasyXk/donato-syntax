# Donato Syntax Highlighting for Visual Studio Code

This Visual Studio Code extension provides syntax highlighting support for the **Donato** programming language.

---

## Features

- Syntax highlighting for control keywords such as `if`, `then`, `else`, `while`, and `return`.
- Support for variable and function declarations with keywords like `let`, `function`, `struct`, `class`.
- Recognition of access modifiers: `public` and `private`.
- Highlights primitive types (`int`, `bool`, `double`, `void`, etc.) and the `auto` type.
- Constants support for boolean literals `true` and `false`.
- Full numeric literals support: integers, decimals, and scientific notation.
- Proper highlighting of strings with escape sequences.
- Operators support for assignment, comparison, and arithmetic.
- Punctuation highlighting including braces, parentheses, commas, colons, dots, and semicolons.
- Distinction between function names and variable/class names.
- Support for both block comments (`/* ... */`) and single-line comments (`// ...`).

---

## Usage

Open any file with the `.donato` extension in Visual Studio Code. The syntax highlighting will be automatically applied based on the language grammar.

Example code snippet:

```donato
// This is a sample Donato code
class Point2D{
  int x;
  int y;
  public:
    Point2D(int x, int y){
      this.x = x;
      this.y = y;
      return;
    }

    function void setX(int x){
      this.x = x;
      return;
    }

    function void setY(int y){
      this.y = y;
      return;
    }

    function int getX(){
      return this.x;
    }

    function int getY(){
      return this.y;
    }
}

