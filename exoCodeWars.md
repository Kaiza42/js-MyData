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
  let newArray = [];
  
  for(let counter = 1; counter <= number; counter++){
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
## kyu 8

```js
function whatday(num) { 
switch(num){
    case 1:
    return "Sunday"
    break;
      case 2:
    return "Monday"
    break;
      case 3:
    return "Tuesday"
    break;
      case 4:
    return "Wednesday"
    break;
      case 5:
    return "Thursday"
    break;
      case 6:
    return "Friday"
    break;
      case 7:
    return "Saturday"
    break;
      default :
    return "Wrong, please enter a number between 1 and 7"
    
}
  // put your code here
}

```

## You only need one - Beginner kyu 8 

```js
function check(a, x) {
  // your code here
 return a.includes(x, 0)
}

```
## Incorrect division method kyu 8

```js
const solve = (x, y) => x / y

```
## Remove First and Last Character kyu 8
```js
function removeChar(str){
 //You got this!
return str.slice(1,-1)
};
```

## Square Every Digit kyu 7 

```js
function squareDigits(num){
  //may the code be with you
  let newNum = new Array();
  ('' + num).split('').map(n => {
    newNum.push(n**2);
   })
  
  return parseInt(newNum.join(''));
}
```
## calculate average kyu 8 

```js
function findAverage(array) {
  // your code here
  let somme = 0
   somme = array.reduce((n , array) => n + array,0);
   if (somme, array.length !== 0 ){
     return somme / array.length
   }else  {
     return somme , array = 0
   }
}  
```
## Grasshopper - Summation 

```js
var summation = function (num) {
  // Code here
let result = 0 ; 
for(let somme = 1 ; somme <= num ; somme++){
 result += somme;
    
}
return   result  
  
}
```

## Grasshopper - Grade book kyu 8

```js
function getGrade (s1, s2, s3) {
 let somme = (s1 + s3 + s2) /3
 
   if (somme >= 90){
     return 'A'
   }else if(somme >= 80) {
     return 'B'
   }else if (somme >= 70) {
     return "C" 
   }else if (somme >= 60) {
     return 'D'
   }else{
     return 'F'
   }
}
```

## Grasshopper - Personalized Message kyu 8

```js
function greet (name, owner) {
  // Add code here
  if(owner === name){
    return 'Hello boss'
  }else{
    return 'Hello guest'
  }
}

 ```
## Remove exclamation marks

```js
function removeExclamationMarks(s) {
 
  return s.replace(/[!]/)
}
 ```

## Regex validate PIN code
```js
 function validatePIN(pin) {
  return /^(\d{4}|\d{6})$/.test(pin)
}
 ```

 ## Regex Failure - Bug Fixing #2
```js
 function filterWords(phrase){
  return phrase.replace((/bad|mean|ugly|horrible|hideous/ig),'awesome');
}
 ```

## regex validation of 24 hours time kyu 7 
```js
 function validateTime(time) {
  //regex here.test(time)
```
## regex validation of 24 hours time. kyu 7 
```js
return /^([01]?\d|2[0-3]):[0-5]\d$/.test(time)
  }
```

## validate code with simple regex kyu 8
```js
function validateCode (code) {
//your code here
  return /^[123]/gi.test(code)
}
``` 

## Simple validation of a username with regex kyu 8

```js
function validateUsr(username) {
  const res = /^[abcdefghijklmnopqrstuvwxyz\d_]{4,16}$/.test(username)
  return res  
}
``` 
## Beginner Series #1 School Paperwork

```js
function paperwork(n, m) {
if (n < 0 || m < 0){
   return 0;
}
  return n * m
  
}
``` 

## A bugs trilogy: Episode 1 - "Let Math.Random(); decide your future" kyu 8 
```js
function yourFutureCareer() {
	var career = Math.random();
  
	if (career <= 0.32) {
    return 'FrontEnd Developer';
  } else if (career <= 0.65) {
    return 'BackEnd Developer';
  } else {
    return 'Full-Stack Developer';
  }
}
``` 

## Grasshopper - Débogage de la syntaxe des fonctions
```js
function main (verb, noun){
  return verb + noun
}
```

## FIXME: Replace all dots kyu 8

```js
var replaceDots = function(str) {
  return str.replace((/\./g), '-');
}
``` 

## Fix the Bugs (Syntax) - My First Kata kyu 8

```js
function myFirstKata(a,b) {
if (typeof(a) === 'number' && typeof(b) === 'number') {
return (a % b) + (b % a);
} else {
return false;
}
}
``` 


## 101 Dalmatians - squash the bugs, not the dogs! kyu 8 
```js
function howManyDalmatians(number){
  
  var dogs = ["Hardly any", "More than a handful!", "Woah that's a lot of dogs!", "101 DALMATIANS!!!"];
  
 return  number <= 10 ? dogs[0] : number <= 50 ? dogs[1] : number == 101 ? dogs[3] : dogs[2]
}
``` 
## Failed Filter - Bug Fixing #3
```js 
var FilterNumbers = function(str) {
   return str.split('').filter(yes => yes.match(/[a-zA-Z]/g)).join('');
}
``` 
## Keep Hydrated! kyu 8

```js 
function litres(time) {
return Math.floor(time * 0.5);

}
``` 
## Beginner Series #2 Clock kyu 8 

```js 
function past(h, m, s){
  //#Happy Coding! ^_^
  return (h * 60 *60 *1000) + (m* 60 *1000) + (s *1000)
}
``` 
## Count the Monkeys! kyu 8

```js 
function monkeyCount(n) {
// your code here
  let tableau = []
  for( let count = 1 ; count <= n ; count++){
    tableau.push(count)
   
  }
  return tableau
}
``` 
## Sauterelle - Vérification du facteur kyu 8 

```js 
function checkForFactor (base, factor) {
  // code here
  if (base % factor === 0){
    return true
  }else{
    return false
  }
}
```

## Sum The Strings
```js 
function sumStr(a,b) {
if (a === '') a = '0'
  if (b === '') b = '0'
return `${parseInt(a) + parseInt(b)}`
}
```
## Reverse list
```js 
function reverseList(arr) {
  return arr.reverse()
}
```
## Switch it Up!
```js 
function switchItUp(number){
//Write your own Code!
  switch(number){
      case 1 :
      return "One"
      break;
       case 2 :
      return "Two"
      break;
       case 3 :
      return "Three"
      break;
        case 4 :
      return "Four"
      break;
       case 5 :
      return "Five"
      break;
       case 6 :
      return "Six"
      break;
      case 7 :
      return "Seven"
      break;
      case 8 :
      return "Eight"
      break;
       case 9 :
      return "Nine"
      break;
      default : 
      return "Zero"
  }
}
```

## Removing Elements

```js 
function removeEveryOther(arr){
  //your code here
  return arr.filter((envieDeDeceder, abbattezMoi) => abbattezMoi % 2 === 0 )
}
```
## Grasshopper - Debug sayHello

```js 
function sayHello(killMePlease) {
  return 'Hello, ' + killMePlease
}
```
## Grasshopper - Combine strings kyu 8 

```js 
// Create the combineNames function here
let combineNames = (... name) => name.join(' ')
```
##  Reversing Words in a String
```js 
function reverse(string){
  //your code here
  return string.split(' ').reverse().join(' ')
}
```

## String cleaning kyu 8
```js 
function stringClean(s){
  // Function will return the cleaned string
  return s.replace(/\d/g,'')
}
```

## Chuck Norris VII - True or False? (Beginner)

```js 
function ifChuckSaysSo(){
return !true
}
```

## Drink about kyu 8 

```js 
function peopleWithAgeDrink(old) {
  if (old < 14){
    return 'drink toddy'
  }else if (old < 18){
    return 'drink coke'
  }else if (old < 21){
    return 'drink beer'
  }else{
  return  'drink whisky'
  }
  
};
```

## Fundamentals: Retur kyu 8 

```js 
function add(a,b){
    return a + b 
}

function divide(a,b){
    return a / b 
}

function multiply(a,b){
    return a* b
}

function mod(a,b){
    return a % b 
}
   
function exponent(a,b){
    return a ** b 
}
    
function subt(a,b){
    return a -b 
}
```
## Rock Paper Scissors! kyu 8

```js
const rps = (p1, p2) => {
  if(p1 === 'rock' && p2 === 'scissors'){
    return "Player 1 won!"
  }else if (p1 === 'paper' && p2 === 'rock'){
    return "Player 1 won!"
  }else if (p1 === 'scissors' && p2 === 'paper'){
   return "Player 1 won!"
  }else if (p1 === p2){
    return 'Draw!'
  } else{
 
     return "Player 2 won!"
  }
};
```

## Return the day

```js
function whatday(num) { 

  // put your code here
if( num == 1){
  return "Sunday"
}else if(num == 2){
  return "Monday"
}else if(num == 3) {
  return "Tuesday"
}else if (num == 4){
  return "Wednesday"
}else if (num == 5){
  return "Thursday"
}else if (num == 6){
  return "Friday"
}else if (num == 7){
  return "Saturday"
}else{
  return "Wrong, please enter a number between 1 and 7"

}
}
```
## If you can't sleep, just count sheep!! kyu 8 

```js
var countSheep = function (num){
  //your code here
  
  let result = ''
  for(let i = 1 ; i <= num ; i++){
     result += i.toString() + " sheep..."
    
  }
   return result
    
}
```
## Grasshopper - Fonction buts Messi kyu 8

```js
function goals (laLigaGoals, copaDelReyGoals, championsLeagueGoals) {
  return laLigaGoals + copaDelReyGoals + championsLeagueGoals;
}
```
## Grasshopper - Fixateur de fonctions de base kyu 8
```js
function addFive(num) {
  var total = num + 5
  return total
}
```

## Grasshopper - Fonction de combat du jeu terminal kyu 8

```js
function combat(health, damage) {
  // Write your code here
  if ( health < damage){
    return 0
  }else {
    return health - damage 
  }
}
```
## Keep up the hoop kyu 8

```js
function hoopCount (n) {
   //your code goes here   
  if ( n >= 10 ){
    return "Great, now move on to tricks"
  }else {
    return "Keep at it until you get it"
  }
}
```
## Reverse List Order kyu 8 

```js
function reverseList(list) {
return list.reverse()
}
```
## Vowel remover kyu 8 

```js
function shortcut (string) {
  return string.replace((/[aeiou]/gi), '')
}
```
## Welcome to the City

```js
function sayHello( name, city, state ) {
  name = name.join(' ')


  return 'Hello, ' + name + '! Welcome to ' + city + ', ' + state + '!'
}
```

## Remove the time kyu 8

```js
function shortenToDate(longDate) {
  // your code here
  
  return longDate.split(' ').slice(0,-1).join(' ').replace((/,/), '')
}
```