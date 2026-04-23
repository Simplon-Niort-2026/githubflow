## Pourquoi ne travailles-tu pas uniquement sur `main` ?
Car le principe du git c'est de faire du versionning et de revert les modifications le plus rapidement et facilement possible. Si tout le monde travaille sur le main, les conflits seront nombreux et fréquents, fastidieux à résoudre et il sera compliqué de voir les possibles erreurs inaperues et de les "dé-appliquer"
## Pourquoi éviter de créer une seule branche par personne ?
Une branche par personne ne parle pas du point de vue du projet et ne décrit pas l'action, ce qui est gênant en cas de problèmes sur le projet. Aussi, une branche par nom peut contenir plusieurs responsabilités de code (SRP SOLID) et complexifie la tâche de découpage en sprints.
## Qu'est-ce qu'un workflow ?
Un workflow est une méthode de travail, consistant en un flux limpide et organisé pour atteindre un objectif spécifique.
## Quand créer une branche avec le GitHub Flow ?
Lorsqu'une issue est crée (représentant une user story correcte et conscise), il est nécéssaire un Pull Request (PR) puis une branche de celle-ci.
## Qu'est-ce qu'une _Pull Request_ ?
Une PR est une proposition de fusion (merge) avec le main.
## Qu'est-ce qu'une _Code Review_ ?
Le code review est un élément clé de la méthode agile (mais pas que) :
- Il permet d'éviter le code owning en présentant tout le projet à l'équipe de manière à ce que tout le monde en ait connaissance (il sert aussi éviter le code obscur)
- Il permet de vérifier si le ou les fichier.s/dossier.s envoyé.s afin de prévenir toute erreur (allant d'une coquille/typo, à une clé d'API visible, en passant par une erreur dans le code qui pourrait "casser" le projet et/ou entrer en conflit)
- Il peut aussi aider à trouver des solutions auxquelles nous n'auriont pas pensé.
Le code reviewing se base sur la bieveillance, l'entraide et la recherche en équipe.