Vous venez de faire un 'git fetch' et vous vous appercevez qu'un dev a 
modifié exactement le même fichier à la même ligne sur laquelle vous venez 
de travailler.

Cela semble inoffensif, et il n'a pas besoin de polluler l'historique.
Vous ne voulez pas que tout le monde connaisse l'état de votre espace de travail.

- Utiliser 'git stash' pour "planquer" vos modifications
- Utiliser 'git pull' pour récupérer la derniere version de origin/master
- Utiliser 'git stash apply' pour appliquer vos changements.
- Résoudre le confilt dans first.txt
- Utiliser 'git stash drop' pour vider votre planque
- Commiter

