# Read-09

## Concepts of Functional Programming in Javascript

### What is functional programming?

* Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

### Why is this an impure function?

* Simply because it uses a global object that was not passed as a parameter to the function.

### Observation: mutability is discouraged in functional programming.

### The idea is to treat functions as values and pass functions like data. This way we can combine different functions to create new functions with new behavior.

### Pure functions benefits
The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:

* Given a parameter A → expect the function to return value B
* Given a parameter C → expect the function to return value D


[Main Page](https://thaerm94.github.io/reading-notes301)