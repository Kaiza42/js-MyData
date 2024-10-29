# dans celui-ci je ferais des explication de code qui m'interesse 

le replace ``le premier (...) le premier capture les premiers caractere `` <br>
          `` le deuxieme (...) capture les caractère `` <br>
           ``le troisieme (.*) le troisieme prends tout les autre caractere `` <br>

la partie la plus interessante ``le premier ($1) place le premiere grouppe entre parenthèse`` <br>
                               ``le deuxieme $2 place le groupe avec un espace`` <br>
                               ``le troisieme -$3 place le reste avec un tiret ``


# Boucle inachevée – Correction de bug n°1
```js
 return numbers.join('').replace(/(...)(...)(.*)/, '($1) $2-$3');
 ```



```
## Array.diff kyu 6 

j'ai plutot mal compris cette ligne du coup je vais la décomposer élement par élement. <br>


``a.filter``  créer un nouveau tableau qui contient uniquement a qu'on appel ici ``item`` donc : ``a.filter(item)`` <br>
``item =>``c'est une fonction fléché qui sert de ``callBack``la fonction fléché prends chaque élément de a donc item sa donne ``a.filter(item =>)`` <br>
``!b.includes(item)`` c'est la condition qui permet de verifier si aucun élement de ``a`` est présent dans ``b`` donc : ``a.filter(item => !b.includes(item))``

```js
return a.filter(item => !b.includes(item));
```


