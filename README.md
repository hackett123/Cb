Cb

Mantra
    - Cb is a pod-oriented language
        - A pod is a structure containing member fields and methods
        - All variables and methods must be defined in a pod
        - The Main pod is mandatory for a Main() method entry point
            - The Main pod contains only the Main() method for now
        - Standard Cb Library folder (with Math.cb)
        - Stick to C++ mantra: only pay for what you use 
            - Imports are explicit and done at the top of the definition of the pod that is doing the importing
            - Syntax is "Import Math", "Import Math.Trig", "Import Math.Trig.Sin"
        - Stage 1 of Cb: Everything is Public
        - Interpod communication is done through variableName.member
            - int count is podInstance.count
        - Static members are accessed through PodName.sMember
            - int maxSize is Pod.sMaxSize

    dynamic security clearance system


Control Flow: 
    - For loops: for [(optional variable declaration) and instantiation] to [end condition] by [step change]
        - for int i is 0 to 10 by +1
        - for int i is 100 to vec.y by vec.step
        - for i to 10 by + 2
        - Can also omit the step change to use the default (+1)
        - for int i is 0 to 10
    - Foreach loops: TBD
    - Foreach loops w/ iterator: TBD
    - While loops: while [condition]
        - while i more equals 0
    - Do While loops: do [code] while [condition]



Tokens and Keywords
    - Math operations use the symbol : "+, -, etc", use ^ for power
        - also include trig and log
        - root function : root(x, y) computes x to the 1 / y
        - complicated numbers as DOUBLE PRECISION
    - Logical operands are denoted with words : "and", "or", "not", "xor",
    - Defining variables -> Strong-typed language
    - Data width (bytes)
        - ints = 4
        - shorts = 2
        - chars = 1 (permit number vals or explicit character input in single quotes 'a' '\t' etc)
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

Arrays
    - Type[] 
    - Arrays are initialized either with a given size or a list of contents
        - int[] array
        - int[] array is an int[5] 
        - int[] array is 1, 2, 3, 4, 5 
    - Array filling with iterators TBD
    - Array members include: 
        - int length: the length

TODO: Array pod with common functions (a la extention methods) 
    
Sample Dec :
        int x is 3;
        int x is 3
        int x = 3;
        int x = 3

    

TODO: 
    - lists
    - iterators 
    - foreach loops

Do Not Include (DNI) :
    - curly braces
