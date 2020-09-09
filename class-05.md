# HTML Images
When you make a site usually you need to add an image cause images can clerify the text you wrote also they make your site's style better. Also it's preferred to create a folder for all your images so you can easily get them when making your site.
### Adding images on HTML
You can add an image (*jpeg, gif, or png format*) to your site by using the (img) empty tag inside the html file with its attributes (src) which includes the path of the image, (alt) which is an alternative if the image didn't show up so it describes the image in words and you can use (title) attribute to add more information about your image. You can control the size of an image by using (width) and (height) attributes in pixels. An image can be placed in different locations:
1- Before a paraghraph.
2- Inside the start of the paragraph.
3- In the middle of the paragraph.
If the image is *followed by a block level element* then a new line is made after it whereas if it's inside a block level element any text or inline elements will flow around the image. An old code was used to align images horizantally or vertically using (align) attribute.
- Images that are created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.
### Figure and Figure caption HTML5
You can write a caption for an image by putting the (img) tag inside the (figure) tag and then write the caption of the image between the (figcaption) tags.

# CSS Colors
- The color property in css allows you to put any color you want for any text and the colors in css come in three ways:
  1- RGB : this contain how much there red, green and blue in a color and it's written in this way (rgb(255,255,255)), so its values ranges between 0-255.
  2- Hex : this is consider as a code begin with # and have six digits (#FFFFFF).
  3- Color names ; this simple by only writting the name of the color (color: red;)
- Background-color properety allows you to put a color in the background of any text using any of the three different color ways.
- Opacity property in CSS3  allows you to specify the opacity of an element and its values ranges between 0.0-1.0 so there is a value called rgba in which includes the rgb color + the opacity which is the fourth value.
- HLS and HLSA in CSS3 contain three properities: Hue (angle between 0 and 360), lightness (%) and saturation(%) and HLSA includes the same but + a fourth property called alpha indicates the transparency (number between 0 and 1.0.).

# CSS Text
- Font-weight:property effect the text with values; bold, bolder, light or lighter.
- Font-style: effect the text with values; normal, italic, oblique.
- Font-stretch: effect the text with values; condensed, regular or extended.
- Font-family: this property allows you to choose the typeface of text.
- Font-size: allows you to specify the size of the text using pixels, percentages or em measurements.
- @font-face: allows you to use a font, even if it is not installed on the user's computer and following it the path of that font (src).
- Text-transform: a property that transforms your text into uppercase or lowercase and i has three values; uppercase, lowercase and capitalize(make the first letter of each word a capital letter).
- Text-decoration: a property with different values; none, underline, overline, line-through and blink(this animates the text and make it flash on/off).
- Word-spacing: a property makes spaces between words.
- Letter-spacing: a property makes spaces between letters.
- Text-align : This property align your text to right, left, center or use justify value which indicates every line in a paragraph, except the last line, should take the full width of the containing box.
- Verticle-align: this property is most commonly used with inline elements and its values are:
1- baseline
2- sub
3- super
4- top
5- text-top
6- middle
7- bottom
8- text-bottom
- Text-indent: property allows you to indent the first line of text within an element.
- Text-shadow: property gives a shadow for the text and it value takes  three lengths and a color for the drop shadow (the first lenght indicates how far to the left or right, the second one how far to the top and bottom , the third value is optional indicates the blur ).
- :first-letter and :first-line : ( they are called pseudo-elements) you can specify any property for them and change whatever you want in them.
- :link, :visited  : (pseudo-classes) you can style unvisited and visited links by setting any property in these.
- :hover  : this is applied when a user when hover over an element.
- :active :applied when an element is being activated by a user; for example, when a button is being pressed or a link being clicked. 
- :focus  : Any element that you can interact with, such as a link you can click on or any form control can have focus.

**If you need extra information you can check this [website](https://www.tutorialrepublic.com/css-tutorial/)**
