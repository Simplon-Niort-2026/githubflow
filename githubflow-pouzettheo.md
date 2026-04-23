

- ## 1. Pourquoi ne travailles-tu pas uniquement sur `main` ?

	Cela permet d'être organisé et d'avoir un travail structuré. Mais aussi de ne pas avoir de conflits entre les différents participants au projet. Chaque personne travaille dans son coin sur de petites tâches dans une branche, pour ne pas impacter le travail des autres.


- ## 2. Pourquoi éviter de créer une seule branche par personne ?
	Il vaut mieux créer une branche par fonctionnalité implémentée ou par correction de bug — de petites branches qui seront simples à review et qui ne « casseront pas le code ». Si une personne travaille pendant 2 semaines sur sa propre branche, la review sera extrêmement longue et toute la logique d'agilité est perdue.

## 3. Qu'est-ce qu'un workflow ?

C'est une sorte de "recette" qui garantit que tout le monde travaille de la même manière. Il permet de :

- **Structurer la collaboration** entre les développeurs.
    
- **Éviter les conflits** de code (quand deux personnes modifient le même fichier).
    
- **Assurer la qualité** en imposant des étapes de vérification.
    

---

## 4. Quand créer une branche avec le GitHub Flow ?

Le GitHub Flow est l'un des workflows les plus simples et les plus populaires. Contrairement à d'autres modèles plus complexes (comme GitFlow), il repose sur une règle d'or : la branche `main` (ou `master`) est toujours déployable.

Dans ce cadre, tu dois créer une nouvelle branche (appelée Feature Branch) dans les situations suivantes :

### A. Pour chaque nouvelle fonctionnalité

Dès que tu commences à coder une nouvelle option ou un nouvel outil pour ton application.

- _Exemple :_ `feature/ajout-panier` ou `feature/bouton-contact`.
    

### B. Pour corriger un bug (Hotfix/Bugfix)

Même pour une petite correction, on ne travaille jamais directement sur la branche principale. On crée une branche dédiée pour tester le correctif.

- _Exemple :_ `fix/correction-affichage-prix`.
    

### C. Pour faire une expérimentation

Si tu veux tester une nouvelle bibliothèque ou une refonte graphique sans risquer de casser le projet actuel.

### Le cycle de vie d'une branche dans GitHub Flow :

1. **Création :** On part de `main`.
    
2. **Commits :** On ajoute des changements localement.
    
3. **Pull Request (PR) :** On demande aux collègues de relire le code.
    
4. **Discussion/Correction :** On affine le code selon les retours.
    
5. **Merge :** Une fois validée, on fusionne la branche dans `main`.

## 5. Qu'est-ce qu'une Pull Request ?

- C'est une fonctionnalité qui facilite la collaboration des développeurs. Elle fournit une interface Web pour discuter des changements proposés avant de les intégrer au projet officiel.
- Ce mécanisme qui permet à un développeur de prévenir les membres de son équipe qu'il a terminé une fonctionnalité. Une fois que sa branche de fonctionnalité est prête, le développeur fait une pull request via son compte. Ainsi, toutes les personnes concernées sont informées du fait qu'elles doivent réviser le code et le merger dans la branche principale (main).

## 6. Qu'est-ce qu'une Code Review ?

La revue de code (code review en anglais) est l’examen systématique du code source par une tierce personne.

- Son objectif est de déceler les bugs avant la mise en production, mais aussi d’améliorer la qualité et la sécurité du code. Elle est souvent assimilée à un comité de lecture.
- Son inconvénient, c'est qu'elle peut être perçue par une perte de temps. Cependant, réaliser un code plus stable et plus compréhensible grâce au code review permet à l'inverse de gagner du temps sur du long terme.

6 conseils pour une code review réussie :

- La bienveillance
- Etablir une charte de bonnes pratiques pour automatiser les pratiques de chacun
- Procéder à une "auto-revue" avant de démarrer une relecture
- Privilégier les petites revues
- Expliciter les commits
- Intégrer les revues de code dans le planning




