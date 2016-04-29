# Haskell

Haskell is a lazy, functional, statically , maths-hipster language created by drunk
scotsmen who clearly had some sort of genius-epiphany and created a
work of art.

Haskell is really strict, and sometimes feels like you're tied up
by a mad control freak. That pays off though, when all your code
doesn't segfault all the time and stuff.

An Example of fibonacci (it's kinda naive)

```
fib :: Int -> Int
fib 0 = 0
fib 1 = 0
fib n = 
    fib(n - 1) + fib(n - 2)
```
