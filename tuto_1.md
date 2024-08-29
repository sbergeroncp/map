# Tutoriel 1

## @showdialog

Mon premier jeu !

## Étape 1

Ajoute le bloc ``||variables:définir mySprite||`` (onglet ``||sprites:Sprites||``) dans le bloc ``||loops:au démarrage||``.

Clique sur le carré gris et sélectionne la même image que dans l'indice.

```blocks

let vaisseau = sprites.create(tutorial_asset_exemple.spaceship_1, SpriteKind.Player)

```

```blockconfig.global
let vaisseau = sprites.create(tutorial_asset_exemple.spaceship_1, SpriteKind.Player)
```

```package

tutorial_asset_exemple=github:sbergeroncp/tutorial_asset_exemple

```