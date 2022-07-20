# Day02

Differences between Document and Window Objects ?

Document Object:

The document object represent a web page that is loaded in the browser. By accessing the document object, we can access the element in the HTML page. With the help of document objects, we can add dynamic content to our web page. The document object can be accessed with a window.document or just document.

Syntax:

document.property_name;

Methods of Document:

Syntax:

document.method_name;

Document
It is the direct child of the window object. It is aka Document Object Model (DOM).
You can access it via window.document or document.
document object has many useful methods defined on it.
For example, document.getElementById(), document.getElementByTagName(), document.createElement(), document.querySelector() and many more
document API

Window Object:

The window object is the topmost object of the DOM hierarchy. It represents a browser window or frame that displays the contents of the webpage. Whenever a window appears on the screen to display the contents of the document, the window object is created. 

Syntax:

window.property_name;

Methods of Window:

Syntax:

window.method_name;

Window
It is the root level element in any web page.
All the global variables are defined on the window object.
For example, alert(), confirm() are methods defined on the window object.
Writing alert() is similar to window.alert()
Also, properties like document, location are properties of the window object.
window API


