1. Implement `forEach` array method using Array.reduce

- `forEach` accepts two parameter array and callback
- It does not return anything
- It should work exactly like array `forEach` method

```js
function forEach(array, callback) {
  for(let element of array) {
    callback(element);
  }
}

forEach(['Sam', 'Jon', 'Arya'], (name, i, arr) =>
  console.log(name + name, i, arr)
);

```

2. Implement `map` array method using Array.reduce

- `map` accepts two parameter array and callback
- It returns same size of array
- It should work exactly like array `map` method

```js
function map(arr , callback) {
let final = [];
for(let ele of arr) {
  final.push(callback(ele));
}
return final;
}

map(['Sam', 'Jon', 'Arya'], (name) => name + name); // ['SamSam', 'JonJon', 'AryaArya']
```

3. Implement `filter` array method using Array.reduce

- `filter` accepts two parameter array and callback
- It returns same size or smaller array
- It should work exactly like array `filter` method

```js
function filter(arr , callback) {
  // Your code goes here
}
filter(['Sam', 'Jon', 'Arya'], (name) =>
  name.startsWith('S')
); // ['Sam']
```
