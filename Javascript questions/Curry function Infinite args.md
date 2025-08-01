## Infinite Currying in JavaScript


Create a function to filter comments from bannedWords and return as a array of items

```
function concatenate(...strings) {
  return strings.join(" ");
}

function curry(f) {
  // Code here
}

const curriedConcatenate = curry(concatenate);
//Input: 
console.log(curriedConcatenate("Hello")("world!")("How", "are", "you?")()); 

// Outputs: 
"Hello world! How are you?"
````