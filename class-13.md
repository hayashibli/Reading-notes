# Local storage

Persistent local storage is one of the most important things for applications. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data,  and they have 3 disadvantages :
1- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.
2- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet. 
3- Cookies are limited to about 4 KB of data — enough to slow down your application.

Microsoft invented many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called *DHTML Behaviors*, and one of these behaviors was called *userData*. In which the user data allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.

In 2002, Adobe introduced a feature in Flash 6 called “Flash cookies.” it allows Flash objects to store up to 100 KB of data per domain.
In 2007, Google launched Gears, provides an API to an embedded SQL database based on SQLite and they can store unlimited amounts of data per domain in SQL database tables.

**HTML5 Storage**
Certain browser vendors also refer to it as "Local Storage" or "DOM Storage".

- What is HTML5 Storage?
it’s a way for web pages to store named key/value pairs locally, within the client web browser. it is implemented natively in web browsers, so it is available even when third-party browser plugins are not. HTML5 Storage is based on *named key/value pairs*. You store data based on a named key, then you can retrieve that data with the same key, the data can be any type supported by JavaScript, including strings, Booleans, integers, or floats, this data is stored as strings. There are three main methods to use with local storage:
- setItem() : Add key and value to localStorage.  
- getItem() : Retrieve a value by the key from localStorage.
- removeItem() : Remove an item by key from localStorage.
*You can use square brackets instead of setItem and getItem.*

**Tracking changes to the the HTML5 storage**
You can keep track programmatically of when the storage area changes, you can trap the *storage* event which is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually make changes.

