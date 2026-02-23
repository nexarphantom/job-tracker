1) What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
getElementById is use to select a element using id.
getElementsByClassName is used to select elements using class name.
querySelector is more flexible because it uses CSS selectors. It returns only the first element that matches the selector.

2) How do you create and insert a new element into the DOM?
To create a new element, we use document.createElement(). After creating it, we can add text, attributes, or classes to it. Then we insert it into the DOM using methods like appendChild().

3) What is Event Bubbling? How does it work?
Event bubbling is a process where an event starts from the target element and then moves upward through its parent elements.

4) What is Event Delegation in JavaScript? Why is it useful?
Event delegation is a technique where instead of adding event listeners to multiple child elements, we add a single event listener to their parent. so, its is very useful

5) What is the difference between preventDefault() and stopPropagation()?
preventDefault() stops the browser’s default behavior. For example it can prevent a form from submitting and stop a link from navigating to another page.
stopPropagation() stops the event from moving up (or down) the DOM tree. It prevents event bubbling.
