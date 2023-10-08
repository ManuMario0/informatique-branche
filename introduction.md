```template
//
```

# Informatique (un peu) branchée - introduction

## Étape 1

A l'aide de l'instruction ``||basic:showLeds||`` (montrer LED), dessinez une flèche pointant vers le haut.
```blocks
basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    `)
```

## Étape 2

Modifiez ce que vous avez pour faire en sorte que cette flèche n'aparaisse
que si l'on appuie sur le bouton "A".

```blocks
input.onButtonPressed(Button.A, function () {})
```

## Étape 3

En utilisant l'instruction ``||basic:showArrow()||`` (montrer flèche) et une
boucle adaptée dans ``||loops:for()||`` (répéter 4 fois), faites tourner tourner la flèche sur elle même
5 fois.

```blocks
for (let index = 0; index < 5; index++) {
    basic.showArrow(ArrowNames.North)
}
```

## Étape 4

Comment faire, en modifiant le code le minimum possible pour que la flèche
tourne sans s'arrêter ?

```blocks
while (true) {}
```

## Étape 5

Définir une variable, lui attribuer la valeur 3 puis l'afficher.

```blocks
let x = 0
basic.showNumber(x)
```

## Congrats !

Tu as réussis ! Maintenant tu peux passer à l'exercice [suivant](https://makecode.microbit.org/#tutorial:github:manumario0/informatique-branche/premier-jeu) !
