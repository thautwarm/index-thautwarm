Index of Thautwarm's own repos
====================================================

P.S: I will list repos of my academic and industrial collaborations in my GitHub profile. So here is only for indexing my own repos, with classification notes.

My blog pages are available at [Site-32](https://thautwarm.github.io/Site-32/), and the contents of this page are

- [Programming Languages By Me](https://github.com/thautwarm/LanguageCollections)
- [Unique Investigations in Python](https://github.com/thautwarm/index-thautwarm#unique-investigations-in-python)
- [Enjoying the Freedom of Julia](https://github.com/thautwarm/index-thautwarm#enjoying-the-freedom-of-julia)
- [Parsing, and fastest Python parser generator over the world](https://github.com/thautwarm/index-thautwarm#parsing)
- [Miscellaneous](https://github.com/thautwarm/index-thautwarm/blob/master/README.md#miscellaneous)


-----------------------------------------------


Programming Languages By Me
----------------------------------------

Check out the large list at https://github.com/thautwarm/LanguageCollections .

Unique Investigations in Python
----------------------------------------------------------

We shall never loss our braveness to address complex problems in real world,
this is the motivation to start the following works.

- Repo: https://github.com/thautwarm/Redy
    - topic: Const expressions, goto statements, LISP macros in Python
    - P.S: 
        It's an "evil" implementation, because things must rely on the existence of Python source files.

        Not offensive but I have to say, in the world of Python, most of others' similar works are this "evil".
        To make things reliable and practical, I then started investigating Python bytecode instructions.
    
- Repo: https://github.com/thautwarm/idris-python
    - topic: Idris Python back end
    
    This allows Idris programming language,
    in which you can make sure your program is correct during compile time, running in Python3.

- Repo: https://github.com/thautwarm/scoping-resolver
    - topic: analysis for Python scopes

    This is extremely useful when you're working with Python's scopes, i.e., things about free variables, cell variables and so on.


- Repo: https://github.com/thautwarm/moshmosh
    - topic: semantics(and even syntax) extensions to Python, which is NOT EVIL(it does not rely on the existence of Python source code, but needs proper bytecode compilation before import)

    As a successor of the repo Redy, this is a general purpose framework, but also provides the fastest(and maybe richest) pattern matching implementation over the Python world as some "builtin" extensions.

- Repo: https://github.com/thautwarm/restrain-jit
    - topic: JIT, as a normal 3-rd party library, compatible with anything in CPython(but not for PyPy).

    This is still WIP, but the mechanisms of doing JIT in this way work. Things are not very difficult, a short but vivid introduction of HOW-TO is given at
    [PyConChina, Chengdu, 2019: 解放python的表达力, 性能和安全性](https://github.com/PyConChina/2019-Slides/blob/master/Chengdu/3_Thautwarm_%E8%A7%A3%E6%94%BEpython%E7%9A%84%E8%A1%A8%E8%BE%BE%E5%8A%9B_%E6%80%A7%E8%83%BD%E5%92%8C%E5%AE%89%E5%85%A8%E6%80%A7_%E8%AF%AD%E6%B3%95%E5%92%8C%E8%AF%AD%E4%B9%89%E6%89%A9%E5%B1%95_JIT_%E9%9D%99%E6%80%81%E6%A3%80%E6%9F%A5.pdf), unfortunately, Chinese only in current stage.

    The reason why I now suspended the development is the busy schedule of graduate students and lacking of a good programming language to maintain a too big and complex codebase myself.

    Lacking of a programming language to develop Python JIT motivates me to create Proud Programming Languages and Urgent Programming Languages.

**I'm particularly familiar with every details of Python Programming itself, and can answer in 1 second for the question like "why the program behaves in this way" or "how to achieve xxx functionalities in Python".**

People in my research fields are usually not willing to give a good comment to Python, I certainly understand their concerns. But for me, Python is special, because this is the first language I found very consistent and spent much time with.


Enjoying the Freedom of Julia
-----------------------------------------------

I started playing with Julia since its v0.4, got involved in the community since its v1.0, and highly praise the active and friendly community of Julia. They do provide good chances to allow users and developers to interact unbelievable frequently.

People there are not only awesome scientists, but also very interesting and knowledgeable guys. For instance, in Julia community, you can find some data scientist with Haskell programming experience, and some physicist addicted to meta-programming.

Besides, Julia language features are awesome, I'm so glad that I can implemented many interesting things from academic world there.

I want to appreciate the community for their appreciations to my works!

- Repo: https://github.com/thautwarm/MLStyle.jl
    - topic: extensible and efficient pattern matching, algebraic data types.

- Repo: https://github.com/thautwarm/CanonicalTraits.jl
    - topic: an implementation for traits/type classes in Julia.

- Repo: https://github.com/thautwarm/GeneralizedGenerated.jl
    - topic: staging programming(Can Racket users imagine zero-cost runtime `eval`?).

- Repo: https://github.com/thautwarm/ParameterisedModule.jl
    - topic: first class and parameterised modules.

- Repo: https://github.com/thautwarm/NameResolution.jl
    - topic: analysis for scopes, can be implemented for every programming language using lexical scopes.

- Repo: https://github.com/thautwarm/JuliaVariables.jl
    - topic: scope analysis for Julia programming languages.

- Repo: https://github.com/thautwarm/HigherKindedPolymorphisms.jl
    - topic: higher kinded polymorphisms implemented in Julia.


- Repo: https://github.com/JuliaCN/Py2Jl.jl
    - topic: Python to Julia transpiler


Parsing
-----------------------------

I used to pay quite a lot of efforts to work out a good parser generator.

Fortunately, I finally succeeded in making **the fastest Python parser generator**,
which is statically generated, and much faster than the other alternatives.

I wasted too much time on PEG and parser combinators during 2017 to the early 2019, because implementations of them in dynamic programming languages are certainly very slow.

I finally made this cross-language parser generator.

- Repo: https://github.com/thautwarm/RBNF.hs
    - topic: parser analysis, optimizations and generators

- Repo: https://github.com/thautwarm/rbnf-rts
    - topic: Python wrapper for RBNF.hs with some very convenient syntax sugars.


The previous attempts(not recommended to use except RBNF.jl):
- https://github.com/thautwarm/EBNFParser
- https://github.com/thautwarm/RBNF
- https://github.com/thautwarm/RBNF.jl
- https://github.com/thautwarm/Ruiko.fs



Miscellaneous
---------------------

- Repo: https://github.com/thautwarm/resume
    - topic: my resume, but usually not updated in time

- Repo: https://github.com/Xython/Linq.py
    - topic: porting C# LINQ to Python, with very good static checking support(in PyCharm)

    Not recommended to use.

- Repo: https://github.com/Xython/pipe-fn
    - topic: runtime pipe operator superior to https://github.com/JulienPalard/Pipe

    Not recommended to use.

- Repo: https://github.com/Xython/auto-orm
    - topic: generating good typed ORM APIs, targeting sqlalchemy.

- Repo: https://github.com/thautwarm/paperbnf
    - topic: generating beautifully-rendered LaTex source, from BNF notations. Tools for writing papers.

- Repo: https://github.com/thautwarm/rsolve.py
    - topic: Solving constraint satisfaction problems based on propositional logic.

- Repo: https://github.com/thautwarm/FSTan
    - topic: Higher abstraction infrastructures in F#(ad-hoc polymorphism, subtypeclassing, monad, hkt...), exactly what we've dreamed about for so long

- Repo: https://github.com/RemuLang/remu-operator
    - topic: resolving operator precedences and, associativity in non-parsing time.

- Repo: https://github.com/thautwarm/graphviz-artist
    - topic: using GraphViz in Python without any learning.

- Repo: https://github.com/thautwarm/LLAST
    - topic: emitting LLVM IRs from recursive IRS like ASTs.


-----------------------------------------
-----------------------------------------


In the summer before entering the university, the desire of programming occurred to me after reading a light novel called "Sword Art Online",
in which an artificial intelligence called "Alice" comes into the real world and lives like a normal individual.

This shocked me, enlightened some part of my mind, and changed my dream from becoming a mathematician of pure math to a programmer.

I was moving forward with non-trivial hard-working(a comment from one of my supervisors during undergraduate period), got across many fields like Bio-informatics, Machine Learning, and finally made the decision to devote my life to the field of Programming Languages.

Although things totally changed years later, creating artificial intelligence is still my dream,
but it is now only a pastime.

I chose Programming Languages, because I found it's the secret to become efficient in working for almost every areas. This could be a little subjective: my idea is, by learning about more of PL, I will be knowledgable and energetic enough to experience more species of programming fields.
