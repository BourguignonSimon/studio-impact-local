# Procédure de test des maquettes visuelles - Studio d'Impact Local

Ce document définit la méthodologie spécifique pour tester efficacement les maquettes visuelles des différents outils du Studio d'Impact Local. Il complète la procédure de test standardisée générale en se concentrant sur les aspects visuels et d'expérience utilisateur.

## 1. Préparation des tests

### Sélection des participants
- **Groupe interne**: 2-3 membres de l'équipe n'ayant pas participé directement à la conception
- **Groupe amis**: 3-5 personnes proches du projet mais non impliquées dans la création
- **Groupe cible**: 5-8 personnes représentatives des futurs utilisateurs (selon personas)

### Préparation des scénarios de test
- Élaborer 3-5 scénarios d'utilisation par outil, basés sur les personas (issue #27)
- Rédiger les consignes précises pour chaque scénario
- Préparer des questions guide pour l'entretien post-test

### Configuration de l'environnement de test
- Préparer les maquettes dans leur format natif et en version partageable
- Configurer les outils d'enregistrement (écran, voix, expressions faciales si possible)
- Tester les outils de partage d'écran et de prototype avant les sessions

## 2. Protocole de test

### Accueil et introduction (5-10 min)
- Présenter brièvement le concept du Studio d'Impact Local
- Expliquer le but du test (évaluer les maquettes, pas les participants)
- Préciser qu'il n'y a pas de bonnes ou mauvaises réponses
- Obtenir le consentement pour l'enregistrement

### Test guidé (15-20 min par outil)
- Présenter les maquettes sans trop d'explications
- Demander aux participants de réaliser les scénarios préparés
- Utiliser la méthode "penser à voix haute"
- Observer sans intervenir sauf si absolument nécessaire
- Noter les points d'hésitation, les erreurs, les réactions positives

### Questionnaire post-test (5-10 min)
- Faire remplir un questionnaire standardisé (SUS - System Usability Scale)
- Ajouter des questions spécifiques sur l'esthétique et la compréhension
- Inclure des échelles de notation (1-5) pour aspects clés:
  - Clarté visuelle
  - Attrait esthétique
  - Facilité de compréhension
  - Cohérence avec les attentes
  - Impression d'utilité

### Entretien semi-directif (10-15 min)
- Explorer les impressions générales
- Approfondir les points de friction observés
- Recueillir des suggestions d'amélioration
- Évaluer la perception de la valeur et de l'utilité

## 3. Types de tests spécifiques par outil

### Tests du Canvas
- **Test de compréhension**: présenter le canvas vide et demander d'expliquer sa structure
- **Test de remplissage**: fournir un cas d'étude et demander de remplir le canvas
- **Test de navigation**: pour la version digitale, évaluer les interactions entre les sections
- **Test d'impression**: vérifier la lisibilité et l'utilisabilité de la version imprimable

### Tests de la Narration
- **Test de structure**: évaluer la compréhension des 5 étapes sans explication préalable
- **Test de création**: demander aux participants de créer une mini-narration avec les templates
- **Test de présentation**: demander d'utiliser les supports pour présenter un projet fictif
- **Test de mémorisation**: vérifier la rétention des 5 étapes après utilisation

### Tests du Micro-centre
- **Test d'orientation**: demander de décrire comment ils utiliseraient l'espace
- **Test de projection**: évaluer leur capacité à se projeter dans les différentes zones
- **Test des configurations**: présenter les différentes configurations et recueillir leur préférence
- **Test des parcours**: demander de tracer le parcours qu'ils suivraient pour différentes activités

### Tests de l'interface digitale
- **Test de navigation**: évaluer la facilité à trouver des informations spécifiques
- **Test des tâches**: demander de réaliser des actions précises dans l'interface
- **Test du design system**: évaluer la cohérence et la compréhension des composants UI
- **Test d'accessibilité**: vérifier la lisibilité, les contrastes et la facilité d'utilisation

## 4. Analyse des résultats

### Métriques quantitatives
- **Taux de réussite**: pourcentage de tâches complétées avec succès
- **Temps d'exécution**: durée nécessaire pour accomplir chaque tâche
- **Taux d'erreur**: nombre d'erreurs commises pendant la réalisation des tâches
- **Score SUS**: évaluation standardisée de l'utilisabilité (objectif >68/100)
- **Scores spécifiques**: moyenne des notes sur les échelles personnalisées

### Analyse qualitative
- **Thèmes récurrents**: identifier les patterns dans les commentaires et observations
- **Points de friction**: cataloguer les problèmes rencontrés par ordre de fréquence et gravité
- **Suggestions**: classifier les propositions d'amélioration par faisabilité et impact
- **Citations marquantes**: recueillir des verbatims représentatifs pour illustrer les retours

### Priorisation des améliorations
- Utiliser une matrice impact/effort pour prioriser les modifications
- Classer les problèmes en:
  - **Critiques**: bloquants, affectent significativement l'expérience (à corriger immédiatement)
  - **Majeurs**: limitent l'efficacité ou la satisfaction (à planifier rapidement)
  - **Mineurs**: n'empêchent pas l'utilisation mais créent de la friction (à planifier)
  - **Cosmétiques**: détails d'amélioration (à considérer ultérieurement)

## 5. Documentation et suivi

### Rapport de test
- Synthèse des résultats quantitatifs
- Analyse des retours qualitatifs
- Liste priorisée des problèmes identifiés
- Recommandations d'améliorations
- Plan d'action pour l'itération

### Mise à jour du backlog
- Créer des issues GitHub pour les modifications prioritaires
- Lier ces issues au rapport de test
- Planifier les modifications dans les prochaines itérations

### Communication des résultats
- Présenter les résultats clés à l'équipe
- Organiser une session de debriefing collaborative
- Documenter les décisions prises suite aux tests

### Planification des prochains tests
- Planifier les tests pour la prochaine itération des maquettes
- Affiner les scénarios de test en fonction des résultats précédents
- Envisager de tester avec de nouveaux participants ou de recontacter les mêmes

## 6. Templates et outils

### Formulaire de consentement
```
# Formulaire de consentement - Test de maquettes visuelles

Je, soussigné(e) _________________________, accepte de participer à une session 
de test des maquettes visuelles du Studio d'Impact Local.

Je comprends que:
- Ma participation est volontaire et je peux arrêter à tout moment
- La session sera enregistrée (audio/vidéo/capture d'écran)
- Les données recueillies ne seront utilisées que pour améliorer les outils
- Mon anonymat sera préservé dans l'analyse et les rapports

Date: ___/___/_____ 
Signature: _________________
```

### Questionnaire SUS adapté
```
Pour chaque affirmation, indiquez votre degré d'accord sur une échelle de 1 (pas du tout d'accord) à 5 (tout à fait d'accord):

1. Je pense que j'utiliserais volontiers cet outil fréquemment
2. J'ai trouvé cet outil inutilement complexe
3. J'ai trouvé cet outil facile à utiliser
4. Je pense avoir besoin d'une aide technique pour utiliser cet outil
5. J'ai trouvé que les différentes fonctions étaient bien intégrées
6. J'ai trouvé trop d'incohérences dans cet outil
7. Je pense que la plupart des gens apprendraient rapidement à utiliser cet outil
8. J'ai trouvé cet outil très lourd à utiliser
9. Je me suis senti(e) en confiance en utilisant cet outil
10. J'ai dû apprendre beaucoup de choses avant de pouvoir utiliser cet outil

11. L'apparence visuelle de cet outil est attrayante
12. Les informations sont présentées de façon claire et lisible
13. La structure et l'organisation sont intuitives
14. Cet outil me semble utile pour mon projet d'impact local
15. Je recommanderais cet outil à d'autres porteurs de projets
```

### Grille d'observation
```
# Grille d'observation - Test de maquettes visuelles

Participant: _________________ 
Date: ___/___/_____
Maquette testée: _________________

## Scénario 1: [Description du scénario]
- Tâche réussie: □ Oui □ Partiellement □ Non
- Temps d'exécution: ___ min ___ sec
- Nombre d'erreurs: ___
- Points d'hésitation: _____________________________
- Réactions notables: _____________________________

## Scénario 2: [Description du scénario]
[...]

## Observations générales
- Langage corporel: _____________________________
- Commentaires spontanés: _____________________________
- Questions posées: _____________________________
- Frustrations exprimées: _____________________________
- Points d'appréciation: _____________________________
```

### Structure du rapport de test
```
# Rapport de test - [Nom de la maquette]

## Résumé exécutif
- Principales conclusions
- Recommandations prioritaires

## Méthodologie
- Dates et lieu des tests
- Nombre et profil des participants
- Scénarios testés

## Résultats quantitatifs
- Taux de réussite par scénario
- Temps moyens d'exécution
- Scores SUS et autres métriques

## Analyse qualitative
- Thèmes principaux identifiés
- Points forts 
- Points d'amélioration
- Citations représentatives

## Plan d'action
- Modifications prioritaires
- Calendrier d'implémentation
- Prochaines étapes de test

## Annexes
- Données brutes
- Captures d'écran annotées
- Liens vers les enregistrements
```

## 7. Ressources supplémentaires

### Conseils pour les facilitateurs de test
- Restez neutre pendant les observations
- Évitez de guider les participants ou de réagir à leurs difficultés
- Encouragez à "penser à voix haute" sans diriger
- Prenez des notes détaillées sur les comportements non-verbaux
- Posez des questions ouvertes plutôt que fermées
- Demandez "pourquoi?" pour approfondir les réponses

### Adaptations pour les tests à distance
- Privilégier des outils de visioconférence avec partage d'écran
- Demander aux participants d'activer leur caméra si possible
- Prévoir 5-10 minutes supplémentaires pour la configuration technique
- Envoyer les liens et instructions à l'avance
- Avoir un plan B en cas de problème technique
- Adapter le rythme pour compenser le manque d'indices non-verbaux

### Recommandations pour l'analyse
- Impliquer plusieurs membres de l'équipe dans l'analyse
- Distinguer les problèmes d'utilisabilité des préférences personnelles
- Rechercher les patterns plutôt que les cas isolés
- Pondérer les retours en fonction des personas cibles
- Relier les problèmes identifiés aux principes de design

---

Cette procédure sera régulièrement mise à jour en fonction des retours d'expérience. Consultez toujours la version la plus récente avant de commencer une série de tests.