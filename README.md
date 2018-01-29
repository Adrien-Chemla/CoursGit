# Configuration
## Configurer son nom 
````
git config --global user.name
````

## Configurer son mail 
````
git config --global user.email
````
# Créer un projet Git
## Créer un nouveau repo
```
git init
```

## Ajouter un fichier au suivi Git
````
touch README.md
git add ./README.md
````

# Ignorer un fichier
````
touch fichier-cache.txt
touch toto.js
touch yolo.js
touch .gitignore
````

Ajouter fichier-cache.txt dans le fichier .gitignore :

> **Ignorer un fichier**
> ---
> ./fichier-cache.txt
> ---
> **Ignorer un type de fichier**
> ---
> *.txt
> ---
> **Ignorer un fichier avec une règle**
> ---
> t*.js

## Voir l'état de mon répertoire de travail
````
git status
````

## Connecter le répertoire local avec le répertoire en ligne
````
git remote add origin <url-du-remote>
````

## Envoyer le projet 
````
git push -u origin master
````

# Récuperer un projet
````
git clone <url-du-remote<> <nom du dossier>
````

# Gérer des versions parallèles
## Créer une branche
````
git branch <nom-branche>
git push --set-upstream origin <nom-branche>
````

## Se déplacer sur une branche
````
git checkout ≤nom-branche>
````

<<<<<<< HEAD
## Lister les branches
````
git branch
````

## Créer et se dépalcer sur la branche
````
git checkout -b <nom-branche>
````

## Supprimer une branche
````
git branch -d <nom-branche>
````

=======
**Ignorer un fichier**
./fichier-cache.txt

**Ignorer un type de fichier**
*.txt

**Ignorer un fichier avec une règle**
t*.js

**Je s'appelle groot**
>>>>>>> origin/groot
