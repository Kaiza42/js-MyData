# dans celui-ci je ferais des explication de code qui m'interesse 

le replace ``le premier (...) le premier capture les premiers caractere `` <br>
          `` le deuxieme (...) capture les caractère `` <br>
           ``le troisieme (.*) le troisieme prends tout les autre caractere `` <br>

la partie la plus interessante ``le premier ($1) place le premiere grouppe entre parenthèse`` <br>
                               ``le deuxieme $2 place le groupe avec un espace`` <br>
                               ``le troisieme $3 place le reste avec un tiret ``



`` return numbers.join('').replace(/(...)(...)(.*)/, '($1) $2-$3');``
