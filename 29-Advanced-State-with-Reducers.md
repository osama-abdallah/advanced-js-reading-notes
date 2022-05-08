# Advanced State with Reducers

useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

There are two different ways to initialize useReducer state. You may choose either one depending on the use case. The simplest way is to pass the initial state as a second argument.

If you return the same value from a Reducer Hook as the current state, React will bail out without rendering the children or firing effects.

Pass an inline callback and an array of dependencies. useCallback will return a memoized version of the callback that only changes if one of the dependencies has changed. This is useful when passing callbacks to optimized child components that rely on reference equality to prevent unnecessary renders.

While Redux, Recoil, and MobX are usually the best options for managing global state in large React applications, more often than necessary, many React developers jump into these third-party state management libraries when they could have effectively handled their state with Hooks.

When you consider the complexity of getting started with a third-party library like Redux, which is made much easier with Redux Toolkit, and the excessive amount of boilerplate code needed, managing state with React Hooks and the Context API becomes quite an appealing option. There’s no need to install an external package or add a bunch of files and folders to manage global state in our application.

- repo link (https://github.com/osama-abdallah/advanced-js-reading-notes/blob/main/README.md)

- Live Link (https://github.com/osama-abdallah/advanced-js-reading-notes/blob/main/29-Advanced-State-with-Reducers.md)