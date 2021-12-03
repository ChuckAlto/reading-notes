# 205 Class Reading 5

## Images
> A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one. (Jon Duckett, html and css, page 97)
According to Duckett (pg;97) images on a website should
- Be relevant
- Convey information
- convey the right mood
- be instantly recognisable
- fit the color palette

To add an image to a website you use the element `<img>`. this element is an empty element and requires no closing tag. after the `<img>` you wand to give a source for the picture.  if you want to put a picture of yourself titled 'me' on your site and it is located in an images folder the code would look like this.
`<img src="images/me.jpg"/>`
Most code adds an `alt` to the code which shows a text description of the picture. This can be used by screen reader software and search engines.
`<img src="images/me.jpg" alt ="a picture of me"/>`
A Title attribute can also be placed within the `<img>` element. the title will be revealed when a mouse is hovered over the image.
`<img src="images/me.jpg" alt ="a picture of me" title="this here is a picture of yours truely."/>`
Images are also typically given a height and width within the attribute. this controls how large the picture will appear compared to the rest of the website.
`<img src="images/me.jpg" alt ="a picture of me" title="this here is a picture of yours truely." width="100" height="100"/>`

## Color

The colors on your page can make the website look professional or silly, pleasant to look at or a mess. They can make text easy to read or near impossible to differentiate from the background.  Using CSS you can control the use of colors on your website.
You can change the color of your text. for example if you have a `<p>` element. using CSS you can change the text color to white.
` p {`
  `color: white;`
`}`
if you do this thought, you want to make sure the background color makes the text stand out instead of disappearing into it. with a white text the darker the background the better. this is how you change the background color.
` p {`
  `color: white;`
  `background-color: Black;`
`}`
This can bed done in the same place where you turned the text white.  Now you have a white text on a black background.  This will stand out and be easily readable by the end user.
Using CSS you can easily change any color to any shade of any color, and even change the opacity of the color element.

### Text

You can also control the font of your text.  It is important to choose a style that conveys the overall mood of your website.  If you have a business website you don't want to use what might be considered a silly font style.  If you are making a personal website then you can really show off your personality. The font can also effect the readability of your website. There are different typefaces that can be used in different ways.
-Serif; the serif typeface have extra details at the ends of the make strokes. they look a little fancier and were typically used because they were considered easier to read.
-Sans-Serif; Straight ends to the letters with no extras. It is considered a cleaner design and has easier readability if the text is small.
-Monospace; every letter in monospace has the exact same width.  

You can also control the "weight" of text making the text lighter or bolder. The style be it normal, italic, or oblique. you can also stretch or condense the text.

[main](README.md)
