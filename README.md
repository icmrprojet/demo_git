# demo_git
**Liste des commandes pour GITHUB**

<a href="https://fayechartre6.000webhostapp.com/github/" target="_blank">
<img src="https://user-images.githubusercontent.com/32952402/32414664-71da98a2-c22c-11e7-85c0-ff3faed54b68.jpg" width="200"></a>

# Connecter le PC à Github
```
git config --global user.email "emailgithub@gmail"
git config --global user.name "name"
```
# Actualisation du remote d'un fichier

1. Toujours récupérer les sources sur le Remote  :
   - `git clone https://lienFourniParGitHub`
   - `git pull origin master` si le dossier existe et est déjà partagé
   
2. Faire les modifs en local
   - `git status` permet de voir si les fichiers sont prêts
   **si rouge** faire un `git add` 
   **si vert** passer au `git commit`
   
3. Ajouter au paquet : 
   - `git add .` (. pour tous les fichiers sinon nom du fichier)
   
4. Créer la version : 
   - `git commit -m "explication"`
   
5. Pousser en ligne :
   - `git push origine master`
   

# EX : Creation d'un fichier et synchronisation du remote

1. Création du fichier via la console : `touch test.html`
2. `ls` pour lister 
3. `git add .` pour l'ajouter
4. `git commit -m "new file"`
5. `git push origine master` pour l'envoyer sur Github
