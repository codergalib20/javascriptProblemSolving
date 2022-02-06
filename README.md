### javascriptProblemSolving

# language : Javascript

<br><br><br>

## Remove duplicate elements from an array

<br>
```
const array = e => [...new Set(e)];
```
<br>
```
console.log(array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]));
```

<br><br>

### How to work a loop in setTimeOut function

<br>
const a = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
<br>
```
for (let i = 0; i < 10; i++) {
  setTimeout(() => console.log(a[i]), 1000);
}
```
<br><br>
```
for (var i = 0; i < 10; i++) {
  setTimeout(() => console.log(a[i]), 1000);
}
```
<br><br><br>

```
console.log("Line one");
setTimeout(() => {
console.log("Live two");
}, 2000);
console.log("Line three");
```

<br><br><br>

```
function createAlert() {
  alert("This is a alert");
}
createAlert()
```

<br><br><br>

```
function myFunction(name = "Chagol") {
  if(name){
    console.log(`Mr. ${name}`);
  }
}
myFunction("Asadullah Hil Galib");
```

<br><br><br>

```
const myFunction = (name = "No name here") => {
console.log(`Mr. ${name}`);
};
myFunction("Asadullah Hil Galib");
```

<br><br><br>

```
const name = "Asa";
if (name) {
if (name.length >= 10) {
console.log("User provide a big name " + name.length);
} else if (name.length <= 5) {
console.log("User provide a small name " + name.length);
} else {
console.log("User provide a medium name " + name.length);
}
} else {
console.log("User don't Authentication");
}
```

<br><br><br>

```
const name = "Galib";
name ? console.log("User provide her name!") : console.log("user don't provide her name!");
```

<br><br><br>

```
const name = "Asadullah";
const age = "16";
const father = "Lutfor Rahman";
let mother = "Siddaka begum";
let sister = "";
let brother = "Shybul alif sakib";

if (name) {
  console.log(
    `User provide her ${name ? name : ""} ${age ? age : ""} ${
      father ? father : ""
    } ${mother ? mother : ""} ${sister ? mother : ""} ${brother ? brother : ""}`
  );
}
```

<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
<br><br><br>
