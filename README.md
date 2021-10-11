# Mon premier titre : Le nom de mon application
## Premier sous-titre
### sous sous-titre

+ premier element liste a puce
+ deuxieme element

1. premier element
2. deuxieme element

**texte en gras**

*texte en italique*

---


``` Java
int a = 12;

"Bloc de code"

```
```HTML
<h1>Titre<h1>
```

|Tableau|nom|prenom|age|
|---|---|---|---|
|   |Lamarcq|Olivier|36|

[Aller vers Google]("http://google.com")

[^1]: Note en bas de page

![Mon image](https://media.istockphoto.com/photos/tidal-swirl-at-saltstraumen-maelstrom-in-northern-norway-picture-id1328519923?s=612x612)

## creer un repository local
git init

## suivre un fichier a enregistrer
git add *

## enregistrer l'etat des fichiers
git commit -m "message"

## pousser les modifications en repo distant
git push

## voir l'état actuel des modifications
git status

## recupere l'état actuel du repo distant
git pull

## connexion au repo distant
git remote add origin "origine"
git remote remove origin

## voir les derniers commit
git log

## revenir a un commit precedent
git reset -hard "ash_du_commit"

## annuler le suivi d'un fichier
git rm --cached "nom_fichier"