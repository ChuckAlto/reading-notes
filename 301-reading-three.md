#  301 Reading Three

## React docs - lists and keys

- What does .map() return?

Answer- it returns a new array populated with the results of a function on every element in the original array.

- If I want to loop through an array and display each value in JSX, how do I do that in React?

Answer- loop through using .map() and then us {} to include them in JSX.

- Each list item needs a unique ____.

Answer- Key

- What is the purpose of a key?

Answer- as per the reading https://reactjs.org/docs/lists-and-keys.html

> Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.


## The Spread Operator

- What is the spread operator?

Answer- a syntax for adding items to arrays, combining arrays, and spreading an array into a functions arguments.

- List 4 things that the spread operator can do.

Answer- 1 spreads an array into seperate arguments. 2 adds an item to a list. 3 combines objects. 4 copies an array.

- Give an example of using the spread operator to combine two arrays.

Answer- 
`let array1 = [1, 2, 3];`
`let array2 = [4, 5, 6];`
`let array3 = [...array1,...array2];`

- Give an example of using the spread operator to add a new item to an array.

`let array1 = [1, 2, 3];`
`let array2 = [4,...array1];`

- Give an example of using the spread operator to combine two objects into one.

Answer- 
`let objectOne = {hey: "you"};`
`let objectTwo = {hows: "it going"};`
`let objectThree = {...objectOne, ...ObjectTwo};`

## how to pass functions between components

- In the video, what is the first step that the developer does to pass functions between components?

Answer- create a function wherever the state is that is going to change.

- In your own words, what does the increment function do?

Answer- It changes a value by a set increment. 

- How can you pass a method from a parent component into a child component?

Answer- 

- How does the child component invoke a method that was passed to it from a parent component?

Answer-

[main](README.md)
