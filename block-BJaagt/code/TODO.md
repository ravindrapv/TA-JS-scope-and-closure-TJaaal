Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = 'Arya';
}
console.log(useranme); // output is it will throw error username is not defined becuse we didnot call the function
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = 'Arya';
}
console.log(useranme); // output error username is not defined
```
in the above code we are looking for variable named `username` ther is no variable found due to its a block scope `const` is only globale scope so it canrt access the block scope variable const so
it will thogh an error
The above code will throw an error `Reference Error username is not defined`.


3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = 'Arya';
}
console.log(useranme); // output block scope  error username is not defined
```
in the above code we are looking for variable named `username` ther is no variable found due to its a block scope `const` is only globale scope so it canrt access the block scope variable const so
it will thogh an error
The above code will throw an error `Reference Error username is not defined`. 

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = 'Arya';
}
console.log(useranme); // output is Arya
```
`var` can able to access the block scope variable so the out put is Arya

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  var username = 'Arya';
}
console.log(useranme); // output 'username' has already been declared
```
'username' has already been declared `var` can able to access the block scope so user name defined 2 times so its throgh an error 'username' has already been declared

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  let username = 'Arya';
}
console.log(useranme); // output is John 
```
`let` its a global scope so let cant access the inside black scope so 
the output is John 

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
function sayHello() {
  let username = 'Arya';
}
sayHello();
console.log(useranme); // output is john
```
the out put is john let is global scope and function is called but inside the function user name is not console so the out put is `John`

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, 'First'); // output 1 t0 9  First
} 
console.log(i, 'Second'); // output 10 Second
```

9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, 'First'); // output  1 t0 9  First
}
console.log(i, 'Second'); // output error i is not defined
```
the secand one cant access becuse `let` is global scope cant access so i is not defined