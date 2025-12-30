---
marp: true
theme: default
paginate: true
backgroundColor: #ffffff
---



# Gestion des conflits  
## dans Git & GitHub

Mini-veille – Atelier pratique

<br>

**Présentée par : Salma Akajou**  
**Encadrée par : M. Fouad Essarraj**

---

## Introduction

Dans un projet collaboratif, plusieurs développeurs travaillent sur les mêmes fichiers.

Cela peut provoquer des conflits lors de la fusion du code.

Cette veille présente :
- les conflits Git
- leurs causes
- les règles pour les éviter
- le principe de leur résolution


---

## Qu’est-ce qu’un conflit Git ?

Un conflit Git apparaît lorsque **Git ne peut pas fusionner automatiquement** plusieurs modifications concurrentes.

➡ Git détecte une ambiguïté  
➡ Il bloque la fusion  
➡ Il demande une intervention humaine

📌 Situation normale en travail collaboratif

---

## Dans quels cas apparaissent les conflits ?

- Fusion de branches (`merge`)
- Mise à jour du projet (`pull`)
- Pull Request sur GitHub

📍 Le conflit apparaît quand Git ne peut pas décider quelle version garder.

---

## Causes principales des conflits Git

- Modification de la **même zone de code**

- Absence de mise à jour avant de coder
- Mauvaise organisation des branches
- Faible communication entre développeurs

---

## Types de conflits Git

### Conflit de contenu
Même fichier, même portion de code modifiée

### Conflit suppression / modification
Un fichier supprimé et modifié en parallèle

### Conflit de renommage
Renommage différent d’un même fichier

---

## Comment Git signale un conflit ?

Git affiche un message de conflit lors de l’opération.

Dans le fichier concerné, Git insère :
- la version locale
- la version distante
- des marqueurs de conflit

📌 Git ne modifie jamais le code sans validation humaine.

---

## Principe général de résolution

La résolution consiste à :

- Identifier les versions en conflit
- Analyser l’intention de chaque modification
- Choisir ou combiner les solutions
- Valider la résolution par un commit

➡ La décision reste toujours humaine.

---

## Règles pour éviter les conflits Git

- Synchroniser la branche régulièrement
- Travailler avec des branches fonctionnelles
- Faire des commits clairs et fréquents
- Limiter les modifications sur les fichiers critiques
- Communiquer avant les changements importants

---

## Gestion des conflits sur GitHub

GitHub détecte les conflits lors des Pull Requests.

Avantages :
- Blocage automatique du merge
- Visualisation des conflits
- Résolution sécurisée
- Revue de code intégrée

---
## Atelier pratique

Objectif :
- Simuler un conflit Git réel
- Identifier les modifications en conflit
- Résoudre le conflit manuellement
- Valider la résolution avec un commit

📌 Atelier réalisé en direct.

---
