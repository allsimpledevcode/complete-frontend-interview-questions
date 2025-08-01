## Infinite Currying in JavaScript


Implement a function to get input and array of funtions and return value.


```
function step1(value, callback) {
  setTimeout(() => {
    const newValue = value + 1;
    callback(newValue)
  });
}

// Multiplication
function step2(value, callback) {
  setTimeout(() => {
    const newValue = value * 10;
    callback(newValue);
  });
}

// TODO Implement the build function
function build(input, functions, callback) {
    // Code here
}

build(5, [step1, step2], (result) => {
  console.log("Expected output", result == 56);
});
```