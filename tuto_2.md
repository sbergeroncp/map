# Tutoriel 2

## @showdialog

✅ Apprends à programmer les blocs ``||scene:Scène||`` et ``||game:Jeu||``.

## Étape 1

⬇️⬇️⬇️

Ajoute le bloc ``||scene:définir image d'arrière-plan||`` (onglet ``||scene:Scène||``) sous le bloc ``||game:splash||``.

```blocks

scene.setBackgroundColor(15)
game.splash("Castlevania")
scene.setBackgroundImage(tutorial_asset_exemple.chateau1)
```

## Étape 2

Ajoute le bloc ``||game:afficher long texte||`` (onglet ``||scene:Jeu||``) sous le bloc ``||scene:définir image d'arrière-plan||``.

Modifie le bloc ``||game:afficher long texte||``.

Remplace la valeur par ➡️➡️➡️ : Explorant les catacombes du château de Dracula...

```blocks

scene.setBackgroundColor(15)
game.splash("Castlevania")
scene.setBackgroundImage(tutorial_asset_exemple.chateau1)
game.showLongText("Explorant les catacombes du château de Dracula...,", DialogLayout.Bottom)

```

## Étape 3

Ajoute le bloc ``||game:afficher long texte||`` (onglet ``||scene:Jeu||``) sous le bloc ``||game:afficher long texte||``.

Modifie le bloc ``||game:afficher long texte||``.

Remplace la valeur par ➡️➡️➡️ : Un sort magique vous transforme en chauve-souris...

```blocks

scene.setBackgroundColor(15)
game.splash("Castlevania")
scene.setBackgroundImage(tutorial_asset_exemple.chateau1)
game.showLongText("Explorant les catacombes du château de Dracula...,", DialogLayout.Bottom)
game.showLongText("Un sort magique vous transforme en chauve-souris...,", DialogLayout.Bottom)

```
```blockconfig.global
scene.setBackgroundColor(15)
game.splash("Castlevania")
scene.setBackgroundImage(tutorial_asset_exemple.chateau1)
game.showLongText("Explorant les catacombes du château de Dracula...,", DialogLayout.Bottom)
game.showLongText("Un sort magique vous transforme en chauve-souris...,", DialogLayout.Bottom)

```

```template
scene.setBackgroundColor(15)
game.splash("Castlevania")
```

```package
tutorial_asset_exemple=github:sbergeroncp/tutorial_asset_exemple
```