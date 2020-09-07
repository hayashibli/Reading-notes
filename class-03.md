# HTML Lists
There are three main types of lists:
1- Ordered list (<ol></ol>): The items (<li>item</li> )inside this list are numbered.
2- Unordered list (<ul></ul>): The items inside this list are unordered so they start with bulletpoints.
3- Definition lists (<dl></dl>): This list includes terms (<dt>term</dt>) and their definitions (<dd>term's definition</dd>).

- *Nested list* or *sub list* means list inside another , so for example if you made an ordered list you can put another list inside one of the ordered list's items.

# HTML Boxes
As we say previously that CSS treats HTML elements like a box, so using CSS you can give multiple properities for these boxes such as:
1- Change thes dimensions of your boxes: The dimensions are *width* and *height* and you can use pixels(px), ems(em) or percentages(%). Also there are *min-width, min-height* which indicate the smallest box size that will display in the user's screen when narrowing the and *max-width, max height* which indicate the largest box size that will display on the user's screen when stretching the browser's window. There is a property called *Overflow* responsible for telling the browser what to do if the content contained within a box is larger than the box itself and it has two values:
 - Hidden: it hides the extra content that didn't fit within the box
 - Scroll: it adds scrollbars to be able to see the full content inside the box just by scrolling.

2- Create borders around boxes: Every box has a border even if it's transparent in which it seperates the edge of a box from the another. Borders can have different *styles* ex:(solid,doubled,dotteted, etc) , *widths* ex: (any value in px or thin, medium or thick) and *colours*. You can type all the properities of a border in one line like this (border: 5px solid red;).

3- Set margins and padding for boxes: These are responsible for how the box will appear in which margins are outside the box so they are responsible for the gaps between boxes and padding is the space between the border and the content. To center a box in a webpage you should give it a width unless it will take the full width of the window then putting margin-left and margin-right **auto**.

4- Show and hide boxes: Through visibility property and it has two values; visible (show the element) and hidden(hide the element).

### CSS3 new border and boxes properities
- Border-image: applies an image to a box's border

- Box-shadow: applies a shadow for the box and its values are horizantal offset(x), vertical offset(y), blur, spread and colour.

- Border-radius: it gives the ability to make the border's corners rounded and the size of radius is by pixels, also you can create complex corners shapes by specifying values for the horizantal and vertical parts.

# Javascript Arrays
You can create an array by writing a variable and give it the name of the array and the values are assigned inside square brackets and 
separated by commas and they don't need to be the same data type. The image below is an example of an array and this method called *array literal*:
![image!](https://www.wikihow.com/images/d/d4/69157-10.jpg)
To put values for the variables inside the array , they are accessed as if they are in a numbered list and this list start from the number zero not one. so each variable in the array is given a number called index. Each array has a property called length, which holds the number of items in the array. 

# Javascript Decisions and loops
1- If- else is a conditional statement which checks a condition so if the statement is true the (if code block ) will be executed but if it's false then the (else block code) will be executed.

2- Switch statement: start with a variable called switch value, and there are *cases* contain values for the variable. Also a (break;)should be written after each case so not all the cases will be executed. It has a default option if none of the cases match.

There is something called **type coercion* in which javascript converts the data type behind the scences just to complete the operation.

Loops check a condition if it's true the code block will run until the answer is false then it will exit the loop. There are three types of loops:
1- For loop: is used to run a code block specific number of times. it consists of initialization, condition and update.

2- While loop: is used to run a code block unlimited number of times until the answer is false then it will exit the while loop.

3- Do While loop: is similar to while loop but it differs in running the statement inside the curly bracket at least one time even if the answer is false.




