# Front-end assignment

## Intro

We will discuss this assignment with you during the next interview.

We realize that you may have questions about the requirements, please make a note of any assumptions along with instructions in a readme file submitted with your solution. You should be ready to explain any assumptions and technical choices you have made.

There is no stated time limit but 4-8 hours is expected.

The important thing is to arrive at a solution that you are satisfied with and comfortable discussing with others. The code should be representative of what you would produce at work. Keep clarity, testability, maintainability and efficiency in mind. It must be easy to scan the code, and quickly understand what it’s doing.

The solution should be written in Javascript and/or Typescript. You are free to pick any framework and tool-chain you like (or no framework). Try to use something you are familiar with so that you can spend most of your time on implementing the use-cases.

We realize some corners will have to be cut in order to not spend too much time on this assigment. Please make a note of things you decide not to implement but think would be beneficial.

## Premise

The goal is to build a browser-based client for the existing warehouse API. The API is available in the directory warehouse-api, see README.md for more details.

Your solution should implement the acceptance criterias. We do not expect you to submit a fully functioning warehouse. There are no acceptance criteria on the GUI and UX design, but they will be discussed in the interview, so you should be able to motivate your decisions. After meeting the acceptance criteria, you are free to add features or make improvements as you see fit.

Your solution should be usable in recent versions of Chrome, Safari and Firefox.

## Story 1

As a warehouse employee I want to be able to list available products, their quantities and the articles in each product.

### Acceptance criteria

The client should have a view listing all products, for each product showing the name and quantity in stock
For each product, the client should have a view showing what articles make up the product


## Story 2

As a warehouse employee I want to be able to manage sales of the products in store.

### Acceptance criteria

The client should allow registering sales for one or more products
When a sale is registered, the quantity in stock should be updated accordingly

