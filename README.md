### javascriptProblemSolving

# language : Javascript

<br><br><br>

## Remove duplicate elements from an array

<br>
const array = e => [...new Set(e)];
<br>
console.log(array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]));

<br><br>

### How to work a loop in setTimeOut function

<br>
const a = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
<br>
for (let i = 0; i < 10; i++) {
  <br>
  setTimeout(() => console.log(a[i]), 1000);
  <br>
}
<br><br>
for (var i = 0; i < 10; i++) {
  <br>
  setTimeout(() => console.log(a[i]), 1000);
  <br>
}

<br><br><br>
