# Tutoriel 2

## @showdialog

Let's go !

## Étape 1

Ajoute le bloc ``||scene:définir image d'arrière-plan||`` (onglet ``||scene:Scène||``) sous le bloc ``||variables:définir mySprite||``.

```blocks
let vaisseau = sprites.create(tutorial_asset_exemple.spaceship_1, SpriteKind.Player)
scene.setBackgroundImage(tutorial_asset_exemple.background1)
```

```blockconfig.global
let vaisseau = sprites.create(tutorial_asset_exemple.spaceship_1, SpriteKind.Player)
scene.setBackgroundImage(tutorial_asset_exemple.background1)
```

```template
let vaisseau = sprites.create(tutorial_asset_exemple.spaceship_1, SpriteKind.Player)
```

```package
tutorial_asset_exemple=github:sbergeroncp/tutorial_asset_exemple
```