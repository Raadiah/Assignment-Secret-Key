# Question and Answer:

## Q1: What is ES6 and what are the new features introduced in ES6?
Answer: ES6 or EcmaScript 6 is an official release version of JavaScript released on 2015. It contains many modern features and is a major update of the language. The features added in ES6 are: 

1. let and const keywords
2. For..of loop for iterables
3. Classes
4. Maps and Sets
5. Promises
6. Multi-line strings
7. Destructing arrays
8. Parameter Handling
9. Spread and rest operators
10. Symbols
11. Modules
12. Promises
13. async..wait
14. Arrow functions
15. Template literals
16. Enhanced Object literals etc 

## Q2: What is Event Bubble and Event Delegation in JS?
Answer: For nested DOM, the innermost children triggers its event first, then gradually the parents trigger the events sequentially. This upward triggering from children to parent to grandparent and so in, is known as Event Bubble.

Event Delegation is the process through which an event is added to the parent object. The children gets the event of the parent through bubbling effect. Two benefits of event delegation are:

1. Maintains clear code with fewer event handlers
2. Newer child elements automatically gets the event

## Q3: What is the difference between localstorage , session storage and cookies?
Answer: Local Storage saves data locally, and the data is retained even with reload/refresh. The data does not go unless the browser is closed. It works only for data from same-origin. This is generally used so that data is not needed to be fetched repeatedly, or temporary data.

On the other hand, session storage items clear when the session ends. It ends when tab/window is closed. Like local storage, it also works for same-origin only.

Cookies are the information that websites save on local device for recognizing a person in the future. Thus it helps to customize their items according to individual's choice. Every time the website is visited, the cookies are also sent to the server.

## Q4: In CSS what is the difference between display inline, display inline block and display block?
Answer: Inline element goes with the natural flow of the text, and width/height cannot be added to it. It does not take any new line, and other inline/inline-block elements may sit beside it.

Inline-block also goes on the same line, but the difference is that it can have width/height added to it.

Block elements take a new line, does not sit beside any other element and occupies the full width.

## Q5: What are new features in CSS3?
Answer: There are many new features in CSS3. Among them are: flexbox, grid layout, media query, shadow, animation, transitions, transforms, gradient, border-radius etc. These help in more effective styling.