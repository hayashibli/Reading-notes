# HTML Links
Links allow you to move from one page to another on the same website or from website to another website. They are created using (<a>) and have an opening tag which includes an attribute called *href* inside it you can put the reference or the path of the link and a closing tag, so when you click on the link text setted between the (a) tags it will take you to another place.
There is different types of links:
1- Linking to other websites: there's something called **absolute URL** this includes the full address of the other site.
2- Linking to other pages on the same website: there's a shorthand for the absolute URL called **relative URL** with this you do not need to specify the domain name in the URL. In the image below you can see the first statement which is an example on the absolute URL and the second one is an example on the relative URL ![image!](https://image.slidesharecdn.com/slideshtmlcss-130114114521-phpapp01/95/learn-html-css-from-scratch-in-30-days-41-638.jpg?cb=1488135662)
3- Email links: to create a link starts up with an email begin the href attribute value with **mailto:** then type the email address you want the email to be sent to.
4- Opening links in a new window: it is done by using a new attribute with its value (target:"_blank") next to the (href) attribute and this attribute is preffered when you want to open another website in a new tab.
5- Linking to a Specific Part of the *Same Page*: an example ((<a href="#top">)).
6- Linking to a Specific Part of *Another Page*:an example ((<a href="http:/www.htmlandcssbookcom/#toppart">)).

# CSS Layouts
Css treats html elements as boxes so they can be either block level boxes or inline boxes. 
- **Block-level elements** start on a new line. 
- **Inline elements** flow in between surrounding text.
- **Containing or parent elements** when a block level box is inside another block box then the outer box is the containing element.
Positioning of the elements using *positioning* property, can be controlled by positioning schemes  :
- Normal flow:  the block-level element appears on a new line down to the page. The syntax is (position: static;).
- Relative Positioning:  moves an element from its normal flow position and shifting it to the top, right, bottom, or left. The syntax is (position:relative;).
- Absolute positioning: positions the element in relation to its containing element. It is taken out of normal flow. The syntax is (position:absolute;).
- Fixed positioning: positions the element in relation to the browser window. Therefore, when you scrolls down the page, it stays in the exact same place. The syntax (position:fixed;)

**Box offset** with its values (fixed,floating) can position a box right, left, top or bottom.

- Floating elements:  allows you to take an element in normal flow and place it to the left or right of the containing
element. Also we can use *float* to place elements next to each other. Clearing floats (clear:) property allows you to say that no element (within the same containing element) and you can use these values with the clear property (right, left, both and none).
When you use relative, fixed, or absolute positioning, boxes can overlap other boxes so the**z-index** property allows you to control which box appears on top.  Its value is a number, and the higher the number the closer that element is to the front.

When creating *columns* use three main properities (width, float and margin).
*Fixed width layout* designs do not change size when the user increases or decreases the size of the browser window used with pixels. Whereas *Liquid layout* designs stretch and contract when the user increases or decreases the size of the browser window used with percentages. 
**Layout Grids**: grid structures used to help in positioning items on a page. They set consistent proportions and spaces between items which helps to create a professional looking design.

# Javascript Functions and Methods
Functions consist of a series of statements that are grouped together to achieve specific task and you can reuse the function as you want rather than repeating the set of statements, Methods are the same as functions but they are written inside a an object.
- To perform a task inside a function statement you should give this function a name and then **calling** it, the response of the function statement is called  **return value** and the return can be multiple of values if we used an array, pieces of information inside the function like: width, height are called **parameters**.
- *Function Declaration* is done by giving the function a name (identifier) followed by parentheses and the series of statements inside the curly brackets to achieve a task. In such cases when you declare a function you give it parameters inside the parentheses, when you call a finction with its parameters you put the values inside the parentheses called (arguments).
- *Calling the function*: is done by typing the the function's name followed by a semi-colon and you can call the same function as you like.
Functions can be written in two ways:
1- Declaration
(function area (width, height)
return width * height;
};
var size= area (3, 4) ; )
2- Expression
(var area = function(width, height) {
return width * height;
} ;
var size = area (3, 4) ;)

- variable's scope :  If you declare a variable within a function, it can only be used within that function. 
A variable inside a function is called local variable and a variable outside the function statement is called global variable.