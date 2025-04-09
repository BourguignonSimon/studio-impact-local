# Organisation du projet avec Kanban

Ce document décrit l'organisation du flux de travail pour le projet Studio d'Impact Local à l'aide d'un tableau Kanban sur GitHub Projects.

## Structure du tableau Kanban

Le tableau Kanban est organisé en 5 colonnes qui représentent les différentes étapes du flux de travail :

### 1. Backlog (À faire)
- Toutes les tâches identifiées mais pas encore planifiées pour le sprint en cours
- Les tâches sont triées par priorité (haute en haut, basse en bas)
- Chaque tâche doit avoir au minimum un label et être rattachée à un Epic (issue principale)

### 2. À planifier
- Tâches sélectionnées pour le sprint en cours
- Ces tâches sont prêtes à être attribuées et travaillées
- Elles contiennent une description complète et des critères d'acceptation clairs

### 3. En cours
- Tâches sur lesquelles quelqu'un travaille activement
- Une personne ne devrait pas avoir plus de 2-3 tâches "En cours" simultanément
- Si une tâche est bloquée, ajouter le label "bloqué" et documenter la raison dans un commentaire

### 4. Révision
- Tâches terminées qui nécessitent une révision ou un test
- Chaque tâche doit être revue par une personne différente de celle qui l'a réalisée
- Les commentaires et suggestions d'amélioration sont ajoutés directement dans l'issue

### 5. Terminé
- Tâches qui ont passé l'étape de révision avec succès
- Ces tâches sont considérées comme complètement terminées
- Les tâches terminées sont archivées à la fin de chaque sprint

## Utilisation des labels

Les labels nous aident à organiser et filtrer les issues :

- **Type:**
  - `feature`: Nouvelle fonctionnalité
  - `bug`: Correction d'un problème
  - `documentation`: Amélioration de la documentation
  - `enhancement`: Amélioration d'une fonctionnalité existante

- **Priorité:**
  - `priority:high`: Tâche prioritaire à traiter en premier
  - `priority:medium`: Priorité normale
  - `priority:low`: Peut attendre ou être reportée

- **Statut:**
  - `blocked`: Tâche bloquée par un problème externe
  - `needs-review`: Besoin d'une révision ou d'une décision
  - `in-progress`: Travail en cours
  - `ready`: Prêt à être travaillé

- **Pilier:**
  - `pilier:canvas`: Relatif à l'Impact Model Canvas
  - `pilier:narration`: Relatif à la Narration Signature
  - `pilier:micro-centre`: Relatif au Micro-centre Pilote
  - `pilier:offre`: Relatif à l'offre "Lance ton projet"
  - `pilier:monétisation`: Relatif à la stratégie de monétisation

## Les Epics (issues principales)

Les Epics servent à regrouper les tâches liées à un même objectif majeur :

1. **#1 Impact Model Canvas** - Développement complet du canvas et de ses outils
2. **#2 Narration Signature** - Développement de la méthodologie narrative et des supports
3. **#3 Micro-centre Pilote** - Conception et mise en œuvre du lieu physique
4. **#4 Offre "Lance ton projet"** - Développement de l'offre commerciale
5. **#5 Stratégie de monétisation** - Élaboration du modèle économique global

Chaque tâche (issue secondaire) doit être rattachée à l'un de ces Epics pour maintenir une organisation claire.

## Organisation des sprints

Nous travaillons en cycles de deux semaines (sprints) :

### Début de sprint
- Réunion de planification (1h)
- Sélection des tâches prioritaires pour le sprint
- Estimation de l'effort pour chaque tâche
- Attribution des responsabilités

### Pendant le sprint
- Stand-up quotidien ou bihebdomadaire (15 min)
- Mise à jour du tableau Kanban
- Documentation des progrès dans les issues

### Fin de sprint
- Réunion de revue (1h)
- Démonstration des réalisations
- Rétrospective sur ce qui a bien fonctionné et ce qui peut être amélioré
- Préparation du sprint suivant

## Flux de travail des tâches

### Création d'une nouvelle tâche
1. Créer une issue en utilisant le template approprié
2. Ajouter une description détaillée et des critères d'acceptation
3. Ajouter les labels pertinents
4. Rattacher l'issue à un Epic
5. Placer l'issue dans la colonne "Backlog"

### Traitement d'une tâche
1. Déplacer l'issue dans "À planifier" lors de la planification de sprint
2. S'assigner la tâche et la déplacer dans "En cours"
3. Créer une branche pour les tâches de développement (format: `type/issue-number-short-description`)
4. Mettre à jour régulièrement l'issue avec l'avancement
5. Soumettre la tâche pour révision une fois terminée

### Révision et clôture
1. Un autre membre de l'équipe révise la tâche
2. Une fois approuvée, l'issue est déplacée dans "Terminé"
3. Pour les tâches de développement, fusionner la branche avec main
4. Célébrer l'accomplissement!

## Métriques et suivi

Nous suivons ces métriques pour mesurer notre efficacité :

- **Vélocité** : Nombre de tâches terminées par sprint
- **Cycle time** : Temps moyen entre le début et la fin d'une tâche
- **Taux de complétion** : Pourcentage de tâches planifiées qui sont effectivement terminées
- **Distribution par pilier** : Répartition de l'effort entre les différents piliers du projet

## Schéma général de progression du projet

```
Phase 1: FONDATIONS       Phase 2: DÉVELOPPEMENT     Phase 3: EXPANSION        Phase 4: CONSOLIDATION
+-------------------+     +--------------------+     +------------------+     +--------------------+
| • Canvas          |     | • Micro-centre     |     | • Déploiement    |     | • Automatisation   |
| • Narration       | --> | • Offre complète   | --> | • Commercial     | --> | • Licence         |
| • Test pilote     |     | • Lancement        |     | • Documentation  |     | • Bilan & Plan     |
+-------------------+     +--------------------+     +------------------+     +--------------------+
    Mois 1-3                  Mois 4-6                 Mois 7-9                Mois 10-12
```

Cette organisation permet de maintenir une vue d'ensemble du projet tout en avançant efficacement sur les différentes composantes.