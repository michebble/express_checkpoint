# Node/Express Test

### Question 1

What is `module.exports` and why do we use it?

```text
'module.exports' is a line of code that points to an object that references functions and variable defined in the code above it. The file containing the code can be required in another file, so that those functions and variables can be called in the other file. 

This helps seperate code, which can make it more readable, maintainable, and can prevent unintended modifications.

```

### Question 2

Write one Express route for each of the four CRUD actions.

Then, make each route respond with a one-word string containing the RESTful action that would most likely be associated with this route.

```js
var express = require("express")
var app = express()

// Your code starts here...

```

### Question 3

Describe the differences between Express and Rails as backend frameworks.

```text
Your answer...
```

### Question 4

What do the following lines of code do?

```js
var bodyParser = require("body-parser")
app.use(bodyParser.json())
app.use(bodyParser.urlencoded({extended: true}))
```

```text
Your answer...
```

### Question 5

For this exercise you will be creating an es6 BankAccount class.

It will have the following properties...
* `type` (e.g., "checking"), which should be determined by some input
* `balance`, which should start out as `0`

It should have the following methods...
* `withdraw`, which should decrease the balance by some input
* `deposit`, which should increase the balance by some input
* `showBalance`, which should print the balance in the bank to the console.

The `BankAccount` class has a `transactionHistory` property which keeps track of the withdrawals and deposits made to the account.
* Make sure to indicate whether the transaction increased or decreased the amount of money in the bank.

```text
Your answer...
```

Create an instance of the BankAccount class

```text
Your answer...
```
