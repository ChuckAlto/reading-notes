# 201 Class Reading 7

## Domain Modeling
From the reading at https://github.com/codefellows/domain_modeling#domain-modeling by contributors Ryan Sobol, Sam Hamm, and Keli hansen.
>Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.
From this same reading we are going to construct a program that models the popularity of epic fail videos. first we build a constructor funcion to define the same properties between many objects.
`let epicFailVideo = function(epicRating, has Animals) {`
  `this.epicRating = epicRating;`
  `this.hasAnimals = hasAnimals;`
`}`

`let parkourFail - new EpicFailVideo(7, false);`
`let corgiFail = new EpicFailVideo(4, true);`

`console.log(pardourFail);`
`console.log(corgiFail);`

This is considered `object-oriented programming`
* the `new` keyword creates an object
* The constructor function initializes properties inside that object using the `this` variable.
* The object is stored inside a variable for later use.

## Tables
A table is a way to represent information in a grid containing two axes
* the `<table>` element creates a table where the contents are written in rows.
* `<tr>` is used to indicate a new row.
* Each cell of a table uses a `<td>` table data element.
* A `<th>` element is placed before the `<td>` element to give the row a heading or title.
* A `colspan` attribute is used with `<td>` or `<th>` to spread a cell across multiple columns. 
* the `rowspan` attribute does the same but down across multiple rows.


[main](README.md)
