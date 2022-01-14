# 301 Reading Five

## Thinking in React

* What is the single responsibility principle and how does it apply to components?

Answer- A component should be made to do on single thing. you separate your UI into components and every component matches just one part of your data model.

* What does it mean to build a ‘static’ version of your application?

answer- You build a version that renders the UI with your data but does not have interactivity.

* Once you have a static application, what do you need to add?

Answer- State, to include interactivity.

* What are the three questions you can ask to determine if something is state?

answer- from the reading at https://reactjs.org/docs/thinking-in-react.html
- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.

* How can you identify where state needs to live? 

Answer- You look at what components use the state, then find a common owner component, the state should live in that common owner component or in a higher component to the common owner. That or it can live in it's own component.



## Higher Order Functions

* What is a “higher-order function”?

Answer- from the reading at https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK
> Functions that operate on other functions, either by taking them as arguments or by returning them.

* Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

Answer- It is creating a new function where a new number is returned `m` that is going to be bigger than the inserted number `n`.

* Explain how either map or reduce operates, with regards to higher-order functions.

Answer- from the reading Functions that operate on other functions, either by taking them as arguments or by returning them
>  It builds a value by repeatedly taking a single element from the array and combining it with the current value. When summing numbers, you’d start with the number zero and, for each element, add that to the sum.

[main](README.me)
