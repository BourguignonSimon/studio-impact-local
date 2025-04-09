# Création du tableau Kanban sur GitHub Projects

Pour mettre en place le tableau Kanban, suivez ces étapes :

1. Accédez à https://github.com/BourguignonSimon/studio-impact-local
2. Cliquez sur l'onglet "Projects"
3. Cliquez sur "New project"
4. Sélectionnez "Board" comme template
5. Nommez le projet "Studio d'Impact Local - Kanban"
6. Cliquez sur "Create"

## Configuration du tableau Kanban

1. Dans le nouveau projet, vous verrez par défaut 3 colonnes : "Todo", "In Progress" et "Done"
2. Modifiez ces colonnes pour correspondre à notre flux de travail :
   - Renommez "Todo" en "Backlog"
   - Ajoutez une nouvelle colonne "À planifier" entre "Backlog" et "In Progress"
   - Renommez "In Progress" en "En cours"
   - Ajoutez une nouvelle colonne "Révision" entre "En cours" et "Done"
   - Renommez "Done" en "Terminé"

3. Ajoutez les issues existantes au projet :
   - Cliquez sur "Add items" en haut à droite
   - Sélectionnez toutes les issues du repository
   - Placez-les dans la colonne "Backlog"

4. Organisez les issues par priorité :
   - Les issues avec le label "priority:high" doivent être en haut du Backlog
   - Les issues avec le label "priority:medium" viennent ensuite
   - Les epics (#1 à #5) doivent rester en vue pour référence

## Utilisation quotidienne

1. Lors de la planification de sprint :
   - Déplacez les issues sélectionnées de "Backlog" vers "À planifier"
   - Assignez les issues aux membres de l'équipe

2. Lorsque vous commencez à travailler sur une issue :
   - Déplacez-la de "À planifier" vers "En cours"
   - Mettez à jour régulièrement l'avancement dans l'issue

3. Lorsque vous avez terminé une tâche :
   - Déplacez l'issue vers "Révision"
   - Demandez à un autre membre de l'équipe de réviser votre travail

4. Une fois la révision validée :
   - Déplacez l'issue vers "Terminé"
   - Célébrez l'accomplissement !

## Filtres utiles

Créez ces filtres pour faciliter la gestion du projet :

1. **Mon travail actuel**
   - Filtre : `assignee:@me status:"En cours"`

2. **Priorités hautes non assignées**
   - Filtre : `label:"priority:high" no:assignee`

3. **En attente de révision**
   - Filtre : `status:"Révision"`

4. **Par pilier**
   - Filtre : `label:"pilier:canvas"` (ou autre pilier)

## Révisions régulières

Planifiez ces révisions régulières :

1. **Daily standup** (15 min, chaque jour ou 3 fois par semaine)
   - Passez en revue les issues "En cours"
   - Identifiez les blocages
   - Ajustez les priorités si nécessaire

2. **Revue de sprint** (1h, toutes les deux semaines)
   - Passez en revue les issues "Terminé"
   - Démontrez les résultats
   - Recueillez les feedbacks

3. **Planification de sprint** (1h, toutes les deux semaines)
   - Sélectionnez les issues du prochain sprint
   - Déplacez-les de "Backlog" vers "À planifier"
   - Assignez les responsabilités