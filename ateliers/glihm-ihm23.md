
# Atelier GL-IHM à IHM 2023

## Organisateurs

- Arnaud Blouin, Univ Rennes
- Philippe Palanque, Université Toulouse III
- Xavier Le Pallec, Univ Lille

## Thématique principale de l'atelier à IHM 2023

Les fonctions d'utilisabilité (usability functions) et leur présence dans les toolkits UI : définition, recensement, description et spécification.  


## Instructions aux auteurs - soumission & notification

- 1 page attendue (plus si utile)
- format ACM SIGCHI double colonne 
- par email aux organisateurs de l'atelier (arnaud.blouin at irisa point fr, palanque at irit point fr)
- date limite 23/01/2023 AoE
- notification le 27/01/2023
- programme publié sur le site IHM le 01/03/2023
- atelier le 03/04/2023 (toute la journée)



## Introduction
Dans l'article [ref1], une fonction d'utilisabilité est définie en référence aux fonctions de sécurité [ref2] (e.g. un screen locker) ou de sureté [ref3] (e.g. une ceinture de sécurité dans une voiture). L'undo/redo, l'annulation de tâches en cours (cancelation) ou le feedforward sont des fonctions d'utilisabilité dans la mesure où elles n'ajoutent pas de fonctionnalités nouvelles au système mais augmentent uniquement son utilisabilité. De façon similaire, une fonction de sureté va accroitre la sureté du système en prévenant des problèmes de sureté non désirés (par exemple la ceinture de sécurité n'ajoute rien au véhicule mais accroit la sureté des passagers en réduisant meur probabilité d'être bléssés ou d'être tués).
Actuellement les fonctions d'utilisabilité sont nombreuses, difficiles à programmer (e.g. pour undo [ref4]), hétérogènes et mal identifiées même si leur bénéfice en terme d'utilisabilité est indiscutable. 


## Activités envisagées dans l'atélier
Même si le thème de l'atelier est unique, les objectifs sont multiples et peuvent être orientés vers les diverses communautés qui constituent le GT GL-IHM : l'idée est de recenser les fonctions d'utilisabilité (communauté IHM) et d'évaluer leur présence dans les toolkits et logiciels actuels (communauté GL).

Nous proposons ici un ensemble de pistes à prioriser en fonction de l'intérêt des participants : 
-  Recenser / décrire / analyser les fonctions d'utilisabilité existantes 
-  Recensement et décrire à quel point ces fonctions sont considérées et mises en oeuvre dans les toolkits UI actuels (Web, desktop, mobile) et dans les outils de modélisation (e.g. Sirius, Papyrus) et de développement (IDE)
- Recensement des tâches de développement (aussi bien code que modèle) et identification de ces tâches dont la charge de travail est allégée par l'ajout de fonctions d'utilisabilité 


Pour lancer la réflexion nous proposons ci-dessous un ensemble de fonctions d'utilisabilité et de tâches de dévelopement. 

*Fonctions d'utilisabilité*
- undo/redo
- copier/coller
- feedforward
- feedback
- suggestions/completion
- navigation
- build system 
- Continuous Integration / Continuous Deployment
- automatisations
- linters / analyse de code
- etc.

*Exemples de tâches des développeurs (activités en développement en solo programmation ou modélisation)*
- reusinage (refactoring)
- écriture/execution tests
- détecter les défauts
- corriger les défauts 
- produire les fonctions demandées dans les exigences 
- offrir les performances demandées dans les exigences
- navigation dans code/modèle (comprehénsion)
- etc.

*Références*
[ref 1] Navarre, D., Palanque, P., Coppers, S., Luyten, K., & Vanacken, D. (2021). Model-based Engineering of Feedforward Usability Function for GUI Widgets.  Interacting with Computers, 33(1), 73-91.
[ref2] Yoon, C., Park, T., Lee, S., Kang, H., Shin, S. and Zonghua, Z. (2015) Enabling security functions with SDN. Comput. Netw., 85, 19–35. 
[ref3] Lee, S. and Yamada, Y. (2010) Strategy on safety function implementation: case study involving risk assessment and functional safety analysis for a power assist system. Adv. Robot., 24, 1791–1811.
[ref4] Interacto: A Modern User Interaction Processing Model. Arnaud Blouin, Jean-Marc Jézéquel. IEEE Transactions on Software Engineering, 2021


## Contribution

Voici une liste non exhausitive de contributions attendues :
- Détail d'une fonction d'utilisabilité
- Détail concernant la (non) présence d'une fonction d'utilisabilité dans les toolkits UI ou logiciels actuels
- Détail sur comment un logiciel donné gère certaines fonctions d'utilisabilité
- Détail sur une ou plusieurs tâches des développeurs
