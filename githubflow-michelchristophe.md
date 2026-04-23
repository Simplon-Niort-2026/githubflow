# GITHUB FLOW



- **Pourquoi ne travailles-tu pas uniquement sur `main` ?**
On ne travaille pas directement sur la branche main pour éviter de casser le code. Si on push une fonctionnalité qui fait bugger l'application, tout le projet est cassé. Cest donc d'une part pour une question de sécurité. Mais pas uniquement. Pour une question de collaboration également. Quand on travailler en équipe, on va travailler sur des branches. Comme cela chacun pourra faire relire son code par ses collaborateurs et si tout est validé, le travaille peut être fusionner sur la branche main.



- **Pourquoi éviter de créer une seule branche par personne ?**
Lorsque l'on travaille en équipe, on va plutôt créer une branche par fonctionnalité. Cela permet de pouvoir travailler à plusieurs sur une même fonctionnalité.




- **Qu'est-ce qu'un workflow ?**
Un workflow est un flux de travail. C'est un ensemble d'activités que l'équipe doit réaliser.




- **Quand créer une branche avec le GitHub Flow ?**
On créé une branche par issue. Donc lorsque l'on veut travailler sur une issue (une tâche), On va créer une branche à partir de cette issue (sur github par exemple) puis récupérer cette branche sur son dépôt local pour travailler dessus.




- **Qu'est-ce qu'une _Pull Request_ ?**
Une pull request est une fonctionnalité facilitant la collaboration des développeurs. C'est une interface Web conviviale pour discuter des changements proposés avant de les intégrer au projet officiel.
les pull requests sont un mécanisme qui permet à un développeur de prévenir les membres de son équipe qu'il a terminé une fonctionnalité. Ainsi, toutes les personnes concernées sont informées du fait qu'elles doivent réviser le code avant qu'il ne soit mergé (fusionné) avec la branch principale.



- **Qu'est-ce qu'une _Code Review_ ?**
Une code review est le fait qu'un ou plusieurs développeurs relisent le code d'un collaborateur lorsque ce dernier a fait une pull request. L'objectif dune review est de pouvoir échanger sur le code. On va pouvoir demander des changements de toutes sortes (nommage, code si on repère un problème ou futur potentiel problème ...). Cela permettra au développeur qui a demander la review de faire les modifications et les faire relire de nouveau. Une fois que tout est validé, il pourra merger avec la branche main.
