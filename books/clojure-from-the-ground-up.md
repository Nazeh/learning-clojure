# Clojure from the ground up

Chapter 1
  why clojure?
  
    - clojure is concise, expressive.
    - faster than Ruby, python and JS
    - Emphasizes safety in its type system and approach to parallelism.
    - easier to write correct multithreaded programs.
    - REPLs
      - great for beginners to experiment.
      - well suited for manipulating complex data structures.
      - consistently designed Standard library.
      - Full-featured core data-types.

drawbackes
  - much slower to start than scripting languages.
- not well suited for high-performance numeric operations.

========

nil 
true 
false

true false and nil = poles of Lisp logical system

numerics
0 1 -23 1.2e-3 1/2

strings
"ast"


symbols 
    a reference to other values

    adding a ' first evaluates the symbol itself!

    'inc => inc
    '(1 2 3) => (1 2 3)


lisp expression is like a tree (is data itself !!)

(inc (inc 0))
increment
  increment
    number zero

lists starts with verbs/functions followed by zero or more objects to be acted on!

Clojure eavaluates 
  symbols substited by its meanings
  then inner most list first.
  lists are evaluated left to right


Chapter 2

types in clojure are strong and dynamic.

Longs : 64 binary digits
 use one bit to store the sign
 the rest represent the size of the number
    biggest number is 2**63
    Long/MAX_VALUE

other numbers

  BigInt
  integers 32 bits
  shorts 32 bits
  bytes 8 bits

  why all those?


  fractions

    floats 32 bits
    doubles 64 bits default
    ratio 1/3

math operations
  Long + Double = Double (preserve informatio)  

equality
(= 3 3.0) => false
(== 3 3.0) => true

