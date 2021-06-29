# Passing Functions as Props
* What does .map() return?
- Function to take an array.
- Rendering Multiple Components.
* If I want to loop through an array and display each value in JSX, how do I do that in React?
````
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);
````
* Each list item needs a unique identifies>
What is the purpose of a key?
key is a special string attribute you need to include when creating lists of element and help React identify which items have changed, are added, or are removed.
# The Spread Operator
* What is the spread operator?
JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments. ```...arr```
*List 4 things that the spread operator can do.
- Copying an array.
- Concatenating or combining arrays.
- Using Math functions.
- Using an array as arguments.
* Give an example of using the spread operator to combine two arrays.
```
const letter = ['A','B','C','D']
const moreLetter = [...letter];
console.log(moreLetter) 
fruits[0] = 'A'
console.log(...[...letter,'...',...moreLetter])
```
* Give an example of using the spread operator to add a new item to an array.
```
const letter = ['A','B','C','D']
const fewMoreFruit = ['F', 'G', ...letter]
console.log(fewMoreFruit)
```
* Give an example of using the spread operator to combine two objects into one.
```
const letterC = {letterC: "A B C D"}
const letterS = {letters: "a b c d"}

const letter = {...letterC,...letterS}
console.log(letter)

```

