### 1) Variables
```
let a, variable1, variable2;
let b = 3;
let c = 10;
let d = [];
let client = {
    nom: 'Florentin',
    panier: 0
};
let f = function ( variable1, variable2, ... ) { ... };
var g;
const h;
```
---
### 2) Table
```
let table = [];

let element1 = table.push('element1');
let element2 = table.push('element2');
let element3 = table.push('element3');

console.log(table, table[0], table.lenght);
```
---
### 3) Conditions

#### 3.1) "If" Condition
```
let example1 = 12;
let example2 = 12;

if (example1 == 11) {
    alert('La variable vaut 11');
} else if (example1 == 12) {
    alert('La variable vaut 12');
} else {
    alert('La variable ne vaut pas 11');
}

if (example2 == 20 && example2 == example1) {
    //alert('[condition if ( ... && ... )]');
}

if (example2 == 20 || example2 == example1) {
    //alert('[condition if ( ... || ... )]');
}
```
---
#### 3.2) "Switch" Condition

```
let example1 = 1;

switch (example1) {
    case 0:
        // code à éxécuter si la variable a valeur1
        alert('La variable "example1" vaut 0');
        break;
    case 1:
        // code à éxécuter si la variable a valeur2
        alert('La variable "example1" vaut 1');
        break;
    default:
        // code à éxécuter si la variable n'est égale à aucune des valeurs précédentes
        alert('La variable "example1" ne vaut ni 0 ni 1');
}
```
---
### 4) Functions
```
function functionName(params) {
    ...
}
functionName(params);

function functionName2(params1, params2, params3) {
    ...
}
functionName2(params1, params2, params3);
```
---
### 5) DOM

Dans votre fichier.html :
```
<!DOCTYPE html>
<html lang="en">
<head>...</head>
<body>
    <div class="container">
        <h1>Test avec document.getElement...</h1>
        <p class="test" id="target"></p>
        <p class="target2"></p>
        <p class="target3 test2"></p>
        <p class="target4"></p>
        <p id="target5"></p>
    </div>
    <script src="main.js"></script>
</body>
</html>
```
Dans votre main.js :
```
const text = document.getElementById("target");
text.innerHTML = "Le prix total du panier est de 100 euros";

const text2 = document.querySelector(".container > .cible2")
text2.innerHTML = `"Le prix total du panier est de 150 euros`;

const text3 = document.getElementsByClassName("cible3")[0];
// console.log(text3);
text3.innerHTML = `Le prix total du panier est de 200 euros`;

const text4 = document.getElementsByTagName("p");
// console.log(text4);
```
