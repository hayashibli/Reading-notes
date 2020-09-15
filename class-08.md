# Css layout
As we know from previous readings that css treats each element in html as a box and this box can be :
- A block-level element: which starts on a new line.
- Inline element : which flow in between surrounding text.
When a block element is setted inside another block element then the outer block element is called **Parent or Containing element**, for example if you put (h1) heading inside the div element so the (div) is the containing element.
*Positioning of the elements* using (positioning property), can be controlled by positioning schemes :
- Normal flow: the block-level element appears on a new line down to the page. The syntax is (position: static;).
- Relative Positioning: moves an element from its normal flow position and shifting it to the top, right, bottom, or left. The syntax is (position:relative;).
- Absolute positioning: positions the element in relation to its containing element. It is taken out of normal flow. The syntax is (position:absolute;).
- Fixed positioning: positions the element in relation to the browser window. Therefore, when you scrolls down the page, it stays in the exact same place. The syntax (position:fixed;)

**Box offset** with its values (fixed,floating) can position a box right, left, top or bottom.
**z-index** property controls which element will be overlapped the other element and its value is a number, the element with higher z-index value will overlap the other element.
- Floating elements: allows you to take an element in normal flow and place it to the left or right of the containing element. Also we can use float to place elements next to each other. 
- Clearing floats (clear:) property allows you to say that no element (within the same containing element) and you can use these values with the clear property (right, left, both and none).

When creating columns use three main properities : (width, float and margin).
### Types of layout
- Fixed width layout designs  : do not change size when the user increases or decreases the size of the browser window used with pixels(px). 
- Liquid layout designs : stretch and contract when the user increases or decreases the size of the browser window used with percentages (%).

### Screen size and resolustion
- Visitors to your site will have different sized screens so your design needs to be able to work on a range of different sized screens.
- Screen resolution refers to the number of dots a screen shows per inch.
- Page sizes : Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide.

**Layout Grids**: grid structures used to help in positioning items on a page. They set consistent proportions and spaces between items which helps to create a professional looking design.

**CSS Frameworks** :  provide the code for common tasks, such as creating layout grids, styling forms. You can include the CSS
framework code in your projects rather than writing the CSS from scratch.

- There are two ways to add multiple style sheets to a page:
1: Your HTML page can link to one style sheet and that stylesheet can use the (@import)rule to import other style sheets.
2: In the HTML you can use a separate (link) element for each style sheet.