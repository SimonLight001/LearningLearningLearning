# Haskell Syntax

Haskell has a syntax that's quite strange if you come from other langauges.
ML family languages probably have the closest, although they lack the
extra complexity that the monads bring.

```
-- Two dashes denote a one line comment
-- This is a comment

-- This is a functions type signature
-- it takes two Ints and returns Int
-- below is the function definition. given x and y, it returns x + y
add :: Int -> Int -> Int
add x y = x + y

-- Haskell can also do 'pattern matching' functions
alphabet :: Int -> String
alphabet 1 = "a"
alphabet 2 = "b"
alphabet 3 = "c"
alphabet n = "Too big a number!"
-- These can be used instead of a "case" statement in other languages
```
