Vous venez d'écrire un programme C++ qui lit sa configuration depuis un fichier
nommé conf.ini. Comme vous ne souhaitez pas ajouter chaque fichier manuellement,
vous avez décidé d'utiliser un .gitignore.

Vous devez créer un fichier .gitignore qui devra :
 - Ignorer tous les fichiers qui terminent par un ~ (fichiers de backups)
 - Ignorer tous les fichiers dans le dossier out sauf conf.ini

En d'autres termes, une fois votre .gitignore configuré, la commande 'git add .'
devra seulement indexé les fichiers suivants :
 - .gitignore
 - main.cpp
 - out/conf.ini

