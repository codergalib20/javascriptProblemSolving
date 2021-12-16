### javascriptProblemSolving

language : Javascript

// remove duplicate elements from an array
<br>
const array = e => [...new Set(e)];
<br>
console.log(array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]));
