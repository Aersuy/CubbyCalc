# Calculator Ver 1.02

Simple Console Calculator using C++

## CodeMap

![CodeMap](https://github.com/utilForever/Calculator/blob/master/CodeMap.png)

## How to use

- ?  : Help
- R  : Read expression
- E  : Evaluate and print latest expression
- E n: Evaluate and print nth expression
- P  : Print latest expression postfix
- P n: Print nth expression postfix
- I  : Print latest expression infix
- I n: Print nth expression infix
- T  : Print latest expression tree
- T n: Print nth expression tree
- V  : Print variable table list
- Q  : Quit 

## Version History

- Version 1.00

    - Implement binary operator (+, -, *, /, ^)
    - Implement unary operator (-)
    - Implement trigonometrical function (sin, cos, tan)
    - Implement expression tree (inheritance, polymorphism)
    - Implement infix to postfix converter
    - Implement variable table

- Version 1.01

    - Fix the bug (Recognize "sinx" as not "sin" + "x", but "sinx")
    
- Version 1.02
    
    - Constants refactoring (ExpressionMaker.cpp, ExpressionUtil.cpp → Constants.h)
    - Create help command

## License

<img align="right" src="http://opensource.org/trademarks/opensource/OSI-Approved-License-100x137.png">

The class is licensed under the [MIT License](http://opensource.org/licenses/MIT):

Copyright &copy; 2015 [Chris Ohk](http://www.github.com/utiLForever)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.