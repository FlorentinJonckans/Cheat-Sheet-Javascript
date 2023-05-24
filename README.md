# Cheat-Sheet-Javascript
---
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
let f = function ( variable1, variable2, ... ) { ... }
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
