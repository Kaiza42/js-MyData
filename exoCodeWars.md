 ## 7 kyu Reverse words

 function reverseWords(str) {

  return str.split("").reverse().join("").split(" ").reverse().join(" ");
 }

# Create Phone Number kyu 6

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


## Grasshopper - If/else syntax debug 8 kyu 

```js
function checkAlive (health) {
  if (health > 0) {
    return true
  } else {
    return false
  }
}
 ```
## Opposites Attract
```js
 function lovefunc(flower1,flower2){
				if (flower1 % 2 == 0 && flower2 % 2 !==0) {
					return true;
				}else if(flower1 % 2 !==0 && flower2 % 2==0){
					return true;
				}else return false;
			}
```
## Multiply the number kyu 8

```js
function multiply(number){
  //your code 
 return number * Math.pow(5, number.toString().replace('-','').length)
}
```
## Get the Middle Character

```js
function getMiddle(s)
{
  return s.slice((s.length-1)/2, s.length/2+1);
}
```

## Get Planet Name By ID

```js
function getPlanetName(id){
  var name;
  switch(id){
    case 1:
      name = 'Mercury'
      break;
    case 2:
      name = 'Venus'
      break;
    case 3:
      name = 'Earth'
      break;
    case 4:
      name = 'Mars'
      break;
    case 5:
      name = 'Jupiter'
      break;
    case 6:
      name = 'Saturn'
      break;
    case 7:
      name = 'Uranus'
      break;
    case 8:
      name = 'Neptune'
  }
  
  return name;
}

```

## Capitalization and Mutability

```js
function capitalizeWord(word) {
 
  return word.charAt(0).toUpperCase() + word.slice(1);
}
```

```js
## Square(n) Sum kyu 8

function squareSum(numbers){
  
return numbers
  .map(n => n * n )
  .reduce((total,n)=> {
  return total +n;},0)
  
}
```