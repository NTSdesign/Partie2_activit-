Cr�ation nouveau dossier de projet :
mkdir mon_projet
cd mon_projet/
git init
Cr�ation nouveau fichier :
touch un_fichier.md
git add un_fichier.md ((indexe le fichier pour le suivre))
git commit ??? � Ajout de mon fichier �
-a = ajoute tous les fichiers pr�sent dans l'index au commit
-am = on � d�j� fait un commit
-m = message
 
git status = voir le statut du projet
git log = voir l'historique des modifications
ls = permet de liste les fichiers
 
cat un_fichier.js = voir le contenu du fichier
vim un_fichier.md = rentrer dans l��diteur de texte
sortir de vim s�lectionn� un emplacement apr�s le dernier caract�re et tapez :x
git checkout SHA = se positionner sur un ancien commit
git checkout master = revenir sur le dernier commit
 
git clone URL = r�cup�rer un clone d'un GIT en ligne
git push origin master = envoi sur GITHUB
git pull origin master = r�cup�re sur GITHUB
 
git branch = permet de voir sur quelle branche on se trouve
git branch ma_branche = cr�ation d'une branche
git checkout ma_branche = se positionne sur la branche choisi
git checkout -b ma_branche = cr�� et se positionne sur la branche choisi
git merge mon_fichier = Fusionne dans la branche sur las-quelle on se trouve la branche demander
git branch -d ma_branche = supprime la  branche
 
git blame mon_fichier = Savoir qui � modifier qu'elle ligne
git show SHA = Voir le contenu exact d'un commot
git stash = mettre de c�t� ses modifications de fa�on temporaire sans faire de commit
git stash pop = reprend ou j'avais fait appel � git stash