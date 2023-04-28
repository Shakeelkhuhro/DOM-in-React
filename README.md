# DOM-in-React
Learned about DOM, Virtual DOM and Real DOM (Bytewise Fellowship)

## DOM= Document Object Model
It is Object Presenatation for HTML Document and interface of HTML elements outside the
world like JS
The root of the tree is "Document" Object
DOM is an abstraction (hide unnecessary text) of a structured text.
Structure of DOM is called Dom tree.


it works as follows.
 (HTML parse into DOM tree) ===> (Render tree construction) ===>
 (Layout of the render tree ) ===> (Painting the render tree)

 DOM represents the UI of Applications

 ## Virtual DOM
 It is reprsentation of actual DOM 
 React first updates the Virtual DOM and then actual DOM
 Virtual DOM is like blueprint of machine  and Changes in Virtual DOM will not directly apply on machine

 ## Reconcillation
 Virtual DOM is synced with real DOM with ReactDOM library and this proces is called Reconcillation


 ## Diffing 
 React Compares the virtual DOM and pre-updated virtual dom 
 and only marks the sub-tree of components that are upadeted and this proces is know as Diffing
 
 ## Diffing Algorithem
 Algorithem used behind diffing is known as Diffing Algorithem
