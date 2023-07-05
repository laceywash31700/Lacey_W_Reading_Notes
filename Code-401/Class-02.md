# Class-02 Reading Notes

## An introduction to NodeJS and Express

> 1. ***Explain middleware, answer as though I were a non-technical recruiter.***
> middleware is works a lot like it sounds like its the middle man between a incoming request and an outgoing response in an application.imagine you are running a restaurant and a customer places a order that order needs to go through stages before getting to the kitchen and being served the middleware is like the waiter.
>
> 2. ***Express the most popular node_web framework.***
>
>
> 3. ***Express is “un-opinionated.” What does that mean?***
> web frameworks kinda categorize themselves as opinionated or un-opinionated that means that former is more rigid on how to solve a problem making it more suitable for rapid development at the cost of flexibility. where as the latter is more loosey goosey on how you connect your components and with less restrictions at the cost of 0 hand holding.
>
> 4. ***What is a module and why is modularity useful to us as developers?***
>a module is a self-contained unit of code that encapsulates a specific functionality or set of related functions. It is designed to be reusable and can be easily incorporated into different programs or projects.

Modularity is a concept that promotes the division of a program into separate modules, each focusing on a specific task or feature. It allows developers to break down complex systems into smaller, manageable parts. they are useful because they give organization reusability and collaboration
>
>

## What is NPM?

> 1. ***What version of npm are you running on your machine?***
>9.6.7
>
> 2. ***What command would you type to install a library/package called ‘jshint’ into your node project?***
> 'npm i jshint' in the terminal inside of my project directory.
>

## What is TDD?

> 1. ***Explain why tests are important. Please explain as though I were your non technical elder.***
> So testing your code is important because it makes sure your code does the minimal requirements for development and functions as expected of it.
for example lets say you are cooking pasta right and you are boiling it and want to make sure its done I grew up in a family that would take a string of spaghetti and throw it on the wall if it stuck to the wall the pasta was done that is a a myth of course the only way to know is to taste it but it is sorta like that.
>
> 2. ***What are three expected benefits of testing***

- reduction in defects.
- less effort in the final phases of the project.
- improved technical quality.

> 3. ***Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.***

- not running the test frequently.

- and writing overly trivial test.
>

## CI/CD

> 1. ***What are three benefits of Continuous Integration?***
> Early Detection of Integration Issues: CI allows developers to integrate their code changes frequently and automatically.
> Faster Time to Market: CI streamlines the development workflow by automating the build, test, and deployment processes.
> Increased Collaboration and Team Efficiency: CI encourages collaboration among developers and ensures that the codebase is constantly integrated and validated by automated tests. 
> 2. ***What is the difference between Continuos Delivery and Continuous Deployment?***
> Continuous Delivery ensures that the software is always in a releasable state, the decision to deploy is made manually. On the other hand, Continuous Deployment automates the entire release process, including the decision to deploy, assuming a high level of confidence in the software's quality.
>
> 3. ***Explain how GitHub fits into this process assuming the listener comes from a non-technical background***
>GitHub is a platform where developers store and manage their code. It uses Git for version control, allowing multiple developers to work on the same project. With GitHub's CI/CD integrations, developers can automate the process of building, testing, and deploying their software. When developers make changes to the code, GitHub's CI system automatically checks for issues and ensures stability. It also enables automatic deployment to production environments, making software releases faster and more reliable.
>

## Things I want to know about
