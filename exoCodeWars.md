 ## 7 kyu Reverse words

 function reverseWords(str) {

  return str.split("").reverse().join("").split(" ").reverse().join(" ");
 }

# Boucle inachevée – Correction de bug n°1
```js
 return numbers.join('').replace(/(...)(...)(.*)/, '($1) $2-$3');
 ```

 ```js
function createArray(number){
  var newArray = [];
  
  for(var counter = 1; counter <= number; counter++){
    newArray.push(counter);
  }
  
  return newArray;
}
```
# Le message secret de Jenny
```js
function greet(name){
 
  if(name === "Johnny")
    return "Hello, my love!"; 
  return "Hello, " + name + "!";
}
```

## String Templates - Bug Fixing #5 kyu 8
```js
function buildString(...template){
  return `I like ${template.join(', ')}!`;
}
```

## Basic variable assignmen kyu 8
```js
var a = "code";
var b = "wa.rs";
var name = a + b;
```

## Réparez votre code avant que le jardin ne meure ! kyu 8

```js
function rainAmount(mm){
    if ( mm < 40) {
         return "You need to give your plant " + (40 - mm) + "mm of water"
    } else {
         return "Your plant has had more than enough water for today!"
    }
}
```

## getNames() kyu 7
```js
function getNames(data){
  return data.map(function(item){return item.name});
}
```
## Return Negative
```js

function makeNegative(num) {
  // Code?
 num = -num
  
  return num
}
```

## Array.diff kyu 6 
```js
return a.filter(item => !b.includes(item));
```

## Switch/Case - Bug Fixing #6
```js
function evalObject(value){
  var result = 0;
  switch(value.operation){
    case'+': result = value.a + value.b;
      break;
    case'-': 
      result = value.a - value.b;
            break;
    case'/':
      result = value.a / value.b;
            break;
    case'*': 
      result = value.a * value.b;
            break;
    case'%':
      result = value.a % value.b;
            break;
    case'^': 
      result = Math.pow(value.a, value.b);
            break;
  }
  return result;
}
```

## Basic variable assignmen kyu 8

```js
var a = "code";
var b = "wa.rs";
var name = a + b;
```

## String repeat kyu 8 

```js
function repeatStr (n, s) {
  return s.repeat(n);
  }
```

## Century From Year kyu 8

```js
function century(year) {
  
     return Math.ceil(year/100);
  
}
```

## Is it even? kyu 8
```js
function testEven(n) {
    //Your awesome code here!
  if(n % 2 === 0){
    return true
  }else{
    return false
  }
}
```

## Invert values kyu 8

```js
function invert(array) {
  
  
    return array.map((number) => number * -1);
}
```

# Boucle inachevée – Correction de bug n°1
```js
 return numbers.join('').replace(/(...)(...)(.*)/, '($1) $2-$3');
 ```
