1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percntage = function per(marks,total){
  return (marks * 100) / total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
Function Expression allows us to create an anonymous function which doesn't have any function name which is the main difference between Function Expression and Function Declaration. ... A function expression has to be stored in a variable and can be accessed using variableName

4. Why is a function call an expression in JavaScript?
A function call expression is used to execute a specified function with the provided arguments. If the function being called is overloaded, the compiler will attempt to match the argument types with the function parameter types. If there are no matching function declarations, a compile-time error will be raised.
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer 5 its called the function that returns add a+b;
five = add; // Answer 
// add(a, b) {
//   return a + b;
// }
five = five(10, 11); // Answer 21
five = function () {
  return 'Hello';
}; // Answer
// ƒ (){
// return "hello";
// }
```

6. What is the difference between function definition and function call? Explain with an example.

7. What is the similarities between function definition and function call?

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid
```

9. What is higher order function explain with an example.

10. Explain what is callback function. Why you can pass a function inside a function?
