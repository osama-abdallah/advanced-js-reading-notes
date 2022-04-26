# useState() Hook

## Making Sense Of Hooks

We know that components and top-down data flow help us organize a large UI into small, independent, reusable pieces. However, we often can’t break complex components down any further because the logic is stateful and can’t be extracted to a function or another component. Sometimes that’s what people mean when they say React doesn’t let them “separate concerns.”

These cases are very common and include animations, form handling, connecting to external data sources, and many other things we want to do from our components. When we try to solve these use cases with components alone, we usually end up with huge components that are hard to refactor and test, duplicated logic between different components and lifecycle methods and/or complex patterns like render props and higher-order components.

We think Hooks are our best shot at solving all of these problems. Hooks let us organize the logic inside a component into reusable isolated units.

## The State Hook

A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.

If you write a function component and realize you need to add some state to it, previously you had to convert it to a class. Now you can use a Hook inside the existing function component.

A “state variable”. This is a way to “preserve” some values between the function calls — useState is a new way to use the exact same capabilities that this.state provides in a class. Normally, variables “disappear” when the function exits but state variables are preserved by React.

The only argument to the useState() Hook is the initial state. Unlike with classes, the state doesn’t have to be an object. We can keep a number or a string if that’s all we need. we just want a number for how many times the user clicked, so pass 0 as initial state for our variable. (If we wanted to store two different values in state, we would call useState() twice.)

It returns a pair of values: the current state and a function that updates it. This is why we write const [count, setCount] = useState(). This is similar to this.state.count and this.setState in a class, except you get them in a pair.

## Hooks Api and Reference

Hooks are a new addition in React they let you use state and other React features without writing a class.

below are built-in Hooks in React.

Basic Hooks:

useState
useEffect
useContext

Additional Hooks:

useReducer
useCallback
useMemo
useRef
useImperativeHandle
useLayoutEffect
useDebugValue
useDeferredValue
useTransition
useId

Library Hooks:

useSyncExternalStore
useInsertionEffect

- repo link (https://github.com/osama-abdallah/advanced-js-reading-notes/blob/main/README.md)

- Live Link (https://github.com/osama-abdallah/advanced-js-reading-notes/blob/main/27-useState-Hook.md)
