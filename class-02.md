![image](https://image.shutterstock.com/image-photo/image-260nw-1189540408.jpg)
# HTML
- What is a markup?
It's also called tags which give a meaning for your text, and there are two types of markup:
1- Structural markup: these are tags used to describe headings and paragraphs.
2- Semantic markup: these provide extra information like; header, footer and article and they will not effect the structure of the page.

## Structural markup

### Headings 
There are six html headings : h1, h2, h3, h4, h5 and h6 with different sizes in which h1 is the largest heading and it's used as main heading whereas h6 is the smallest heading. Small headings are used as sub headings.

### Paragraphs
You can create a paragraph in html by placing it between two paragraph tags <p> Here is ypur paragraph</p> and when you write multiple paragraphs below each other , the browser automatically will start each paragraph in a new line with a space between them.

### Bold and Italic
If you write a text between these tags <b> word </b> it will appear **bold** so visually it will be different from the rest of the text, it's usually used with keywords. As well as writing a text inside these tags <i> word </i> it will appear *italic* and it's usually used with foreign words, technical terms and names of specific thing like ships.

### Superscript and Subscript 
These tags <sup> </sup> are used to write superior text or number like power in math or the suffixes of dates. On the other hand these tags <sub> </sub> are used to write inferior text like the small numbers in chemical equations.

### White Space
- What is a white space?
It's a space between the codes or text in which webpage authors use it to make their code easy to follow and this space will not be visible in the browser because it will consider several spaces as one space only.

### Line breaks and Horizantal rules
- A line break tag <br /> is an empty tag so there is no (closing tag) and it's used to breake the text into a new line.
- A horizantal rule <hr /> is  also an empty tag and it's used to add a horizantal line as a break between themes or sections.

## Semantic markup

### Strong & Emphasis
- When you write a text between strong tags <strong></strong> it will appear strong like bold and it's indicate that this information is important.
- When you write a text between emphasis tags <em></em> it will appear italic but it has a different meaning like it's important.

### Quotations
There are two types of quotation elements:
1- <blockquote> </blockquote>: these are used for long quotes that take several lines.
2- <q> </q>: these are used for short quotes that sit within a paragraph.

### Abbreviations & Acronyms
These tags <abbr></abbr> are used for both abbreviations and acronyms.

### Citations & Definitions
- <cite></cite>: they are used when you are referencing any piece of work like a book, poem or film.
- <dfn></dfn>: they are used when you want to define a new term.

### Author details
Details like email-address, phone number or place of living can be written between address tags <address></address>.

### Changes to Content
A content is changed if you use these tags:
- <ins></ins>: these show the content that is inserted 
- <del></del>: these show the content that is deleted from it
- <s></s>: these indicate that the content is no longer accurate or relevant but it shouldn't be deleted.




# CSS 
Stands for cascading styling sheet and it includes rules that are responsible for styling the webpage and how the html content should be displayed, also CSS see each html element as a box. CSS rule contains two parts:
1- Selector: indicates the element that the rule will be applied on and it's allowed to give more than one selector the same declaration by seperating them with commas.
2- Declaraion: indicates the style of the element and it consists of two parts which are seperated by a colon :
   - Property: indicates the aspect of the element needed to be changed.
   - Value: indicates the setting for the property.

- There are three ways to style the webpage with CSS:
1- The best method to style the html file is the **external CSS file** then linking it inside the head tags in the html file using <link/> tag with its attributes:
- href: indicates the path of the css file.
- rel: indicates the relationship between the html file and the file it linked to in which th value for css file is **stylesheet**.
- type: this specifies the type of file that is linked to the html snd the value for css is always **text/css**.
2- Internal CSS: this method style the webpage by using the style tags <style></style> into the head elements in the html file.

# Javascript
One of the most important programming languages which is responsible to make the webpage dynamic and enables the user to interact with it. Javascript use scripts for coding which are a series of instructions that the computer follow to achieve specific goal and each instruction is called statement and it should end with a semicolon.

### Comments
Comments are useful even they are invisible but by writing comments to explain what your code does , makes your code easier to read. So comments in Javascript are two types:
1- Multi-line comment: using   /* here is your multiple line comments*/
2- Single-line comment: using     // here is your single comment

### Variables
A script will have to store some information temporarily so it use variables to store data into it.
- **How to use variable?**
  - You should give any variable a name which called also an (identifier) and it's important to assign a value for the variable like the image below:
     
![image!](https://image.slidesharecdn.com/deck-8983a1d9-68df-4447-8481-3b4fd0de734c-9-23-711-170808194636/95/build-a-game-with-javascript-8-638.jpg?cb=1502221614) 
 
  - There are rules for naming a variable:
  1- Start with (a letter, $ or _ ) **only**.
  2- Can contain (letters, numbers, $ or _ ).
  3- Variables are sensitive so you should ensure that you write the name in capital letter or small letter.
  4- Use a name that describes the information.
  5- If the name is more than one word you should write the first letter of each word in capital letter.

### Data Types
Javascript distinguishes between different data types such as:
1- Strings: indicates text or numbers between single or double quotations like; 'hello' , '99', "haya". It's possible to use quotes inside a string like if you use single quote inside the string you should surround it with double quotations and vice versa.
2- Numbers: indicates numerical value like; 77 , 100.
3- Boolean: indicates True or False.

- **Array** is a special type of variable because it can store a list of values and it written in this way:
var colors;
colors ['white', 'black', ' custom']; 
The values can be added on the same line or on seperated lines.

### Expressions
There are two types of them:
1- Expressions that assign a value to a variable.
2- Expressions that use two or more values to return a single value.

### Operators
Which are things that the expressions rely on and they allow to create one value from one or more values.
* Types:
- Assignment operators: assign a value to a variable.
- Arithmatic operators: perform basic math.
- String operators: combine two strings.
- Comparison operators: compare two values and the result will be true/false.
- Logical operators: combine expressions and result will also be true/false.

### Conditional statements
They allow your code to make decisions about next step.
if ... else statements allow you to run one set of code
if a condition is true, and another if it is false.

### Comparison operators 
(===, ! ==, ==, ! =, <, >, <=, =>) are used to compare two operands.

### Logical operators 
Allow you to combine more than one set of comparison operators and they are ( &&AND  !NOT  ||OR).


If you need more information about codes click [here](https://www.w3schools.com/)