# TinyReact
Tiny React is a lightweight clone of the popular JavaScript library, React. This project aims to provide a simplified yet educational implementation of React's core concepts, focusing on the key aspects of JSX processing, rendering, efficient patching, and component lifecycle.
An educational project designed to help me understand the inner workings of React by building a simplified version from scratch. This taught me how JSX blocks are processed into a lightweight Virtual DOM (VDOM), how the VDOM is transformed into the regular DOM, the importance of the "key" property for efficient patching, and the creation, lifecycle, and rendering procedures of React components.



## Some of the main concepts from React Library which I have implemented
#### Real DOM: 
When a web page is rendered in a browser, the browser creates a representation of the page's structure called the Document Object Model (DOM). The DOM represents all the elements on the page as a tree-like structure, with each element as a node in the tree.
#### Virtual DOM: 
Instead of directly manipulating the real DOM, libraries like React create a lightweight, virtual representation of the DOM in memory. This virtual representation is often called the Virtual DOM. It is a JavaScript object that mirrors the structure of the real DOM.
#### Reconciliation: 
When changes are made to the UI, instead of directly updating the real DOM, React and similar libraries make changes to the Virtual DOM. These changes are typically more efficient because they happen in memory and don't require interaction with the browser's rendering engine.
#### Diffing: 
After the Virtual DOM is updated, it performs a process known as "diffing" or "reconciliation." It compares the updated Virtual DOM with the previous version to determine the minimal set of changes needed to update the real DOM.
#### Real DOM Update: 
Once the minimal set of changes is calculated, React or the library in use updates the real DOM with these changes. This process is more efficient than making direct updates to the real DOM, as it reduces the number of actual changes and manipulations required.



# todo
- [ ] add tests
- [ ] add top level view diagram

## References
[Gooact: React in 160 lines of JavaScript](https://medium.com/@sweetpalma/gooact-react-in-160-lines-of-javascript-44e0742ad60f)

[Gooact Repo](https://github.com/sweetpalma/gooact)
