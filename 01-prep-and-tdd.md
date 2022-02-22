 # Event Loop

 Event Loop is what a model in javascript is based on to code, collect and process events. Simply event loop is an infinte loop which constantly checks If callstack whether its empty or not and if so new functions are added from the event queue. If not, then the current function call is processed this allows to give preference to performance sensitive tasks such as user-input.

 # JS callback functions

 JS callback functions are simply when you send a function as a parameter for another function. Callbacks make sure that a function is not going to run before a task is completed instead will run when its completed instead there for providing us with asynchronous JavaScript code and keeps us in the clear from problems and errors. Callback functions can also be used for event declaration for example to run when a client presses a button.

 # JS Promises

 Promises function is to handle asynchronous operations. They are easy to deal with when referring to multiple asynchronous operations where if callbacks are used it may lead to a callback hell followed by unmanageable code. callback functions were used before promises but they had limitations and created unmanageable code. Also it is never easy to handle multiple callbacks at the same time so in general improves code readability and they are made up of .then() and .catch().

 # JS Async/Await

 Async/Await is the extension of promises, by async allowing you to write promises and checking not to break execution thread and make sure a promise is returned while await is a function that waits for the promise.

 # Test-Driven Development

 Testing is making sure a program does what it is meant to do by receiveing the correct input and generating the correct output with the intended side-effects. testing can be done either manually or automatically or a comnbination of the two.

 Test-driven development is about first deciding what you want your program to do and then formulating a test to check it to0 then start writing the code to make it pass. It is usually considered with automated testing. 

 We usually use jest as it is a testing environment that has everything we could possibly need and we write our tests in the form of functions that recieve a few arguments and we can use describe function to place our test inside of it as it allows us to divid our tests into sections within it.

 Tests could be based on a varity of specifications, such as:

* Create a random number
* The number is an integer.
* The number created is within a specified range.
* The number is unique.

and many more.
