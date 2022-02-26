# ES6 Classes

Classes are scheme for creating objects where in javascript they are bulit on prototypes with some syntax (expressions & declarations) and semantics. The body of the class is where we define class members such as methods and contructors, there are multiple methods that can be used such as prototype and generator, further more the classes is always executed in strict mode.

Classes could be static and could also have a child class inside of them using "extends" keywords.

# Routing

Routing is the response from an applications end point to a clients request, it is defined using methods of the express app object, these methods use callback function/s that are triggered when a request is made to the specified end point. 

A router instance is a complete middleware routing system which is usually referred to as a "mini-app"

Route paths with a request method make up the endpoint and those paths could be strings, string pattern or a regular expression.

Route parameters are what we use to get values in a certain position in the URL and are usually followed with the Route response methods which simply send a response to the client to end the request-response cycle.

# Express Routing

Express routing iss simply a mini application that is just for routing stuff. we usually used it in our work to create front end routs for our Home and About us pages and we do this to make our apps more modular and flexiable. Route middleware (route.use()) is a way to check something for example before a request is processed and the position of this router is very important.

In short we use express.Router() multiple times to define groups of routes. Also we use route middleware to process requests and to validate parameters using .param().

# Writing middlewares & How Node JS middleware Works

Middleware is a function that has access to the request and response object and the next function in the apps request- response cycle. next function means that when this function is invoked it passes the current middleware and executes the next one this is important because when the middleware doesnt pass control to the next one the request would go uncomplete, we use app.use() tp call a middleware function.

## Questions:

1. Name 3 real world use cases where you’d want to change the request with custom middleware.

for Authentication, Authorization and logging to files.

2. True or false: The route handler is middleware?

False

3. In what ways can a middleware function end the process and send data to the browser?

it processes data before server sends a response.

4. At what point in the request lifecycle can you “inject” middleware?

Middleware acts as a border between the request and response it comes in the middle.

5. What can cause express to error with “Request headers sent twice, cannot start a second response”.

its when to requests are sent and you didnt not ensure that the request exits or terminates.