# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax

```javascript
const functionName = (params) => {
  // code to be executed
}
```

- **const**: const should be used whenever a function expression is assigned to a variable.
- **The function name**: The name you choose for the function.
- **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
- **The arrow syntax**: Indicates that this will be a function.
- **The body**: The statements that make up the function itself. Surrounded by curly braces.

_Example_:

```javascript
const greet = (name) => {
  console.log('Hello, ' + name + '!')
}
```

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ).

## 2. Calling a function

To execute the function, you _ *call* _ or _ *invoke* _ it by using its name followed by parentheses.

**Example**:

`greet('Alice');` // Outputs: Hello, Alice!

## 3. Return values

Functions can process data input and output a value using the _return_ keyword.

**_Example_**:

```javascript
const addNums = (numA, numB) => {
_return_ numA + numB
}
```

```javascript
const total = addNums(2, 4)

console.log(total) // Expected value: 6
```

For more information on functions and how they are used in JS, check out the [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

![pic](https://images.unsplash.com/photo-1721332154373-17e78d19b4a4?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDF8MHxmZWF0dXJlZC1waG90b3MtZmVlZHwxfHx8ZW58MHx8fHx8)
