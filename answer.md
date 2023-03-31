# Response aux questions
## 1b
### Quelles étapes (steps) sont réalisées par cette action ?
- le checkout sur le repo
- l'installation de python
- les installations des dépendances
- lintage du code
- test avec pytest
### Une étape est définie au minimum par 2 éléments, lesquels sont-ils et à quoi servent-ils ?
le nom et les commandes à exécuter run ou with.
le nom permet de retrouver facilement l'étape dans les logs
le run execute une série de commandes
le with utilise une autre action pour réaliser l'étape
### La première étape contient le mot-clé ‘with’, a quoi sert-il ?
il permet d'utiliser une autre action pour réaliser l'étape de checkout