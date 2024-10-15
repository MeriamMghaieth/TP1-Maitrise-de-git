# TP1-Maitrise-de-git

Partie 1 : Préparaton de l'environnement Git
Q4: git config --global user.name
  git config --global user.email
Q5: git config --global user.email "nv@email.com"

Parte 2: Création d'un nouveau projet
Q6: si j'ai oublier d'ajouter fichier README.md , j'insaire la commande "touch README.md" , apres la commande "git add README.md" pour l'ajouter a l'index , et pour enregistrer l'ajout de fichier : git commit -m "Ajout du fichier README.md"
et finalement on pouche les changements : git push origin <votre-branche>
Q7: on cree un depot distant , on l'ajout a mon projet local avec cette commande "git remote add origin https://github.com/utilisateur/nom-du-depot.git" , et on pousse le cahngement avec :git push -u origin main

Partie 3 : Concepts de base de Git
Q3: pour annuler les modifications local : git checkout -- .
Q4: pour visualiser les fichier : git status

Partie 4 : Collaborer sur Git
Q4: on ajout le depot distant : git remote add origin https://github.com/utilisateur/nom-du-depot.git , on recupêre tt les branches : git fetch origin
 et pour suivre : git checkout --track origin/nom-de-la-branche
Q5: on change la branche : git checkout master et on la supprime : git branch -d nom-de-la-branche




