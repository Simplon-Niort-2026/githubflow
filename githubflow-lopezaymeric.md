


## Pourquoi ne travailles-tu pas uniquement sur `main` ?

Implémenter des fonctionnalités sur différentes branches et pas directement sur le main donne trois avantages concrets :

- **`main` reste stable** → toujours déployable, jamais de code cassé
- **Travail en parallèle** → plusieurs devs sur des features différentes sans se marcher dessus
- **Pull requests** → avant de merger, l'équipe peut relire, commenter et valider le travail

---
## Pourquoi éviter de créer une seule branche par personne ?

Le fait de créer une seule branche par personne empêche la collaboration de plusieurs personnes au sein d'une même branche. Le workflow de branche par fonctionnalité permet quant à lui de créer des branches (comme son nom l'indique) par fonctionnalité et donc de travailler et échanger sur des mêmes fonctionnalités.

---
## Qu'est-ce qu'un workflow ?

Un workflow est tout simplement une méthode de travail, comme le workflow de branche de fonctionnalité par exemple. 

---
## Quand créer une branche avec le GitHub Flow ?

On va au préalable créer des issues pour les différentes fonctionnalités qu'on a prévu d'implémenter sur github, puis on créera une branche pour chaque issue. 

---
## Qu'est-ce qu'une _Pull Request_ ?

Lorsqu'un développeur travaillant sur une branche a terminé la fonctionnalité prévu pour celle-ci, il va créer une pull request qui va permettre à ses collaborateurs de faire une review de son travail et de pouvoir echanger à propos de la branche en question.

---
## Qu'est-ce qu'une _Code Review_ ?

Une code review, ou revue de code en français, est réalisée par un ou plusieurs membre(s) tier(s) de l'équipe travaillant sur le projet et a pour objectif de déceler des bugs ou des erreurs dans le code, améliorer la qualité et la sécurité du code en examinant le code source de l'auteur de la pull request.