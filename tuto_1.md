# Tutoriel 1

## @showdialog

✅ Apprends à programmer les blocs ``||scene:Scène||`` et ``||game:Jeu||``.

## Étape 1

Ajoute le bloc ``||scene:définir couleur d'arrière-plan||`` (onglet ``||scene:Scène||``) dans le bloc ``||loops:au démarrage||``.

```blocks

scene.setBackgroundColor(0)

```
## Étape 2

Modifie le bloc ``||scene:définir couleur d'arrière-plan||``.

Remplace la valeur par ➡️➡️➡️ : ⬛

```blocks

scene.setBackgroundColor(15)

```

## Étape 3

Ajoute le bloc ``||game:splash||`` (onglet ``||scene:Jeu||``) sous le bloc ``||scene:définir couleur d'arrière-plan||``.

Modifie le bloc ``||game:splash||``.

Remplace la valeur par ➡️➡️➡️ : **Escapades**.

```blocks

scene.setBackgroundColor(15)
game.splash("Escapades")

```

## Étape 4

Appuie sur ➕ du bloc ``||game:splash||``.

Ajoute la valeur ➡️➡️➡️ : **virtuelles** dans la case de droite.

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
scene.setBackgroundImage(tutorial_asset_exemple.forest)

```

## Étape 6

Ajoute le bloc ``||variables:définir mySprite||`` (onglet ``||sprites:Sprites||``) sous le bloc ``||scene:définir image d'arrière-plan||``.

Renomme la valeur ``||variables:mySprite||`` par ``||variables:perso||``.

Clique sur le carré gris et sélectionne un personnage.

Regarde l'indice au besoin.

```blocks

scene.setBackgroundColor(15)
game.splash("Escapades", "virtuelles")
scene.setBackgroundImage(tutorial_asset_exemple.forest)
let perso = sprites.create(tutorial_asset_exemple.perso, SpriteKind.Player)

```

```package

tutorial_asset_exemple=github:sbergeroncp/tutorial_asset_exemple

```