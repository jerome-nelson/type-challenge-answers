# Exercises from Type-Challenges Repository
Taken from https://github.com/type-challenges/type-challenges

## Purpose
To know what I don't know about TypeScript

## Key Takeaways
1. Can access array properties using syntax like so:
    - `T["length"]` - will dynamically return length of literal array type
    - `T[number]` - dynamic reference to array values
2. Extends can be used as a strict equality operator
3. It is possible to use recursion to loop through iterative types

## Revision Points
* Usage of recursive types (as in solution for #898 - easy-includes)