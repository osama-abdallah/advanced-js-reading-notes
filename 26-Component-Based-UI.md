# Component Based UI

## React Hello World

The smallest React example looks like this:

ReactDOM
  .createRoot(document.getElementById('root'))
  .render(<h1>Hello, world!</h1>);

It displays a heading saying “Hello, world!” on the page.

## Introducing JSX

It is called JSX, and it is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like. JSX comes with the full power of JavaScript. JSX produces React “elements”.

React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both.

React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

## Rendering Elements

Elements are the smallest building blocks of React apps.

An element describes what you want to see on the screen:

Unlike browser DOM elements, React elements are plain objects, and are cheap to create. React DOM takes care of updating the DOM to match the React elements.

Rendering an Element into the DOM, Let’s say there is a <div> somewhere in your HTML file:

<div id="root"></div>

We call this a “root” DOM node because everything inside it will be managed by React DOM.

Applications built with just React usually have a single root DOM node. If you are integrating React into an existing app, you may have as many isolated root DOM nodes as you like.

To render a React element into a root DOM node, pass both to ReactDOM.render():

const element = <h1>Hello, world</h1>;
ReactDOM.render(element, document.getElementById('root'));

- repo link (https://github.com/osama-abdallah/advanced-js-reading-notes/blob/main/README.md)

- Live Link (https://github.com/osama-abdallah/advanced-js-reading-notes/blob/main/26-Component-Based-UI.md)