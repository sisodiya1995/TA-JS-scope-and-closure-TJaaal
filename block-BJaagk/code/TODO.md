1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// 
let percentages = function percentage(marks, total) {
  return (marks * 100) / total;
}

let percentages = (marks ,total) => (marks * 100) / total;
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// function definition
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
function Expression

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
function Expression
```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
function Expression
```js
let percentage = (marks, total) => (marks * 100) / total;
```
function Expression

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
  ```js 
  function percentage(marks, total) {
   return (marks * 100) / total;

  // function definition store the series of steps.
  let percentage = (marks, total) => (marks * 100) / total;

  // function are object in javascript and objects are value that's why we store function in a variable.if we store 
  //   a function in variable called function expression.
}
```js

4. Why is a function call an expression in JavaScript?

// Ans - To execute the function ,we call the function.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Valid
five = add; // Invalid
five = five(10, 11); // Invalid
five = function () {
  return 'Hello';
}; // Valid
```

6. What is the difference between function definition and function call? Explain with an example.
// function percentage(marks, total) {
  return (marks * 100) / total;
} 
//This is the function definition because we use function keyword.
// percentage(); this is function call.

7. What is the similarities between function definition and function call?

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid 
```

9. What is higher order function explain with an example.
   let double = num => num *2;
   let number = [1,3,5,5]
   number.map(double);

  Ans - function either accept callback function as a parameter or return the function are called higher order function.


10. Explain what is callback function. Why you can pass a function inside a function?

ANs - a callback function is a function pass as an arugument to another function. 
