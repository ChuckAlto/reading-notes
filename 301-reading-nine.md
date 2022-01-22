# 301 Reading Nine

# Functional Programming Concepts

- What is functional programming?

answer- from the website https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa via wikipedia
> Functional programming is a programming paradigm - a style of building the structure and elements of computer programs - the treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

What is a pure function and how do we know if 
something is a pure function?

answer- it is deterministic and returns the same result if given the same arguments. it does not cause side effects.

What are the benefits of a pure function?

answer- it is easier to test and is immutable.

What is immutability?

answer- It can not be changed and does not change over time.

What is Referential transparency?

answer- a function that always yields the same result for the same input.


## Node JS

- What is a module?

answer- javascript code is split up into modules that have certain functionality and can be called when needed.

- What does the word ‘require’ do?

answer- lets you use a function in another place in the application.

- How do we bring another module into the file the we are working in?

answer- `require('./filename')`

- What do we have to do to make a module available?

answer- `module.exports = function;`

[main](README.md)
