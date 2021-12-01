#201 Class Reading 3

## Lists

There are three types of lists in Html. 
* ordered lists `<ol>`- these lists are numbered and needed when a specific order of instructions need to be given. such as in a recipe
* unordered lists `<ul>` - these lists are made with bullet points of varying shape. They are for lists that don't need to have a specific order.
* Definition lists `<dl>` - these are lists that also give a definition of the list item.  
  * the `<dt></dt>` tag goes around the item that needs to be defined
  * the `<dd></DD>` tag goes around the definition.

You can also make lists within lists.  this is called a nested list such as above.

## Boxes

Each html element has it's own box.  These boxes can be manipulated and controled using CSS.  You can control the size of a box by using the `height` and `width` properties. you can tell the browser what to do if there is too much information for a box to contain using `overflow`. You can set a `border` around a box and and style it in shape, color, size, and style.  your border can be closer of further from what is in the box using `padding` and your box can be closer or further from other boxes using `Margin`.  You can center all content in a box with the `text-align` function.

## Arrays

An array is a variable that instead of storing one single value, has the potential to store an entire list of variables. to access a particular value in the array it is the same as a numbered list. Except with arrays the first item in the list is given the value `0`.
for example, in the array
`let food = 'cake', 'steak', 'burrito'`
the item in the first position, cake is at position `0`.  steak is then in position `1` and burrito, while being the third item in the list is in position `2`. up can change a value in an array by selecting it by number and giving it a new value.
food[2] = 'taco'.  This changes the 'burrito' in position 2 to 'taco'

## Switch Statements

From Javascript & Jquery by jon Duckett page 164.
>A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

like and `if` statment but gives a list of possible outcomes `cases` for what variable value is.  Here is a code example.

`let msg;`
`let grade = 2`

`switch (age){`
`case 1:`
  `msg = 'you are in grade 1';`
  `break;`
`case 2:`
  `'msg = ' you are in grade 2';`
`case 3:`
  `msg = 'you are in grade 3';`
`}`

In this example the value will read 'you are in grade 2' since the variable 'grade' is given the value '2' which matches `case 2`

[main](README.md)
