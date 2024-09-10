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

Remplace la valeur par ➡️➡️➡️ : En l'an 1572, un chasseur de vampires se lance à l'assaut du château de Dracula..

```blocks

scene.setBackgroundColor(15)
game.splash("Castlevania")
scene.setBackgroundImage(tutorial_asset_exemple.chateau1)
game.showLongText("En l'an 1572, un chasseur de vampires se lance à l'assaut du château de Dracula..,", DialogLayout.Bottom)

```

```template
scene.setBackgroundColor(15)
game.splash("Castlevania")
```

```package
tutorial_asset_exemple=github:sbergeroncp/tutorial_asset_exemple
```