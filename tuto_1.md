# Tutoriel 1

```package

tutorial_asset_exemple=github:sbergeroncp/tutorial_asset_exemple

```

## @showdialog

✅ Apprends à programmer les blocs ``||scene:Scène||`` et ``||game:Jeu||``.

## Étape 1

Ajoute le bloc ``||scene:définir couleur d'arrière-plan||`` (onglet ``||scene:Scène||``) dans le bloc ``||loops:au démarrage||``.

```blocks

scene.setBackgroundColor(0)

```
## Étape 2

Modifie le bloc ``||scene:définir couleur d'arrière-plan||``.

Remplace la couleur d'arrière-plan par noir (⬛), soit la valeur 15.

```blocks

scene.setBackgroundColor(15)

```

## Étape 3

Ajoute le bloc ``||game:splash||`` (onglet ``||scene:Jeu||``) sous le bloc ``||scene:définir couleur d'arrière-plan||``.

Modifie le bloc ``||game:splash||``.

Ajoute le mot **Escapades** dans la case.

```blocks

scene.setBackgroundColor(15)
game.splash("Escapades")

```

## Étape 4

Appuie sur ➕ du bloc ``||game:splash||``.

Ajoute le mot **virtuelles** dans la case.

```blocks

scene.setBackgroundColor(15)
game.splash("Escapades", "virtuelles")

```

## Étape 5

Ajoute le bloc ``||scene:définir image d'arrière-plan||`` (onglet ``||scene:Scène||``) sous le bloc ``||game:splash||``.

🌳🌳🌳

```blocks

scene.setBackgroundColor(15)
game.splash("Escapades", "virtuelles")
scene.setBackgroundImage(tutorial_asset_exemple.forest1)

```

## Étape 6

Ajoute le bloc ``||variables:définir mySprite||`` (onglet ``||sprites:Sprites||``) sous le bloc ``||scene:définir image d'arrière-plan||``.

🚨🚨🚨 Renomme la variable ``||variables:mySprite||`` par ``||variables:perso||``. 🚨🚨🚨

Regarde l'indice au besoin et sélectionne le même personnage.

```blocks

scene.setBackgroundColor(15)
game.splash("Escapades", "virtuelles")
scene.setBackgroundImage(tutorial_asset_exemple.forest1)
let perso = sprites.create(tutorial_asset_exemple.perso, SpriteKind.Player)

```

## Étape 7

Ajoute le bloc ``||controller:déplacer avec les boutons||`` (onglet ``||controller:Contrôleur||``) sous le bloc ``||Sprites:définir perso||``.

🕹️🕹️🕹️

```blocks

scene.setBackgroundColor(15)
game.splash("Escapades", "virtuelles")
scene.setBackgroundImage(tutorial_asset_exemple.forest1)
let perso = sprites.create(tutorial_asset_exemple.perso, SpriteKind.Player)
controller.moveSprite(perso)

```

## Étape 8

Ajoute le bloc ``||scene:camera suit sprite||`` (onglet ``||scene:Scène||``) sous le bloc ``||controller:déplacer avec les boutons||``.

🎥📹📽️

```blocks

scene.setBackgroundColor(15)
game.splash("Escapades", "virtuelles")
scene.setBackgroundImage(tutorial_asset_exemple.forest1)
let perso = sprites.create(tutorial_asset_exemple.perso, SpriteKind.Player)
controller.moveSprite(perso)
scene.cameraFollowSprite(perso)

```

