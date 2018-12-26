Cb


Tokens and Keywords
    - Math operations use the symbol : "+, -,", use ^ for power
        - also include trip and log
        - root function : root(x, y) computes x to the 1 / y
        - complicated numbers as DOUBLE PRECISION
    - Logical operands are denoted with words : "and", "or", "not", "xor",
    - Defining variables -> Strong-typed language
    - Data width (bytes)
        - ints = 4
        - shorts = 2
        - chars = 1 (no characters explicitly)
        - decimal numbers, long = 8
        - booleans = 1
    - Strings "string" char[6] = "string\0"
    - Comparison Operators are Words
        "x less y" -> x < y
        "x equals y" -> x == y
        "x less equals y" -> x <= y
        "x greater equals y" -> x >= y
        "x greater y" -> x > y
        "not x compWord y" -> ! (x comp y)
    Line Breaks
        - NO semi-colons, we parse until enter ascii value of enter which is 10, NOT carraige return, which is 13.
        - "wrap" at end of line -> next line is a continuation of this line's statement
    Functions
        - Statically typed, so we need to specify return type and parameter types
        Syntax for definition of function :
            returnType funcName(argType0 argName0 argTypeN argNameN) is

    Entry Point for Program is a main function
    
    Sample Dec :
        int x is 3;
        int x is 3
        int x = 3;
        int x = 3


Do Not Include (DNI) :
    - curly braces
