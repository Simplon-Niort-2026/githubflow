
- ### Pourquoi ne travailles-tu pas uniquement sur `main` ?
Travailler sur main pose plusieurs problèmes potentiels.
Dans le cas de figure où une démonstration doit être faite à un client, si tout se passe sur _main_, le projet ne pourra pas se lancer si il y a une fonctionnalité qui est en cours et qui empêche la compilation.
Une autre possibilité, lorsque plusieurs développeurs travaillent simultanément sur la même branche mais pour des sujets différents. Cela va entrainer systématiquement des conflits qu'il faudra résoudre à chaque fois qu'un _push_ sera réalisé, ce qui ralentit le rythme de travail.
<br/>
- ### Pourquoi éviter de créer une seule branche par personne ?
Une solution potentielle et logique suite aux problèmes soulevés dans la question précédente serait de créer une branch par personne. Chaque branch dépend de main tout en isolant le code produit par chaque développeur. Les pushs ne déclenchent plus de conflit.
Cependant, le problème initial est simplement décalé. Car, à chaque fois qu'il faudra fusionner le code avec _main_, la quantité de conflits à résoudre sera très importante puisque c'est tout ce qui aura été écrit sur la branch personnelle qui devra trouver sa place dans le projet et s'ajuster aux modifications réalisées par les autres développeurs. Les chances de casser le travail des autres sont très élevées.
<br/>
- ### Qu'est-ce qu'un workflow ?
Un workflow est le nom donné à la façon dont les développeurs vont travailler sur Github. Cela permet à tou.te.s les participant.e.s de partager la même méthodologie de travail. Cette méthodologie est propre à chaque projet, à chaque équipe et s'adapte aussi à l'écosystème utilisé pour travailler.
<br/>
- ### Quand créer une branche avec le GitHub Flow ?
Une branch devrait être idéalement créée pour chaque modification à apporter au code, quelle que soit l'importance de la modification. Ca peut être pour corriger un bug, ajouter une fonctionnalité, refactoriser une feature, etc.
<br/>
- ### Qu'est-ce qu'une _Pull Request_ ?
Une _pull request_ c'est une manière à un développeur de signaler à son équipe qu'il a terminé de développer la tâche qui lui était confiée et qu'il considère qu'elle est prête à être fusionnée (_merge_) sur la branch principale. A partir de ce moment-là, le développeur ne touche plus à son code et va attendre les observations de ces collègues sur le travail réalisé. On appelle cela une _code review_.
<br/>
- ### Qu'est-ce qu'une _Code Review_ ?
La revue de code (code review) correspond au travail de développeur de relire le travail réalisé par un de ses collègues. L'objectif est de vérifier que le code fonctionne correctement, qu'il n'y a pas de bugs présents qui n'ont pas été anticipé, que la sécurité du projet est bonne et que les conventions sont bien respectées. De cette façon, plusieurs membres de l'équipe sont au courant des évolutions qui vont intervenir et comment elles ont été conçues.
Au besoin, des retours sont faits pour améliorer ou modifier des éléments lorsque c'est nécessaire.