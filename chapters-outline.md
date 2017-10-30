# Chapters Outline

## Module 1

Goals:
- Intuition for functions
- Intution for types
- Familiarity with GHCi
- Compile Program

1. Stack and Development Environment
- What is stack
- Download link
- Creating a new project with stack
- Parts of a stack project
  - .cabal
  - .yaml
- Building a project
- GHCi
- Loading modules into GHCi

2. Functions 
- lambdas
- how lambdas are evaluated
- type signatures
  - polymorphic types
  - Int
  - Bool
  - Double
  - Char
  - String

3. Arithmetic
- Basic operators
  - +, -, *, /, div, mod
  - Natural
- Briefly mention (Num a)

4. Basic ADTs
- newtype
- product types
- sum types

## Module 2

Goals:
- Familiarty with lists

5. Records 
6. Polymorphic containers (List)

## Module 3

Goals:
- Intuition for encoding effects with Functors
- Familiarity with Maybe, Either, Reader, State
- Familiarity with fmap, <*>, pure, and >>=

7. Maybe
8. Either
9. Reader
10. State
11. Functor (abstraction over maybe and list) 
12. Applicative multiple arity functions over these 
13. Monad

## Module 4

Goals:
- Familiarity with functions from Control.Monad
- Familiarity with various IO functions
  - getLine, putStr, readFile, random
  
14. Sequencing programs
15. IO and System functions
