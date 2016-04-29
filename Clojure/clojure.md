# Clojure
## [clojure.org](clojure.org)

Clojure is a lisp language that runs on the JVM (Java Virtual Machine). It is a primarily functional language that can interop with Java, Scala, Groovy, and any other JVM langauge.

Clojure also has ClojureScript, a clojure compiler which compiles to Javascript, allowing for front-end work to be done with it.

Clojure uses Leiningen, its build system. You pretty much want to use this, or it will be a pain.

Clojure has been picked up by the web community, as it works great as a web server and the clojurescript stuff goes
great on frontend. 

```
(defn fib [n]
    (+ (fib (- n 1))
       (fib (- n 2))))
```
