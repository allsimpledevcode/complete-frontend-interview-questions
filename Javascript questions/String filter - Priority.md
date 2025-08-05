## String filter - Priority using presentence word


Create a function to filter name from match presentence word 

Example 1:
``` javascript
const names = ["front", "Frontend Development", "frontend developer", "frontend developer tutorial"];
const input = "frontend";

function filterNames(nameLists, word) {
  // code here
}

const result = filterNames(names, input);
console.log(result);

Output:
["Frontend Development", "frontend developer", "frontend developer tutorial"]
```

Example 1:
``` javascript
const names = ["front", "Frontend Development", "frontend developer", "frontend developer tutorial"];
const input = "frontend developer";

function filterNames(nameLists, word) {
  // code here
}
const result = filterNames(names, input);
console.log(result);

Output:
["frontend developer tutorial", "frontend developer"]
```