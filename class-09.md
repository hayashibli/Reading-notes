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



