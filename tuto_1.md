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

Remplace la valeur par ➡️➡️➡️ : Castlevania

```blocks

scene.setBackgroundColor(15)
game.splash("Castlevania")

```

```package

tutorial_asset_exemple=github:sbergeroncp/tutorial_asset_exemple

```