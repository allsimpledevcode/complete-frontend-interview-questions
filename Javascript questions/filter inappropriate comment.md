## Filter inappropriate comment


Create a function to filter comments from bannedWords and return as a array of items

```
const comments = ["Very useful tutorial, thank you so much!", "React is not a damn framework, it's a LIBRARY",
  "Why you put bloody kitten pictures in a tech tutorial is beyond me!", "Which one is better, React or Angular?", 'There is no "better", it depends on your use case, DAMN YOU'];
const bannedWords = ['bloody', 'damn'];

Input:
const result = filterComments(comments, bannedWords);
console.log(result);

Output:
[
  "Very useful tutorial, thank you so much!",
  "Which one is better, React or Angular?"
]

````