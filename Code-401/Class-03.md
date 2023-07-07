# Class-03 Reading Notes

## ES6 Classes

> 1. ***Classes are a template for creating _objects.***
>
>
> 2. ***Can a class declaration be hoisted?***
>In JavaScript, function declarations are hoisted, which means they can be called before they are defined in the code.
However, class declarations are not hoisted in the same way. When a class is defined using the class keyword, the class
itself is not hoisted to the top of its scope. Unlike function declarations, which are moved to the top of their
scope during the hoisting process, class declarations remain in the place where they are defined.
>
> 3. ***How would you describe a constructor and contextual “this” to a non-technical friend?***
>Think of a constructor as a special function that helps create objects of a particular type. It's like a blueprint or
a template that defines how an object should be created and what properties it should have.
Imagine you want to create a bunch of cars. A constructor would be like the set of instructions you follow to build
each car. It specifies the characteristics and behaviors that all cars of that type should have. For example, a car constructor might define properties like color, model, and year. Now, let's talk about the contextual "this." In JavaScript, "this" is a special keyword that refers to the current object being used or accessed. It allows you to access the properties and methods of that specific object. In the car example, let's say you have a method in the constructor called "startEngine." Inside that method, you might need to refer to the specific car that you want to start the engine of. The contextual "this" keyword helps you do that. When you use "this" inside the constructor, it refers to the current car object that is being created or used.
>

## Using Express Routing

> 1. ***Within Express, what does routing refer to?***
> oue path to our server for what we give back in a response from a request from a client.
>
> 2. ***What is the difference between a route path and a route method?***
>The route path is used to determine which route handler or controller should be invoked when a request matches the
specified path. It helps direct incoming requests to the appropriate logic that should be executed to handle that
request.
>When defining routes in a web application, the route method specifies which HTTP method(s) the route should respond to.
For example, a route can be configured to respond to GET requests, POST requests, or multiple HTTP methods. This
ensures that the appropriate logic is executed based on the type of request being made.
> 3. ***When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?***
> the next parameter is commonly used to control the flow of execution and pass control to the next middleware function or
route handler.This is useful when you want to perform some common operations or checks before or after executing
specific route logic. 'next' is passed to your middleware: If next has been passed to your middleware as a parameter, it
means that your middleware function is expected to pass control to the next middleware or route handler in the chain.
However, it's crucial to ensure that next() is called appropriately in your middleware. If you don't call next(),
the application might get stuck at that middleware, and subsequent middleware or route handlers won't be executed.  
>

## Express Routing

> 1. ***What is an Express Router?***
> its like a mini express route without all the functionality of express I like to think of it like a prototype method for
express
>
> 2. ***By what mean do we initialize express.Router() in an express server?***
> its like using app = express() but instead we say router = express.Router().
>
> 3. ***What do we use route middleware for?***
> Route middleware in Express is used to perform operations or execute functions that are specific to a particular route
or group of routes. It allows you to add additional processing or logic to the request-response cycle before the
final route handler is called such as authentication, input validation and etc.
>

## Things I want to know about
