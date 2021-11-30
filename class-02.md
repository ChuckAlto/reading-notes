# 201 Class Reading 2

## Text

Text can be added to a website in multiple ways.
* to make a large header and sub headers you use the `<h1>` `<h2>` through `<h6>` tags h1 being the biggest and h6 being the smallest
* to make paragraphs you use the `<p>` tag.  each p tag will start on a new line.
You can also manipulate text within the header or paragraph.
* `<b></b>` surrounding text makes that text bold.
* `<i></i>` surrounding text makes text italicized.
* `<sup></sup>` surrounding a word or number or suffix turns it into a superscript.
* `<sub></sub>` surrounding a word or number turns it into subscript.
* `<br />` after a word breaks the paragraph and the next word will be placed on a new line.
* `<hr />` is a way to change themes or a topic.  Placing this in your text will add a horizontal rule between sections of text.

## CSS

If HTML is the framework and walls of a house, then CSS is the interior designer.  CSS is used to decorate a website, from colors, to text to animation, to images. I think Jon Duckett put it best on page 229 of his book "Html&css"  

> The key to understanding how CSSS works is to imagine that there is an invisible box around every HTML element.

When given the address of this box, CSS is able to control the design elements within. if doing this in a seperate CSS code you must first give the address which is the name of the element or tag you want to be effected.  then the instructions for that element must be wrapped in `{ }` curly brackets.  Here is an example of a common code to change the color of text and background of a headline.
`h1{`
    `background-color: red;`
    `color: green;`
`}`
This CSS command turns the background of the h1 header red and the color of the text green.

## Javascript

Javascript adds interactivity to a website. It does this by way of scripts or written commands for what the computer needs to do. 
Jon Duckett wrote on page 56 of "Javascript&jquery"
> A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. 

A sample of a script that might make if they wanted their website to ask the end user their name.
`let user= prompt("What is your name?")`

this will prompt the user to type in their name.  after their name is typed and they hit ok the name can be printed to console with 
`console.log(user)` 
or printed back to the user with a greeting, such as.
`document.write("Welcome " + user)`
on the website the user will see Welcome and their name.

the "user" in the code is considered a variable, what the end user types into the name field gives that variable a value. a variable can store a value as a number, a string, or a boolean true/false.
There are several rules for naming a variable.
* a variable must start with a letter, a `$` dollar sign or an `_` underscore.
* variables are case sensitive
* variables must never contain a `-` dash or a `.` period. nor can you use keywords that tell javascript to do something.


[main](README.md)


