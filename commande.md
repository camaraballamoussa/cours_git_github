# Les commandes
## Initialisation du projet
cette commande est obligatoire pour commencer un projet avec  git, elle permet d'initialiser le projet avec les depandances de git (Création d'un dossier caché)
```
git init
``` 

## Liaison de git à github

```
git config --global user.name "username"
git config --global user.email "email"
```


## La pré sauvegarde
Permet d'ajouter le fichier à la pré sauvegarde
```
git add "fichier"
``` 
Permet de voir l'etat des fichiers
```
git status
``` 
retirer un fichier de la pré sauvegarde
```
git rm --cached "fichier"
```
## Retour en arrière
permet d'annuler les changements
```
git checkout -- . 
```
## La sauvegarde
Permet de valider la pré sauvegarde
```
git commit -m "message"
```

## Les branches
### Création d'une branche
```
git branch "nom_branch"
``` 
Changer de branches
``` 
git checkout "nom_branch"
```
fusionner des branches
```
git merge "autre_branch"
```

## Commande pour la liaso
```
Liaison entre votre repertoire local et celui du web
git remote add origin "adresse_repo"
```
Permet d'ajouter tous les fichiers sauvergarder dans votre repo
```
git push -u origin master
```