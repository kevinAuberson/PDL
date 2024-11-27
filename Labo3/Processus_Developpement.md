# Processus de Développement Agile - Dispositif IoT pour Sécuriser les Dépassements Routiers

---

## Méthodologie Agile

Nous adoptons une approche Agile pour ce projet, basée sur les principes de Scrum et du développement itératif, afin de favoriser la flexibilité, la collaboration et la livraison continue de valeur. Voici comment nous allons structurer notre processus de développement :

### Pratiques Agiles Utilisées

1. **Scrum** :
   - Utilisation de sprints de 2 semaines avec des objectifs clairs et des livraisons incrémentales.
   - Réunions quotidiennes (stand-up) pour suivre les progrès et identifier les obstacles.
   - Rétrospectives régulières pour améliorer continuellement notre processus.

2. **Kanban** :
   - Utilisation d'un tableau Kanban pour visualiser le flux de travail et gérer les tâches.
   - Colonnes : Backlog, Analyse et Conception, Développement, Tests, Déploiement.

3. **Méthode PERT** :
   - Estimation des tâches en utilisant la méthode PERT pour évaluer les délais avec une approche optimiste, attendue et pessimiste.

### Roadmap du Projet

1. **Phase 1: Analyse et Conception (4 semaines)**
   - **Étude de Faisabilité Technique (2 semaines)**
     - Réaliser une analyse approfondie des technologies IoT disponibles pour la détection des véhicules en sens inverse.
     - Consulter des experts en IoT pour évaluer la faisabilité du projet.
   - **Conception Détaillée (2 semaines)**
     - Spécifier les capteurs nécessaires et les exigences matérielles.
     - Concevoir l'architecture logicielle du dispositif IoT.

2. **Phase 2: Développement (8 semaines)**
   - **Développement du Logiciel Embarqué (4 semaines)**
     - Implémenter les algorithmes de détection des véhicules en sens inverse.
     - Intégrer les composants logiciels avec les capteurs.
   - **Développement de l'Interface Utilisateur (2 semaines)**
     - Créer une interface intuitive pour afficher les alertes visuelles.
     - Assurer la compatibilité avec les systèmes embarqués des poids lourds et engins agricoles.
   - **Intégration Matérielle (2 semaines)**
     - Intégrer les composants matériels avec le logiciel développé.
     - Réaliser des tests d'intégration pour garantir le bon fonctionnement du dispositif.

3. **Phase 3: Tests et Validation (4 semaines)**
   - **Tests de Performance (2 semaines)**
     - Effectuer des tests de performance en laboratoire pour simuler différentes conditions de dépassement.
     - Mesurer la réactivité du dispositif et sa précision de détection.
   - **Validation Terrain (2 semaines)**
     - Installer le dispositif sur des véhicules pilotes en conditions réelles.
     - Collecter des données de dépassement pour valider l'efficacité des alertes visuelles.

4. **Phase 4: Déploiement et Suivi (2 semaines)**
   - **Installation sur Flottes Pilotes (1 semaine)**
     - Coordonner avec les partenaires pour installer le dispositif sur une flotte pilote de poids lourds et engins agricoles.
     - Former les conducteurs à l'utilisation du dispositif.
   - **Collecte et Analyse des Données (1 semaine)**
     - Mettre en place un processus de collecte de données automatisé.
     - Analyser les données collectées pour identifier les tendances et améliorations potentielles.

## Personas et User Stories

### Persona du Conducteur de Poids Lourd se Faisant Dépasser

---

#### Nom : Pierre Lambert

#### Âge : 45 ans

#### Profession : Conducteur de Poids Lourd

Pierre travaille comme conducteur de poids lourd pour une entreprise de transport de marchandises en Suisse. Avec plus de 20 ans d'expérience, il est habitué aux longs trajets sur les routes suisses, transportant divers types de cargaisons. Pierre a une excellente connaissance des routes nationales et des défis qu'elles présentent, notamment en termes de sécurité routière.

**Story** : En tant que conducteur de poids lourd, je veux un dispositif de signalisation sur mon véhicule qui informe les autres conducteurs si le dépassement est sûr, afin de réduire les risques d'accidents.

### Persona du Data Analyst à l'Office Fédéral de la Statistique (OFS)

---

#### Nom : Alexandre Martin

#### Âge : 34 ans

#### Profession : Data Analyst à l'Office Fédéral de la Statistique (OFS)

Alexandre travaille pour l'Office Fédéral de la Statistique (OFS) en Suisse, où il se spécialise dans l'analyse des données relatives à la sécurité routière et aux accidents de la route. Il détient un master en statistique appliquée et possède plus de 10 ans d'expérience dans l'analyse de grandes quantités de données pour des rapports gouvernementaux et des projets de recherche.

**Story** : En tant que data analyst à l'OFS, je veux collecter et analyser des données précises sur les situations de dépassement dangereuses, afin de proposer des recommandations pour améliorer la sécurité routière.

### Persona du Conducteur de la Voiture Effectuant le Dépassement

---

#### Nom : Sophie Muller

#### Âge : 32 ans

#### Profession : Cadre dans une entreprise de marketing

Sophie est une jeune professionnelle qui habite en banlieue et travaille en ville. Elle effectue régulièrement des trajets de moyenne distance pour se rendre au travail ou pour des rendez-vous professionnels. Elle est souvent pressée et cherche à optimiser son temps de déplacement. Conduisant une voiture compacte, elle est familière avec les routes à double sens où elle doit souvent dépasser des poids lourds et des engins agricoles.

**Story** : En tant que conductrice de voiture, je veux recevoir des informations claires sur la sécurité des dépassements, afin de réduire le stress et augmenter ma sécurité sur la route.

### Persona du Client (OFROU)

---

#### Nom : Thomas Meier

#### Âge : 50 ans

#### Profession : Responsable de la Sécurité Routière à l'Office Fédéral des Routes (OFROU)

Thomas travaille pour l'Office Fédéral des Routes (OFROU) en Suisse, où il supervise les initiatives de sécurité routière. Il possède un diplôme en génie civil et une expérience de plus de 25 ans dans la gestion des infrastructures routières et la mise en œuvre de politiques de sécurité routière. Thomas est chargé de la réduction des accidents sur les routes suisses et de l'amélioration continue des infrastructures routières.

**Story** : En tant que responsable de la sécurité routière à l'OFROU, je veux utiliser des technologies innovantes pour améliorer la sécurité des dépassements sur les routes suisses, afin de réduire le nombre d'accidents.

# Récapitulatif des Tâches

## Pierre Lambert (Conducteur de Poids Lourd se Faisant Dépasser)

1. **Recherche et Sélection de Capteurs**
   - Rechercher des capteurs fiables pour détecter les véhicules venant en sens inverse.
   - Sélectionner les capteurs les plus adaptés aux besoins du projet.

2. **Installation et Intégration des Capteurs**
   - Développer des méthodes d'installation des capteurs sur les poids lourds.
   - Intégrer les capteurs avec le système IoT du camion.

3. **Développement du Système de Signalisation**
   - Concevoir un système de signalisation visuelle pour informer les autres conducteurs.
   - Tester l'efficacité du système de signalisation en conditions réelles.

4. **Interface Utilisateur pour le Conducteur**
   - Développer une interface simple pour que Pierre puisse vérifier le fonctionnement du dispositif.
   - Créer des alertes pour informer Pierre en cas de dysfonctionnement du système.

5. **Tests et Validation**
   - Effectuer des tests de terrain pour valider la précision et la fiabilité du système.
   - Recueillir des retours d'expérience de Pierre pour améliorer le dispositif.

6. **Documentation et Formation**
   - Rédiger une documentation claire sur l'utilisation et la maintenance du dispositif.
   - Organiser des sessions de formation pour les conducteurs de poids lourds.

## Thomas Meier (Client - OFROU)

1. **Définition des Objectifs et Indicateurs de Performance**
   - Identifier les principaux objectifs de sécurité routière à atteindre.
   - Définir les indicateurs de performance clés pour évaluer l'efficacité des technologies.

2. **Sélection et Approvisionnement des Technologies**
   - Rechercher et sélectionner des technologies IoT adaptées au projet.
   - Assurer l'approvisionnement et la mise en place des technologies sélectionnées.

3. **Coordination avec les Partenaires**
   - Coordonner avec les entreprises de transport et les autorités locales pour le déploiement.
   - Établir des protocoles de collaboration pour le partage des données et des retours.

4. **Déploiement Pilote**
   - Organiser un déploiement pilote de la technologie sur une route spécifique.
   - Évaluer les résultats du pilote et ajuster les paramètres du projet si nécessaire.

5. **Analyse et Rapport des Données**
   - Analyser les données collectées pour évaluer l'impact sur la sécurité routière.
   - Rédiger des rapports détaillés pour les décideurs et les parties prenantes.

6. **Plan de Communication**
   - Développer un plan de communication pour informer le public et les parties prenantes.
   - Organiser des campagnes de sensibilisation sur la nouvelle technologie et ses avantages.

## Alexandre Martin (Data Analyst - OFS)

1. **Définition des Critères de Collecte de Données**
   - Identifier les types de données nécessaires pour l'analyse des dépassements.
   - Définir les critères de collecte pour garantir la précision et la fiabilité des données.

2. **Intégration des Sources de Données**
   - Intégrer les données collectées par les dispositifs IoT avec les bases de données existantes.
   - Assurer la compatibilité et l'interopérabilité des différentes sources de données.

3. **Développement d'Outils d'Analyse**
   - Créer des modèles d'analyse pour identifier les tendances et les facteurs de risque.
   - Utiliser des outils de visualisation de données pour présenter les résultats de manière claire.

4. **Analyse et Interprétation des Données**
   - Effectuer des analyses statistiques pour identifier les zones et moments à risque.
   - Interpréter les résultats pour en tirer des recommandations pratiques.

5. **Rapports et Recommandations**
   - Rédiger des rapports détaillés pour les décideurs politiques et les responsables de la sécurité routière.
   - Proposer des recommandations basées sur les analyses pour améliorer la sécurité routière.

6. **Présentation et Diffusion des Résultats**
   - Présenter les résultats de l'analyse lors de conférences et de réunions.
   - Diffuser les rapports et les recommandations auprès des parties prenantes.

## Sophie Muller (Conductrice de Voiture Effectuant le Dépassement)

1. **Tests Utilisateur**
   - Effectuer des tests utilisateur avec Sophie et d'autres conducteurs pour recueillir des retours.
   - Ajuster l'interface et les alertes en fonction des retours d'expérience des utilisateurs.

2. **Documentation et Support Utilisateur**
   - Rédiger une documentation utilisateur claire sur l'utilisation du système.
   - Mettre en place un support technique pour aider les utilisateurs en cas de problème.

3. **Éducation et Sensibilisation**
   - Développer des supports éducatifs pour sensibiliser les conducteurs à l'utilisation du système.
   - Organiser des sessions de formation ou des tutoriels en ligne pour les conducteurs.

# Estimation des Tâches

| Persona             | Tâche                                                  | Optimiste (heures) | Attendue (heures) | Pessimiste (heures) |
|---------------------|--------------------------------------------------------|-------------------:|-------------------:|--------------------:|
| Pierre Lambert      | Recherche et Sélection de Capteurs                     |                 10 |                15  |                 20  |
|                     | Installation et Intégration des Capteurs               |                 20 |                30  |                 40  |
|                     | Développement du Système de Signalisation              |                 25 |                35  |                 50  |
|                     | Interface Utilisateur pour le Conducteur               |                 15 |                20  |                 30  |
|                     | Tests et Validation                                    |                 30 |                40  |                 60  |
|                     | Documentation et Formation                             |                 15 |                20  |                 25  |
| Thomas Meier        | Définition des Objectifs et Indicateurs de Performance |                 12 |                18  |                 24  |
|                     | Sélection et Approvisionnement des Technologies        |                 20 |                25  |                 35  |
|                     | Coordination avec les Partenaires                      |                 18 |                24  |                 32  |
|                     | Déploiement Pilote                                     |                 25 |                35  |                 45  |
|                     | Analyse et Rapport des Données                         |                 20 |                30  |                 40  |
|                     | Plan de Communication                                  |                 15 |                20  |                 25  |
| Alexandre Martin    | Définition des Critères de Collecte de Données         |                 10 |                15  |                 20  |
|                     | Intégration des Sources de Données                     |                 20 |                30  |                 40  |
|                     | Développement d'Outils d'Analyse                       |                 25 |                35  |                 50  |
|                     | Analyse et Interprétation des Données                  |                 20 |                25  |                 35  |
|                     | Rapports et Recommandations                            |                 18 |                24  |                 30  |
|                     | Présentation et Diffusion des Résultats                |                 12 |                18  |                 24  |
| Sophie Muller       | Tests Utilisateur                                      |                 18 |                24  |                 30  |
|                     | Documentation et Support Utilisateur                   |                 12 |                18  |                 24  |
|                     | Éducation et Sensibilisation                           |                 10 |                15  |                 20  |
