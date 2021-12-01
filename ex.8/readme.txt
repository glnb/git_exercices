Vous avez travaillé pendant des heures sur une fonctionnalité et avez régulièrement
commité votre travail, donc vous pouvez toujours retourner dans des états précedents.

Maintenant, il est temps de merger cette fonctionnalité dans master.

Vous avez cependant commité vos changements avec le mot-clé "WIP" (Work In Progress)
et vous ne souhaitez pas que cela apparaisse sur origin. Vous allez devoir 
rassembler tous vos commits en un seul.

- Utiliser 'git rebase -i' pour rassembler vos commits "WIP" en un seul,
mais ne les supprimez pas. N'oubliez pas d'ajouter un message compréhensible.
- Utiliser 'git pull' pour merger dans master.

