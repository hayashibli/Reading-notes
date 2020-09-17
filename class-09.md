# HTML Forms
Forms are printed documents that contain spaces to fill your information.
**Form controls**
There are multiple types of form controls that you can use to collect information from visitors to your site:
1- To *add text* you can use : 
   - Text input (single-line) :  to fill username or email(contains name, size, maxlength attributes).
   - Password input : to fill a password that appears in black dots(contains name, size, maxlength attributes).
   - Text area (multi-line) : to fill a multiple line text like a message or comments(it contains name attribute, value attribute and checked attribute which indicates that this box should be checked when the page load.).

2- To *make a choice* you can use:
   - Radio buttons : to choose one option.
   - Checkboxes : to check one or more options or uncheck all (it contains name attribute, value attribute and checked attribute which indicates that this box should be checked when the page load.).
   - Drop-down boxes : to select one option from a list after clicking on the dropdown button (drop-down list is created using  (select) element and it contains two or more (option) elements and the select element contain name attribute , selected attribute which indicate that the option should be selected when the page loads , size attribute to determine the number of options that you want to show at once and multiple attribute to be able to select multiple options).

3- To *submit Forms* you can use :
   - Submit buttons : to sumbit information from your page to another one (it contains name and value attributes).
   - Image buttons : similar to submit buttons but this allows to use an image.

4- To *upload files* you can use :
   - File upload : allow to upload files like images to a website ( when you make the type = file then at *text input* with a *browse button* are appeared in the web page).

**How forms work ?**
1- First the user fill his/her information in the form then click on the submit button.
2- The form controls or inputs names are sent along the server with their values that the the user filled or select.
3- The server processes these information using a programming language such as (PHP, C#, VB.net,or Java). It may also store the information in a database.
4-  Finally the server creates a new page to send back to the browser based on the information received.

**How to create a form in the html ?**
By using (form) elements and it should contain the *action attribute* which includes the url to another page on the server that will recieve the user's information after he/she submit them ,also it usually contains the *method attribute* which have two values to send a form either *get* in which the values from the form are added to the end of the URL added in the action attribute and its preffered for short forms or *post* in which values are sent in what are known as HTTP headers and it's preferred for forms that are long ,allows the user to upload files,  that contain sensitive information like a password and *id attribute*.

**How to add inputs inside the form in html?**
You should use (input) elements with its different types as clarified at the beginning of this reading.

**Labelling Form Controls**
The (label)element can be used in two ways. It can:
1. Wrap around both the text
description and the form input
![image!](https://miro.medium.com/max/2756/1*sz6WmtriiOH_5dZLi0CtUw.png)
2. Be kept separate from the
form control and use the for
attribute to indicate which form
control it is a label 

**Grouping Form Elements**
You can group form element by using the (fieldset) element and (legend) element inside it.
![image!](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQhVS3I9n9nunOTv-vWuFpDXPYVFni5KAIdww&usqp=CAU)

**HTML5 form validation and input types**
if the form control has not been filled in correctly a message will appear this is known as form validation(you can use required attribute to show a message).

- HTML5 inputs and attributes:
1- type="date"
2- type="email"
3- type="url"
4- type="search"
5- placeholder attribute : it's value is text that will be shown in the text box until the user clicks in that area.

# HTML lists, tables and forms
**Bullet points styles**
- list-style-type : this property controls the shape of the bullet points.
So for an unordered list (ul), you can use these values : none,disc,circle and square. The ordered list (ol), you can use these values:
decimal, decimal-leading-zero, lower-alpha, upper alpha, lower-roman and upper roman.

- list-style-image : this property allows you to put images as bullet points and it starts with the url of the image.

- list-style-position : this property has two values inside and outside to set the bullet points either inside the text box or outside
to the left of the text block.

- list style : this is a shorthand property in which you can put inside it multiple values related to the bullet points.

**Table properties**
- width 
- padding 
- text-transform 
- letter-spacing, font-size
- border-top, border-bottom
- text-align 
- background-color 
- :hover 

**Border on empty cells in the table**
Empty-cell property has three values; hide, show and inherit.

**Gaps Between Cells**
- border-spacing : this property allows to make spaces between the table cells and its value can be separated into horizantal and vertical
distances with px measurement.
- border-collapse : this property has two values; collapse which collapse borders into single border or separate value which detach borders
from each other.

**Styling forms inputs**
*Text Inputs* can be styled using these properties:
- font-size
- color and backgroung-color
- border and border radius
- :focus
- :hover
- background-image

*Submit buttons* can be styled using these properties:
- color
- text-shadow
- border-bottom
- background-color
- :hover

*Fieldsets* can be styled using these properties:
- width
- color and background-color
- border and border-radius
- padding

*Cursor* property  which allows to control the type of mouse cursor and there are many values for it:

- auto
- crosshair
- default
- pointer
- move
- text
- wait
- help
- url("cursor.gif");


# Javascript Events
Events occur when user interacts with the web page like by clicking a button or a link and other things. After the event occurance it can be used to trigger particular function.

**Different event types**
These events can be used to trigger a function in your JavaScript code. 
**EVENTS FIRE OR ARE RAISED**
When an event has occurred, it is often described as having fired or been raised. 
**EVENTS TRIGGER SCRIPTS**
Events are said to trigger a function or script. 
- UI EVENTS : Occur when a user interacts with the browser's user interface (UI) rather than the web page.
load 
unload 
error 
resize 
scroll 

- KEYBOARD EVENTS : Occur when a user interacts with the keyboard (see also input event) 
keydown 
keyup 
keypress 

- MOUSE EVENTS : Occur when a user interacts with a mouse. trackpad, or touchscreen.
click 
dbl click 
mousedown 
mouseup 
mousemove 
mouseover 
mouseout 

-FOCUS EVENTS : Occur when an element (e.g., a link or form field) gains or loses focus.
focus / focus in
blur / focusout

- FORM EVENTS :Occur when a user interacts with a form element. 
input
change
submit
reset
cut
copy
paste
select

-MUTATION EVENTS* : Occur when the DOM structure has been changed by a script.

DOMSubtreeModified
DOMNodelnserted
DOMNodeRemoved
OOMNodelnsertedlntoDocument
DOMNodeRemovedFromOocument

**HOW EVENTS TRIGGER JAVASCRIPT CODE ?**
When the user interact with the web bage an event is fired and then you can use it to trigger javascript codes using three steps called together as the *event handling*.

1- Select element's node
2- Specify the event
3- Call/ Run your code

**Event listeners** are a more recent approach to handling events.
element.AddEventListener(event, function name)

![image!](https://cdn.tutsplus.com/active/uploads/legacy/flashtuts/074_EventListenersBasics/1.jpg)
 


