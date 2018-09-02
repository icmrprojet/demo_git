# demo_git
##Recap pour démarrer

#Connecter le PC à Github
```
git config --global user.email "emailgithub@gmail"
git config --global user.name "name"
```
#Actualisation du remote d'un fichier
```
1. Toujours récupérer les sources sur le Remote  :**git clone** lienFourniParGitHub 
2. Faire les modifs en local
**git status** permet de voir si les fichiers sont prêts
3. Ajouter au paquet : **git add .** (pour tous les fichiers)
4. Créer la version : **git commit -m "explication"
**git status** permet de vérifier si les fichiers sont tous au vert
5. Pousser en ligne : **git push origine master**
```