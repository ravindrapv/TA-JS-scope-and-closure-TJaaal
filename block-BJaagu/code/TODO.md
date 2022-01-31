Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT NaN undefined
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT numA is undefinrd
let numA = 21,
  numB = 30;
```
its throw an error `numA` is undefinrd

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //OUTPUT 51
```

Find the output of the code snippets below:

```js
console.log(sayHello()); // OUTPUT  is hello
function sayHello() {
  console.log("Hey");
}
function sayHello() {
  console.log("Hello");
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT is Tyrion
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT  ReferenceError: username is not defined
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT sayHello is not defined
let sayHello = () => {
  console.log(username);
};
```
error

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT  ReferenceError: sayHello is not defined
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```
error

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT  ReferenceError: sayHello is not defined
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```
error

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // OUTPUT  sayHello is not defined
let sayHello = () => {
  console.log(username);
};
```
error

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  var username = "John";
};
sayHello(); // OUTPUT undefined
```
undefined

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // OUTPUT is John
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // OUTPUT  error
```
 ReferenceError: Cannot access 'username' before initialization