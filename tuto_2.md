# Tutoriel 2

## @showdialog

✅ Apprends à programmer les blocs ``||scene:Scène||`` et ``||sprites:Sprites||``.

## Étape 1

⬇️⬇️⬇️

Ajoute le bloc ``||scene:définir image d'arrière-plan||`` (onglet ``||scene:Scène||``) sous le bloc ``||game:splash||``.

```blocks

scene.setBackgroundColor(15)
game.splash("Castlevania")
scene.setBackgroundImage(tutorial_asset_exemple.chateau1)
```

## Étape 2

Ajoute le bloc ``||scene:afficher long texte||`` (onglet ``||scene:Scène||``) sous le bloc ``||scene:définir image d'arrière-plan||``.

Modifie le bloc ``||scene:afficher long texte||``.

Remplace la valeur par ➡️➡️➡️ : Au début du jeu, vous incarnerez une vilaine chauve-souris.

```blocks

scene.setBackgroundColor(15)
game.splash("Castlevania")
scene.setBackgroundImage(tutorial_asset_exemple.chateau1)
game.showLongText("Au début du jeu, vous incarnerez une vilaine chauve-souris.,", DialogLayout.Bottom)

```

```template
scene.setBackgroundColor(15)
game.splash("Castlevania")
```

```blockconfig.global
scene.setBackgroundColor(15)
game.splash("Castlevania")
scene.setBackgroundImage(tutorial_asset_exemple.chateau1)
game.showLongText("Au début du jeu, vous incarnerez une vilaine chauve-souris.,", DialogLayout.Bottom)

```

```package
tutorial_asset_exemple=github:sbergeroncp/tutorial_asset_exemple
```