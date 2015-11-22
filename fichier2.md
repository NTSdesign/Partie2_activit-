Création nouveau dossier de projet :
mkdir mon_projet
cd mon_projet/
git init
Création nouveau fichier :
touch un_fichier.md
git add un_fichier.md ((indexe le fichier pour le suivre))
git commit ??? « Ajout de mon fichier »
-a = ajoute tous les fichiers présent dans l'index au commit
-am = on à déjà fait un commit
-m = message
 
git status = voir le statut du projet
git log = voir l'historique des modifications
ls = permet de liste les fichiers
 
cat un_fichier.js = voir le contenu du fichier
vim un_fichier.md = rentrer dans l’éditeur de texte
sortir de vim sélectionné un emplacement après le dernier caractère et tapez :x
git checkout SHA = se positionner sur un ancien commit
git checkout master = revenir sur le dernier commit
 
git clone URL = récupérer un clone d'un GIT en ligne
git push origin master = envoi sur GITHUB
git pull origin master = récupère sur GITHUB
 
git branch = permet de voir sur quelle branche on se trouve
git branch ma_branche = création d'une branche
git checkout ma_branche = se positionne sur la branche choisi
git checkout -b ma_branche = créé et se positionne sur la branche choisi
git merge mon_fichier = Fusionne dans la branche sur las-quelle on se trouve la branche demander
git branch -d ma_branche = supprime la  branche
 
git blame mon_fichier = Savoir qui à modifier qu'elle ligne
git show SHA = Voir le contenu exact d'un commot
git stash = mettre de côté ses modifications de façon temporaire sans faire de commit
git stash pop = reprend ou j'avais fait appel à git stash