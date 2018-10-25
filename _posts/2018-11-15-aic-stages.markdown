---
layout: post
title:  "propositions de stages"
date:   2018-11-15 10:45:00 +0200
categories: ens aic
---
## Stage au LIMSI CNRS : Comparaison de fonctions objectif pour l'apprentissage de représentation : application à la vérification du locuteur et au calcul de similarité sémantique textuelle

### Contacts
Sahar Ghannay (ghannay@limsi.fr), Sophie Rosset (rosset@limsi.fr), Hervé Bredin (bredin@limsi.fr)

### Sujet
Le rôle de la fonction objectif dans l'apprentissage neuronal est de fournir une mesure de la performance du réseau de neurones (i.e. sa capacité à répondre correctement à une tâche précise). Cette mesure, lorsqu'elle est dérivable, permet alors de mettre à jour le réseau de neurones par rétro-propagation du gradient de telle sorte que sa performance soit améliorée.
Parmi ces fonctions objectif, on peut par exemple citer la “contrastive loss” [HCL06], la “triplet loss” [SKP15], ou encore la “center loss” [WZLQ16].
L'objectif de ce stage est de comparer différentes fonctions objectif permettant l'apprentissage des représentations neuronales adaptées à des tâches applicatives telles que la vérification du locuteur et la similarité sémantique textuelle. La plupart de ces méthodes ont été initialement proposées dans le domaine de la vision par ordinateur pour la reconnaissance d'image (et de visage en particulier) et certaines ont été appliquées récemment à tâche de vérification du locuteur [Bre17]. Cependant, elles n'ont pas encore été utilisées pour la tâche de similarité sémantique textuelle.

### Description des tâches
* Implémentation des différentes fonctions objectif : Après une étape d’étude de la littérature sur le sujet, la première tâche consiste à implémenter les fonctions objectif les plus prometteuses en les testant sur des exemples jouet bien maîtrisés (tels que la base MNIST de reconnaissance de chiffre manuscrit, par exemple).
* Application à la vérification du locuteur : La tâche de vérification du locuteur consiste à déterminer si deux signaux audio proviennent ou non de l’enregistrement du même locuteur. On utilisera la base de données VoxCeleb [CNZ18, NCZ17] pour mener ces expériences. Elle contient plus d’un million d’enregistrements correspondant à plus de 6000 locuteurs, et constitue de fait le plus grand corpus librement disponible pour l’identification et la vérification du locuteur.
* Application au calcul de similarité sémantique textuelle : La tâche de similarité sémantique textuelle (SST) est motivée par le fait que la modélisation de la similarité sémantique des phrases est un problème fondamental en compréhension de la langue, pertinent pour de nombreuses applications, notamment la traduction automatique, la recherche de réponses à des questions précises (ou questions-réponses), le dialogue dialogue, etc.
Cette tâche consiste à évaluer dans quelle mesure deux phrases sont sémantiquement équivalentes. Plusieurs approches ont étés proposées [CDA + 17], qui sont fondées généralement soit sur les méthodes classiques en traitement automatique des langues (TAL), soit sur des méthodes d’apprentissage profond. La première approche s’appuie sur l’utilisation d’un classifieur enrichi par différents types de descripteurs : sémantiques, syntaxiques, etc. La deuxième est fondée sur l’exploitation des représentations de phrases et des architectures neuronales. Dans le cadre des campagnes d’évaluation SemEval, la tâche de SST a été proposée. Dans ce cadre, la tâche consiste pour le système de SST à attribuer un score de similarité à chaque paire de phrase sur une échelle de 0 (les deux phrases sont complètement différentes) à 5 (les deux phrases sont complè tement identiques)... Notre objectif dans ce stage est de pouvoir étudier les différentes fonctions objectif sur la tâche SST et de comparer nos résultats aux résultats obtenus par les différents systèmes ayant participé à la tâche 5 (en anglais) de la campagne d’évaluation SemEval 2017. Ce système fait la combinaison des approches de TAL et d’apprentissage profond.

### Références
[Bre17] Hervé Bredin. Tristounet : triplet loss for speaker turn embedding. In 2017 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pages 5430–5434. IEEE, 2017.
[CDA + 17] Daniel Cer, Mona Diab, Eneko Agirre, Inigo Lopez-Gazpio, and Lucia Specia. Semeval-2017 task 1 : Semantic textual similarity-multilingual and cross-lingual focused evaluation. arXiv preprint arXiv :1708.00055, 2017.
[CNZ18] Joon Son Chung, Arsha Nagr ni, and Andrew Zisserman. Voxceleb2 : Deep speaker recognition. arXiv preprint arXiv :1806.05622, 2018.
[HCL06] Raia Hadsell, Sumit Chopra, and Yann LeCun. Dimensionality reduction by learning an invariant mapping. In CVPR 2006, pages 1735–1742. IEEE, 2006.
[NCZ17] Arsha Nagrani, Joon Son Chung, and Andrew Zisserman. Voxceleb : a large-scale speaker identification dataset. arXiv preprint arXiv :1706.08612, 2017.
[SKP15] Florian Schroff, Dmitry Kalenichenko, and James Philbin. Facenet : A unified embedding for face recognition and clustering. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 815–823, 2015.
[WZLQ16] Yandong Wen, Kaipeng Zhang, Zhifeng Li, and Yu Qiao. A discriminative feature learning approach for deep face recognition. In European Conference on Computer Vision, pages 499–515. Springer, 2016.

### Profil attendu
- Master 2 en Informatique (ou équivalent), avec au moins une spécialité en
  - Apprentissage
  - Traitement automatique de la langue
  - Traitement de la parole
      
compétences techniques : python, linux


### Informations pratiques
- Durée du stage:  5-6 mois (stage pouvant donner lieu à une poursuite en thèse)
- Début du stage:  date de début à définir avec le stagiaire
- Gratification: environ 570€/mois. remboursement frais de transport et subvention cantine


## Stage Skaizengroup: Automatic Knowledge base population based on public sources integration and sourcing

### Contact
ncabioch@skaizengroup.fr

### Objectif du stage
- Establish the state of the art in term of automted Knowledge base population from public sources with fact checking and best validity scoring algorithms and approaches. Our goal in this first part of the mission is to analyze different options and solutions in the field  of Natural Language Processing, Topic Detection and tracking, Entity link detection and evaluation systems, Content based recommendations, supervised and unsupervised learning. Performance and scoring evaluation framework should also be highlighted and their performances evaluated.
In this first goal, we want to have an emphasis on the impact of targeting a sharp and very specific topic field (like biology, finance or even sharper like Know Your Customers) on the performances of the automated population of the KB, as well as the impact of multi-lingual environments on the same.
- Start modélisation and experimentations (POC) on the possible lever to improvements the state of the art solution, especially to increase the level of confidence on the incorporated information through
- Use of ontologies on specific domains for Entity Relation extraction improvement
- Creation of simple distributed network of experts to validate information (in a blockchain like mode)
- Use of Semantic dependency parsing, opinion analysis, negation parsing and associated tooling

Focus on the second part will be on Know Your Customers activity
It will be done in relation with Business Subject Mater experts

### Profil attendu 
- Master2 / PHD Profile
- Natural Language Parsing and Understanding Expertise
- Data Science, Machine Learning, Information acquisition appetite
- skills in data programmation (R, Python, tensorflow or equivalent and machine learning)
- In touch with the academic community
- Capacity to produce scientific publications and conference papers
- hard worker, and ability to work in small teams

### Informations pratiques
Les locaux sont à Paris La Défense, mais du télétravail est possible

Le salaire est à discuter selon expérience