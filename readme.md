1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans: Difference between Selectors: 

getElementById() → Selects one specific element by its unique id.
getElementsByClassName() → Collects all elements that use the same class name.
querySelector() → Returns only the first element that matches a CSS selector.
querySelectorAll() → Returns all elements that match a CSS selector as a list.

2. How do you create and insert a new element into the DOM?

Ans: Creating and Inserting Elements into the DOM:

A new element can be created with createElement and then added inside an existing element using methods like appendChild. For example, a new paragraph can be created and then placed inside a div with a given id.

3. What is Event Bubbling and how does it work?

Ans:Event Bubbling :

Event bubbling means that when an event occurs on a child element, it also moves upward to its parent, then to the grandparent, and continues until it reaches the root of the document.

4. What is Event Delegation in JavaScript? Why is it useful?

Ans: Event Delegation: 

Instead of setting separate event listeners for each child, a single listener can be placed on the parent. The parent then manages events coming from its children by checking the event target. This makes the code more efficient and works well for dynamically added elements.

5. What is the difference between preventDefault() and stopPropagation() methods?

Ans:Difference between preventDefault() and stopPropagation(): 

preventDefault() → Stops the browser from performing its usual action for that element (such as a form submitting automatically).
stopPropagation() → Prevents the event from traveling further up the DOM tree, meaning the bubbling process will stop at that point.


 -- Thanks.
