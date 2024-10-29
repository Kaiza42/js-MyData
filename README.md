# Ceci sont mes note ma compréhension mes mot je la completerais au fil du temp 

## variable constante <br>
``let `` déclarer une variable <br>
``let exemple ;`` <br>
on peut aussi déclarer une variable comme ceci <br>
``let exemple , exempleDeux , exempleTrois; 

``const`` une constante qu'on ne peut évidament pas changer <br>
``const exemple ;``

``var`` n'est plus utiliser elle seras peut etre présente dans de vieille docu donc instivement remplacer ``var`` par ``let``

## les type <br>

``typeof`` sert a savoir quel type ce que lui demande  <br>
``console.log(typeof true)`` il dira que c'est type boolean

``number`` le type number prends en compte tous ce qui est nombre et decimal <br>
``let number = 56``

``bigInt`` valeur de nombre supérieur a 64bits 

``String`` chaine de caractère <br>
``let exemple = "chaineDeCaractère"``

``boolean`` valeur qui fonctioner par false ou true qui prend 0 ou 1 

``object`` un objet 

``array`` Un tableau de valeurs quelconques

``symbol``  Une donnée unique et non-modifiable

``null`` na ni type ni valeur

``undefined`` Une variable pour laquelle aucune valeur n'a été assignée sera de type

on peut dire que que ``null == undefined`` mais pas que ``null === undefined``

# operator 

``+`` Pour dire ``15 + 15`` sa peut etre des variable des chifre ect peut servir pour des variable <br>
``++`` pour dire +1 

``-`` pour soustraire `` 14 - 14`` <br>
``--`` pour dire -1 

``*`` pour multiplier `` 14 * 14``

``**`` pour utiliser  Puissance 

``/`` pour diviser mais jamais par 0  ``14 / 2``

``%`` modulo permet de trouver le reste d'une division entière entre deux nombres

``<`` est inférieur à <br>
``<=`` est inférieur ou égal à 

``>`` est supérieur à <br>
``>=`` est supérieur ou égale à 
 
``==`` égale 

``===`` strictement égale 

``!=`` inégalité renvoie un boolean verifie si les deux variable sont différente <br>
``!==`` inégalité strict renvoie un boolean verifie si les deux variable sont différente

`` && `` signifie ET 

``||`` signifie OU 

``...``  affectation par décomposition  est une expression JavaScript qui permet d'extraire (unpack en anglais) des données d'un tableau ou d'un objet grâce à une syntaxe dont la forme ressemble à la structure du tableau ou de l'objet.


## les therme important 

``getElementById`` va prendre un ID dans le html pour l'utiliser dans Js 

``document`` https://developer.mozilla.org/fr/docs/Web/API/Document a préciser a comprendre

``length`` la propriété length  est un entier non-signé de 32 bits qui indique le nombre d'éléments présents dans le tableau. Elle est toujours supérieure au plus grand indice du tableau.

``include``permet de déterminer si un tableau contient une valeur et renvoie ``true`` or ``false``

``join()`` permet de rajouter un élement entre d'autre string

``reverse()`` permet d'inverser l'odre de tableau ou différente chaine de caractere

``split()`` permet de divisé une chaine de caractere et en faire une sous-chaine

pour utiliser Split pour enlever TOUT espace il faut taper ``split(' ')`` suivie d'un ``join('')``


``join()`` permet de regrouper 

``parsefloat`` permet de transformer une chaine de caractere en number

``parseInt`` permet de transformer un number en chaine de caractere

``"String()"``

``Sort()`` tri les element d'un tableau et les remet dans l'ordre par default

``slice(1,-1)`` Slice va enlever la lettee selectionner -1 pour prendre la derniere 1 pour la premiere

``replace()`` permet de remplacer une partie de la chaine par autre choses le premiere arguement et ce qu'on cherche et le deuxieme et ce par quoi on le remplace un petit exemple : ``/[^aeiou]/gi`` cette arguement comprends par ``^`` pour dire ``tout sauf`` ensuite ``aeiou`` pour les voyelle donc `` tous sauf les voyelles`` ensuite le ``g`` pour global et le ``i`` pour insensible a la casse <br>
deuxieme argument ``""`` pour remplacer les consonnes par une chaine de caractere vide <br>
 en enlevent le ``^`` sa inverserait le tout et les voyelles serait enlever et non les consonne 

``.repeat(8)``permet de répéter le nombre de fois indiquer dans les parenthèse


``Math.min()``  renvoie le plus petit nombre d'une série de 0 ou plusieurs nombres ou bien NaN si au moins un des arguments fourni n'est pas un nombre ou ne peut pas être converti en nombre.


``Math.max()`` renvoie le plus grand nombre parmi ceux passés en paramètres

``toUpperCase()`` pour tout passer en majuscule

``toLowerCase()``pour tou passer en minuscule

## les alert et console.log
``alert()`` sa fait une popup en haut de l'ecran avec le contenue <br>

``console.log()`` pour verifier un console.log on doit faire inspecter la page et aller dans ``console`` pour verifier le contenue



##  if /else / else if

je comprends par des exemple donc exemple : 

on declare la variable <br>
``let fizzBuzz ;`` <br>
on modifie la varibale pour aussi s'ecrire comme ceci ``let fizzBuzz = 10;`` <br>
 ``fizzBuzz = 10;``

du coup si ma varible => fizz buzz est un modulo de 2 du coup  sa fait une ``alert fizz`` <br> sinon sa reguarde si ma variable est un modulo de 5 du coup sa fait `` alert buzz`` <br>
sinon  sa reguarde avec un ternaire SI  c'est un modulo de 2 et de 5 du coup sa fait ``alert fizzbuzz`` <br>
et si ma varibale ``fizzBuzz`` ne remplie aucun de ses condition du coup sa fait ``alert rien``

 ``if (fizzBuzz % 2 === 0){ `` <br>
`` alert(fizzBuzz + " fizz")`` <br>
``}else if (fizzBuzz % 5 === 0) {`` <br>
  ``  alert(fizzBuzz + " envoie buzz")`` <br>
 ``}else if (fizzBuzz % 2 === 0 && fizzBuzz % 5 !== 0) { `` <br>
``    alert(fizzBuzz + " fizzbuzz")``<br>
``  } else  {`` <br>
    ``   alert(fizzBuzz + " rien") `` <br>
``} ``<br>

## ternaire

un exemple de ternaire 

ici on déclare age <br>
``let age = 1``

apres on comence par une déclaration ``enfant`` pour l'exemple on demande si
 age est plus grand que 17 on pose la question avec ``?`` apres on lui dit de nous 
 le signigifier par alert sinon il 
 passe a la prochaine question qui est séparer par ``:`` la longueur d'un ternaire n'est pas vraiment définie 
 tant qu'on ne definie pas nous meme une fin.

 ``let enfant = (age >= 17) ? alert("adulte") : (age >= 12 ) ? alert("adolescent") :  alert("mineur");``


## boucle while 
chaque execution de boucle est une itération

 ici on déclare la variable index <br>
``let index = 1 ;`` <br>

tant que index est plus petit que 10 alors +1 jusqu'a que index arrive a 10 <br>
pour resumé while => parenthèse pour établir la condition acolade le console.log 
qui fait aparaître chaque boucle et le ``index++`` que donne +1 a index a chaque boucle <br> 
``while  (index <= 10) {`` <br>
``  console.log(index);`` <br>
``  index++;`` <br>
``};`` <br>


## boucle do while
chaque execution de boucle est une itération

déclaration de la variable index 
``let index = 1 ;``

``do`` fait ``console.log(index)`` donc affiche index ensuite fait ``index +1`` <br> 
prendre la condition donc ``while (index < 40)`` pour signifier la condition d'arret de la boucle arriver a 39 <br>
``do{`` <br>
``  console.log(index);`` <br>
``  index++`` <br>
``} while (index < 40 )`` <br>


## boucle for 

la boucle for a 3 expression otpionel la premiere déclaration de la variable ou modification de la variable ou vide <br>
dans ce cas la elle déclare ``let age = 80``  <br> bien séparer chaque expression par ``;`` <br>
la deuxieme expression dit tant que ``age`` est plus grand que 1 alors <br>
troisieme expression ``age--`` => age -1 <br>
dans la boucle for il y a un if / else  et selon les condition il affiche avec des ``console.log``

for (let age = 80; age >= 1 ; age--){

  if (age < 2) {
     console.log("il fait beau");
   }else{
     console.log("pas trop en vrai");
   };
 };


## function 

Pour moi la function établie une exportation de ce qu'il y a, a l'interieur 


pour expliquer function dit que sont nom est ``calcul`` qui contient ``testDeux`` et ``testUn`` <br>
ensuite il fait une alert avec une string ``"test"`` + testDeux et testUn


``function calcul(testDeux, testUn){`` <br>
``  alert("test " +  testDeux , testUn)`` <br>
  
``}`` <br>

``calcul(5 * 5)`` <br>

## switch case 

déclaration de la variable et de sa valeur <br>
``let ageHuit = 15``

switch avec la variable a switch <br>
 cas numero 1 si ``ageHuit`` a 10 alors ``console.log('tes un enfant')`` break pour sortir du switch case <br>
dans notre cas la valeur de ``ageHuit`` est de ``15`` prochain cas  <br>
case 15 notre varibale ``ageHuit`` est de 15 donc elle va afficher ``console.log('tu es un ado')`` et sortir du switch case avec ``break`` <br>
le switch case aurait pu continuer jusqu'a default et finir par ``console.log("tes qui ? ");``
``switch(ageHuit) {``

```js
  case  10 : <br>
    console.log('tes un enfant');
 break ;
  case 15 : 
   console.log('tu es un ado');
   break ;
   case 20 : .+
 console.log('tes un adulte');
   break ;
   case 25 :
     console.log('tes un peut plus qu'un adulte');
    break ;
    default : 
    console.log("tes qui ? ");
  break ;
}
```










  
 
 

































