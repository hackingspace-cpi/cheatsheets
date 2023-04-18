
# JavaScript Cheat Sheet

## Variablen

```javascript
//deklarieren
let foo: String;
//deklarieren und zuweisen
let foo: String = "bar";
//zuweisen
foo = "bar";
```

## Bedingungen

```javascript
if(a >= 2){
    // do stuff
}

if(a <>= 2){
    // do stuff
} else {
    // do different stuff
}

```

## Schleifen

```javascript
while(b != c){
    // do stuff
}
for(let i; i <= x; i++){
    // do stuff
}
for(let i; i < myArray.length; i++){
    let myElement = myArray[i]
}
//rückwärts, falls man Elemente löschen will
for(let i = myArray.length - 1; i >= 0; i--){
    let myElement = myArray[i]
}
```

## Funktionen
```javascript
function(param1: String, param2: Number): String {
    //do stuffs
    return "stuff";
}
```
## Array
```javascript
let arr: Array<String> = ["Test", "Baum"];
let elem0 = arr[0]; // Speichere Element aus Array in Variable
let arr[1] = "Blatt"; // Ersetze Element an Index 1
arr.push("anotherElement"); // Element anhängen
arr.splice(i,1); // Element an stelle i entfernen
```

## Klassen
```javascript
class Table extends Furniture{
    public legCount: Number = 4;
    protected color: String;

    constructor(color: String){
        this.color = color;
    }

    flipTable(direction: String){
        // do stuff
    }
}

let table = new Table("red");
```
## Imports
```javascript
    export class MyClass {};
    export let myVar: Array<String>;
    export function myFunction(){}
```
```javascript
    import { MyClass, myVar, myFunction } from "./path/to/file";
```

## Events
```javascript
document.addEventListener('click', (e)=>{
    // Position des Klicks
    let x = e.offsetX;
    let y = e.offsetY;
})

document.addEventListener('keydown', (e)=>{
    // Code der gedrückten Taste
    let key = e.keyCode;
})
```
## Events
```javascript
document.addEventListener('click', (e)=>{
    // Position des Klicks
    let x = e.offsetX;
    let y = e.offsetY;
})

document.addEventListener('keydown', (e)=>{
    // Code der gedrückten Taste
    let key = e.keyCode;
})
```

