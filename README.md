#Questions and Answers:
Question1: What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**? <br/>
##Answer:                                     **getElementById, getElementsByClassName**  <br/>
**getElimentById** method returns an element with a specified value.<br/>
-It returns null if the element does not exist. <br/>
-**getElimentById** method is one of the most common methods in the HTML DOM.It is used almost every time we want to read or edit an HTML element. <br/>
**getElementByClassName** method returns a collection of elements with a specified class name(s).<br/>
-It returns an HTML Collection.It is an array-like collection (list) of HTML elements. The elements can be accessed by index which starts at 0. <br/>

**querySelector** method returns the **first** element that matches a CSS selector. <br/>
**querySelectorAll** method returns **All** matches.<br/>
---------------------------------------------------------------------------------------------------------------------------------------------------
#Question2:How do you **create and insert a new element into the DOM**? <br/>
#Answer: To add a new element to the HTML DOM we must create the element first, and then append it to an existing element. <br/>
----------------------------------------------------------------------------------------------------------------------------------------------------
#Question3: What is **Event Bubbling** and how does it work? <br/>
#Answer: Event bubbling directs an event to its target. It works- <br/>
-when an element(like a button) is clicked ,an event is directed to the element.<br/>
-If an event  handler is set for the element,the event handler is triggered. <br/>
-Then the event "bubles up" to the elements parent. <br/>
-If an event handler set for the parent,this event handler is triggered. <br/>
-The event continues to  bubble,until it raches the top(the document element)
---------------------------------------------------------------------------------------------------------------------------------------------<br/>
