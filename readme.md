
 ## 1. 
- getElementById selects a single element by its ID.
- getElementsByClassName selects all elements with a class and it returns HTMLCollection.
- querySelector selects the first matching element, querySelectorAll selects all matching elements and it returns NodeList.
 ## 2.
 - First create a new element by document.createElement("tag") .Then
- Set content with .innerText or .innerHTML.
- Insert it into the DOM using .appendChild().
## 3.
- When an event happens on an element, it first runs the event handler on that element, and then it "bubbles up" to its parent elements, executing their handlers as well.
## 4.
- Event delegation is a technique where instead of adding event listeners to many child elements, add a single listener to a parent element and the event bubble up.
- Useful for handling dynamic content efficiently.
## 5.
- preventDefault() stops the browser’s default action (like form submit or link navigation).
- stopPropagation() stops the event from bubbling or capturing further in the DOM.