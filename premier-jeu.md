# Premier jeu

## Étape 1

Comptez le nombre de fois où quelqu'un clique sur le bouton "A". On
pourra utiliser une variable pour s'en souvenir. Copiez ensuite ce code pour
le bouton "B" (on fera attention à utiliser une autre variable !)

```blocks
let x = 0
let y = 0
input.onButtonPressed(Button.A, function () {
x = x+1
})
input.onButtonPressed(Button.B, function () {
y = y+1
})
```

## Étape 2

On va maintenant s'occuper du compte `àrebours. Pour cela on va aussi
utiliser une variable. Stockez dans une variable le temps de chaque partie,
pour notre jeu il faut mettre 10 secondes.

## Étape 3

Tout est prêt, il ne reste plus qu'à combiner le tout ! On veut qu'à chaque
seconde on diminue le compteur du temps. Pour faire ca, on peut utiliser
le bloc ``||loops:everyInterval()||``. On pensera
à changer le nombre de ms pour que cette action s'exécute chaque seconde.
Rappel : on a 1 seconde = 1000 ms.

```blocks
loops.everyInterval(500, function () {
})
```

## Étape 4

Pour finir, on veut arrêter de compter une fois le temps dépassé (quand la
variable de temps est inférieure à 0).

## Étape 5

Une fois que le jeu est fini, on aimerait bien savoir qui a gagné. Pour cela
affichez les score et le gagnant à la fin de la partie.

## Félicitations !

Il faut fêter la victoire du grand gagnant. Utilisez ... pour écrire votre propre mélodie
et jouez là en même temps que l'annonce des scores pour récompenser le
gagnant.

```blocks
music.play(music.stringPlayable("- - - - - - - - ", 120), music.PlaybackMode.UntilDone)
```