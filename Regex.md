# ici je vais mettre des regex avec leur itilité au fil du temp

## askip celui ci laise uniquement les lettre de A a Z 
```js
/[^a-zA-Z ]/

```
## celui ci laisse lettre et chiffre

```js
/[^a-zA-Z0-9 ]/
```

## celui ci retire les caractere spécial 
```js
/[!@#$%^&*]/
```

## ce regex dit qu'il garde uniquement les voyelle 
```js
/[^aeiou]/
```

## celui ci c'est une version de code pin de 4 ou 6 chiffre
```js
/^(\d{4}|\d{6})$/
```

## Celui ci permet d'enlerver n'importe quel mot choisie 
```js
/bad|mean|ugly|horrible|hideous/
```
## celui ci fait un orloge de 0h     a 00h 
```js
/^([01]?\d|2[0-3]):[0-5]\d$/
```