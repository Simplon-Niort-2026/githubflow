## Qu'est-ce qu'un workflow ?

C'est une sorte de "recette" qui garantit que tout le monde travaille de la même manière. Il permet de :

- **Structurer la collaboration** entre les développeurs.
    
- **Éviter les conflits** de code (quand deux personnes modifient le même fichier).
    
- **Assurer la qualité** en imposant des étapes de vérification.
    

---

## 2. Quand créer une branche avec le GitHub Flow ?

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