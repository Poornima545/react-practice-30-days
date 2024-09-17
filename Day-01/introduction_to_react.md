##Getting Started With React

1. What is React?

React is a js library for rendering a reusable user interface(UI). It was initially released on May 29, 2013. The current version is 18.3.1. It was created and maintained by Meta.UI is built from small units like buttons, text, & images. React lets us combine them into reusable, nestable components. From web sites to phone apps, everything on the screen can be broken down into components.

2. What is a library?

A library is a collection of pre-written code that developers can use to optimize tasks. In React, for instance, is a library focused on the view part of applications, providing tools to build UIs.

3. What is a single page application?

A SPA is a web application that loads a single HTML page and dynamically updates the content as the user interacts with the app. SPAs use AJAX and HTML5 to create fluid and responsive web apps, without constant page reloads. The index.html is the only HTML file you will have in any React Application. That is why we say that every React Application is a single page application.

4. What is a component?

In React, a component is a self-contained module that renders some output. Components can be functional or class-based and can accept inputs called "props" (properties) to customize their behavior or appearance. Components are reusable and can be nested within other components to build complex UIs.

5.  What is React Virtual DOM?

The virtual DOM is an in-memory representation of the actual DOM in a web application. When changes occur in a react application, react updates the virtual DOM first rather than the real DOM directly. it then compares the new virtual DOM with the previous one(a process called reconciliation) and determines what changes need to be made to the actual DOM.

6. Why React?

React has become one of the most popular libraries for building UI and there are several compelling reasons to consider using for your next web development project. Here are some key advantages of React:

i. Component-Based Architecture:

React promotes breaking down the UI into reusable, self-contained components, which makes it easier to manage and scale projects. Each component handles its own logic and rendering, making the code more modular and easier to maintain.

ii. Virtual DOM for Performance:

React utilizes a virtual DOM to optimize rendering. Instead of updating the entire DOM when changes occur, React updates only the parts that have changed. This leads to improved performance and a smoother user experience, especially in applications with complex UIs.

iii. Strong Community and Ecosystem:

React has large and active community that contributes to a rich ecosystem of libraries and tools. This means developers have access to a wealth of resources, tutorials, and third-party libraries that can simplify development tasks. 

iv. Backed by Facebook:

React is maintained by Facebook, ensuring long-term support, regular updates, and improvements.

7. JSX

JSX stands for javascript XML. JSX is basically a syntax extension for javascript that allows you to write HTML-like code within JavaScript files. It is primarily used with React to describe what the UI should look like. JSX makes it easier to visualize the structure of components.

`//JSX syntax 
const JSX = <h1>Hello, World!</h1>
const data = <small>Oct 2, 2020</small>`

The above strange looking code seems like JavaScript and it seems like , but it is not JavaScript and it seems like HTML but not completely an HTML element. It is a mix of JavaScript and an HTML elements. JSX can allow us to use HTML in JavaScript. The HTML element in the JSX above is h1 and small.



