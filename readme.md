# SoniQ Services Recruitment Task for Backend Developers

Hello! If you are here then you reached the coding challenge for Backend Developers at SoniQ Services!
This coding challenge should represent a task that is very close to what we are usually working on at SoniQ Services.
You should take no more than 5h to complete this task.

The source code of the solution should be provided as a bunch of files (or via github repo). It is highly recommended to push all the sources to git repository so you will be able to demonstrate also your ability of working with build tools and git itself. Please note that **code quality** is very important to us.

Good luck and we hope you will enjoy the process of solving this task!

## Create a Document Store

The aim of this exercise is to create a small backend service based on AWS tools, providing an API interface to store data within an S3 bucket and to use a trigger mechanism to store informations of the S3 object within a database.

Our focus is on the technical design and structure of this service. And don't worry, if you cannot finish the the whole functionality in the given time, we will just have a look at what you have done so far and you can explain your code to us :-)

Feel free to be creative with the scenario! But just to give you a kickstarter: Our product team requires the ability to upload files and having the possiblity to see some extra metadata according to this uploaded file...

## Technical requirements

1. Use Serverless Framework for deployment of your code and to provision the required infrastructure

2. Use NodeJS as Runtime for your lambda, TypeScript is preferred

3. Prefer asyncronous methods over synchronous

4. Clearly separate your infrastructure declaration from your functions

5. Secure the API

### Bonus (optional)

1. Use GraphQL instead of REST

2. Design an makro service architecture diagram

3. Implement a queue mechanism for asyncronous processing of messages (S3 Object Triggers)

4. Use a bundling tool like Webpack to minimize the size of your build

5. Implement Dependency Injection.

6. Add a query method to ask for the data of the uploaded document
