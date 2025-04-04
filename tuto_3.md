# title Escapades virtuelles
# description Apprends à utiliser les blocs de la scène et du jeu pour créer une introduction immersive.
# author TonNom
# board arcade
# package tutorial_asset_exemple=github:sbergeroncp/tutorial_asset_exemple

## @showdialog
✅ Apprends à programmer les blocs ``||scene:Scène||`` et ``||game:Jeu||``.

---

## Étape 1 : Définir la couleur de fond

Ajoute le bloc ``||scene:définir couleur d'arrière-plan||`` dans le bloc ``||loops:au démarrage||`` (onglet ``Scène``).

```blocks
scene.setBackgroundColor(0)
