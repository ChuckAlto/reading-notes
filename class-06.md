# 201 Class Reading 6

## Objects
Objects group together a set of variables and functions. If a variable is part of the object it becomes  known as a `property`. If a function is part of an object it is known as a `Method`. A property has a name and a value. The name is known as the `key` the value can be a string, boolean, number, array, or another object. a method also has a `key` but the value is always a function. here is an example of an object with the variable bob. this object is being created using `literal notation`
`let bob = {`  
`name: 'bob',`  
`age: 32,`
`weight: 210,`  
`}`

In this object `bob` we have the `keys` `name`, `age`, and `weight` and they have corresponding values. 

### Accessing objects
  from Javascript and Jquery by Jon Duckett page 103.
  > You access the properties or methods of an object using dot notation. you can also access properties using square brackets.

  to use dot notation you first give the name of the object. folowed by a period then the name of the property.
  `let bobInfo = bob.name;`
  to use square brackets.
  `let bobinfo = bob['name']`  

## Document Object Model `(DOM)`
From Javascript and Jquery by jon Duckett page 184.
>The Document Object Model `(DOM)` specifies how browsers should create a model of an HTML page and how Javascript can access and update the contents of a web page while it is in the browser window.
The DOM is not javascript nor html. It is a set of rules that covers.  
* Making a model of the html page-the DOM tells the computer how a website should be structured when it loads.
* Accessing and changing the html page-updats objects in the model which updates what is shown in the browser.

The DOM is sometimes called an application programming interface `API` 

[main](README.md)
