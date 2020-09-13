# Objects
They contain a set of variables known as *properties* and have their own values as well as containing functions known as *methods* to create a model of something.
- Properties tell us about the object.
- Methods represent the tasks that are associated with the object.
Variables and functions inside an object have names and values and the name called *key*, an object can't have two keys with the same name.
-The value of a **property** can be a string, number, Boolean, array, or even another object. The value of a **method** is always a function. 
**Literal Notation** is the easiest way to create objects in javascript.
- The object is the curly brackets and their contents which is stored inside a variable. Separate each name/key from its value with a colon,
and separate each property and method with comma.
**Dot Notation** allows you to access any property or method. Also you can access them by using square brackets.3
To delete a property you can just type ( delete hotel.name;) and if you want to clear the value of a property you can type (hotel.name='';).

**DOM** stands for document object model, It's a model of a webpage and specifies how browsers should create HTMl elements that javascript can access them. Also it
is not a part of the HTML or javascript, it's considered as a seperate set of rules. **This model consists of 4 types of nodes**:
1- The document nodes
2- Elements nodes
3- Attribute nodes
4- Text nodes

-Every element, attribute, and piece of text in the HTML is represented by its own *DOM node*. Each node is an object with methods and properties, so scripts
access and update the DOM tree and all the changes made in the DOM tree are reflected on the browser.
- Accessing and updating the DOM tree involves two steps:
1: *Locate* the node that represents the element you want to work with.
2: *Use* its text content, child elements, and attributes. 

- SELECT AN INDIVIDUAL ELEMENT NODE : can be done using either (getElementById()) or (querySelector()).
- TRAVERSING BETWEEN ELEMENT NODES  : you can move from one element node to another through (parentNode, previousSibling/ nextSibling , firstChild/lastChild).
- SELECT MULTIPLE ELEMENTS (NODELISTS) : you can select more than one element node by using (getElementsByClassName(),getElementsByTagName() ,querySelectorAll()).

A *Nodelist* is a collection of element nodes.There are two ways to select an element from a Nodelist:
- The item() method 
- array syntax.
Both require the index number of the element you want. 
You can repeat the actions for an entire Nodelist using a *For loop*.
- TO ACCESS & UPDATE A TEXT NODE USE (.nodeValue) 

**Two different ways for adding and removing content from the DOM tree**
- innerHTML property
- DOM manipulation

**Attributes nodes**
There are two steps to access and update an element's attribute:
1- Select the element node that carries an attribute.
2- Then use different properties and methods to work with the attribute including:
  - methods: (getAttribute(), setAttribute(), hasAttribute(), removeAttribute() ).
  - properties: (className, id).