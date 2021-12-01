Vous venez de faire un 'git fetch' et vous vous appercevez qu'un dev a 
modifié exactement le même fichier à la même ligne sur laquelle vous venez 
de travailler.

Cela semble inoffensif, et il n'a pas besoin de polluler l'historique.
Vous ne voulez pas que tout le monde connaisse l'état de votre espace de travail.

Cette fois ci, au lieu d'utiliser stash, vous allez utiliser rebase.

- Commiter vos changements
- Utiliser 'git pull --rebase' pour récupérer la dernière version de origin/master et
appliquer vos changements
- Résoudre le confilt dans first.txt
- Utiliser 'git rebase --continue' pour finir le rebase
- Pousser les modifications.

Pouvez-vous maintenant voir les différences entre stash et rebase ?

