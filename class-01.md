# HTML structure

- HTML stands for **HyperText Markup Language** in which hypertext refers to the html ability to provide links so it allow the user to move
from one page to another easily and markup refers to the ability to to write notes that provide meaning for the content.

- The webpage structure built with an HTML is similar to the newspaper articles as you can see headings, subheadings,
paragraphs, sections, etc. The HTML code is special characters between brackets called HTML elements, which are consist of two tags; 
an opening and closing tags and between them there is a content that tell the browser information. An opening tag mainly consist of two angle 
brackets and a character between them and a closing tag consist of the same thing but with a forward slash before the charachter
, the image below demonstarates the HTML tags:
![image!](https://thepracticaldev.s3.amazonaws.com/i/ccp2ywlxb49q85qsv3of.png)

- There is also something called *attributes*, these provide extra information about an element and located inside the opening tag.They made
up of two parts: a name and a value.
This image clarify the parts of the attribute:
![image](https://www.w3schools.in/wp-content/uploads/2014/07/HTML-attribute.jpg)

- ### HTML structure main parts:
1- Head: contains all the invisible content so they will not appear in the main webpage.
2- Title: it's important to name the tab of the webpage to know what it will talk about and it's located inside the head tags.
3- Body: contains all the visible content that will be shown in the webpage.

- HTML files are text files so you can create your first webpage using any text editor and when you want to save an HTML file type 
(.htm or .html) extensions. If you want to learn new tips about HTML you can always check the source code of any webpage.

- There several HTMl versions since the first web was created and they continue to improve until we now use HTML5 (version 5) 
which was released in 2000. Each webpage should start with Doctype which will tell the browser which HTML version you are using so in the HTML 5 it will appear like **<!DOCTYPE html>**.

- Comments in HTML don't appear on the user's webpage so you can just add comments and notes to your code using **<!--comment is here-->**, so they are very useful for you 
when you check your code after period of time or when other developer want to check your code these comments will ease on him to understand the code.

- ### ID and Class attributes
1- ID attribute: it's a unique identification for a specific element and can't be used for several elements and known as global attribute cause it's applied on any element. 
Its value should start with a letter not a number or any other character and you can style this element with the specific ID as you like on CSS.
2- Class attribute: it's different from the id as you can use it for several elements which all these elements will have the same clss value so on CSS you will be able to 
style these several elements the same.

- ### Block and Inline displays:
1- Block display: Elements start a new line in the webpage so they take the full width of the web, (ex:<h1>, <p>, <ul>, and <li>).
2- Inline display: Elements continue on the same line in the webpage so they take a specific width, (ex:<a>, <b>, <em>, and <img>).

- ### Grouping texts and elements:
1- **In a block** we use <div> element:
This element allows you to group several elements in one block and you can give it an ID or Class attributes.
2- **Inline** we use <span> element:
This element  acts like an inline equivalent of the <div> element and you can give it an ID or Class attributes.

- ### IFRAMES <iframe>
It's an abbreviation for inline frames and it's like a window in the webpage that may conatain a map or a video. There are many attributes that can be placed inside the iframe opening
tag:
1- src: includes the url of the page to show in the frame
2- height: the height of the iframe in px.
3- width: the width of the iframe in px.
4- scrolling: this attribute isn't supported in HTML5 just in HTML 4 and XHTML, and it indicates whether the iframe should have scrollbars or not. 
5- frameborder: this attribute isn't supported in HTML5 just in HTML 4 and XHTML, and it indicates whether the iframe should have border or not in which a 0 value means no border and a 1
value means a border should appear arround the iframe.
6- seamless: a new attribute in HTML5 in which there is no need for scrollbars and it has no value but when present, it specifies that the <iframe> should look like it is a part 
of the containing document (no borders or scrollbars).

- ### Information about your page:
<meta> element doesn't have a closing tag but it contains attributes that carry the information like name and value attributes. The values of the name attribute could be
- description: contains a description of the page.
- keywords:  contains a list of commaseparated words that a user might search on to find the page.
- robots: This indicates whether search engines should add this page to their search results or not.
Also <meta> is located between the head tags which is not visible for the user and it contains information about your webpage like  who created it, and whether or not 
it is time sensitive (expired). The <meta> element also uses the http-equiv and content attributes in pairs with different purposes like if the value of the http-equiv is
- author: defines the author of the web page.
- pragma: This prevents the browser from caching the page so it just store it locally to save time.
- expires:  browsers often cache the content of a page, the expires option can be used to indicate when the page should expire.

- ### Escape charachters
These are used when you want symbols to appear in your webpage like < () [] ' "" trademark, copyright symbols and others.
This image show some of the escape charachters and the codes used to allow them to appear in the webpage:
![image!](https://i.pinimg.com/originals/e9/06/5f/e9065fb4413e79caec092dbc14e1a6cf.jpg)

- ### HTML5 new layout elements:
In the previous versions of HTML webpage authors were using <div> element and provide a class or id attributes to it to identify the role 
of each part. So HTML5 introduce new layout elements to divide the parts of the webpage and these elements are:
1- <header>: which includes the site name (at the top of the page).
2- <nav>: navigation bar which is inside the header element.
3- <article>: includes most of the content which are inserted into sections <section> and each article and section can have its own header and footer.
4- <footer>: which is in the bottom part of the webpage and contains copyright information, links to the privacy policy, social media links
and terms and conditions.
5- <aside>:When it is used inside an <article> element, it should contain information that is related to the article whereas When it is
used outside of an <article> element, it acts as a container for content that is related to the entire page.
6- <hgroup>:  to group together a set of one or more <h1> through <h6> elements so that they are treated as one single heading. 
7- <figure> <figcaption>: the figure can include images, videos, texts, code and graphs, the figurecaption contain a description for the content inside the figure element.
8- <div>: it's still used to group the previous elements together.
SO these elements make the code easier to follow up or to read.

- ### Website
- It's important to identify the target audience that will visit your website and the main reason for visiting it also knowing what information they need.
- Wireframes are usefull in organizing the content in the webpage.
- Sitemaps allow you to plan the structure of the page.
- The design of the website is so important as it attracts users to visit your website.

# Javascript
- first of all javascript is the language that make the user interact with the webpage.
- A *script* is a  series of instructions that the computer can follow to achieve a goal.
- It's better to keep javascript codes into a seperated file with an extension (.js) and then link it in the html file using <script></script>.
