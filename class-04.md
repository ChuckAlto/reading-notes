# 201 Class Reading 4

## Links
 Links provide the user the opportunity to navigate a website or to leave to a specific website that is linked.  There are several different types of links such as absolute, relative, email links, links that open in new windows or tabs, links that take you to a specific part of a specific page, and links that take you to a specific section of the same page.  all of these are structured similarly and all start with an opening `<a>` tag and end with a `</a>` closing tag. a reference telling the link where it is linking to is also necessary, be it an email address, a different site, or the same site. `href="reddit.com"` is an example.  it sits inside the opening `<a>` like this `<a href="http://www.reddit.com">` then outside the `<a>` is what the user will see and click on.  it can be the name of the site or a picture.  in this example we will use the site name.
 `<a> href="http://www.reddit.com"> Reddit</a>`
 this will give a link called reddit that will take you to the reddit address.  This is called an absolute link.

 If you wish to link to another part of the same website you would use a relative link. It looks the same as an absolute link but instead of a full website you can just use the page name.  `<a href="about-me.html">about me</a>`

 If you want to have a link set up for the user to send an email it is again similar to the other two execpt the `href` will be `mailto:` followed  by an email address. `<a href="mailto:chuckalto@gmail.com">email chuck</a>`

 ## Layout

 CSS gives you positioning schemes to control your websites layout.
 * Normal flow - not really a positioning scheme as it is the regular flow of a page. One element follows another down the page.
 * Relative Positioning - removes the element from its normal flow and positions it anywhere in its box without disturbing the surrounding elements.
 * Absolute Positioning - takes the element out of normal flow and makes it so it no long effects the other elements on the page. this position does not move with the page as the page moves.
 * Fixed Positioning - much like fixed positioning but this element will scroll with the page rather than stay in one spot on the page.
 * Floating Elements - Again this takes the element out of normal flow and gives it a position that other elements on the page must flow around it. This element gives you to opportunity to place elements side by side on the page.

 ## Functions
 From "Javascript and Jquery" by Jon Duckett, page 88.
 > Functions let you group a  series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).

 by taking multiple statements that repeat, and placing or grouping them together in the same function lets you write cleaner more understandable code. A function is given a name and will not run until called upon to do so.

 [main](README.md)
