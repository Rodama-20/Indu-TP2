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

## 2a
### Sur l’onglet Summary d’une analyse de code, SonarCloud fournit 4 indicateurs. Quels sont-ils et quelles sont leurs utilités ?
- Bugs: permet de détecter les bugs dans le code
- Code Smells: permet de détecter les mauvaises pratiques de code
- Vulnerabilities: permet de détecter les failles de sécurité
- Security Hotspots: permet de détecter les endroits où il y a des risques de failles de sécurité
### À quoi sert l’indicateur Quality Gate ?
a savoir si le nouveau code ajoute des problèmes

## 2b
### Quelle est la différence entre les sections New code et Overall Code dans l’onglet Summary ?
- New code: analyse seulement le nouveau code publié et les problème associés
- Overall code: analyse l'entièreté du code
### Y a-t-il des Code Smells ? Si oui, combien et pour quelle(s) raisons(s) ?
Il y a 3 code smells: 2 pour des paramètres de fonctions non utilisés et 1 pour une fonction dupliquée
### Y a-t-il des Security Hotspots ? Si oui, combien et pour quelle(s)raison(s) ?
Il y a 1 security hotspot, dans le docker python fonctionne en root
