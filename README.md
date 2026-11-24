# Planning

Un planning hebdomadaire dans l'esprit du Calendrier d'Apple, en une seule page HTML : créneaux par pôle d'activité, tâches placées directement sur la grille, objectifs d'heures et alarmes.

**Ouvrir le planning : https://meraldbrenonpro.github.io/planning/**

## Ce qu'on peut faire

- **Vues Jour, Semaine et Mois**, avec navigation au clavier ou par balayage sur téléphone.
- **Créneaux** : clique dans la grille ou trace la durée à la souris, glisse un bloc pour le déplacer, tire son bord bas pour l'allonger. Un créneau peut se répéter chaque semaine, et on peut en retirer un seul jour.
- **Tâches en une phrase** : « Appel client demain 14h 45 min » remplit seul la date, l'heure et la durée. Sans heure, la tâche prend le prochain créneau libre.
- **Charge de la semaine** : total d'heures, répartition par pôle, objectifs et alerte de chevauchement.
- **Alarmes** : une sonnerie avant chaque créneau ou tâche, avec rappel dans 5 minutes. Elle ne sonne que si la page est ouverte.
- **Annuler** : Ctrl+Z ou le bouton du message en bas d'écran.

## Raccourcis

| Touche | Action |
| --- | --- |
| ← → | Période précédente ou suivante |
| T | Aujourd'hui |
| J, S, M | Vue Jour, Semaine, Mois |
| N | Nouveau créneau |
| Alt + flèches | Déplacer le bloc sélectionné |
| Ctrl+Z | Annuler |

## Données

Tout est enregistré dans le navigateur de la personne qui utilise la page (localStorage) : rien n'est envoyé à un serveur, et chacun a son propre planning. Changer de navigateur ou vider ses données repart du modèle de départ.

## Installer sa propre copie

Aucune dépendance ni étape de build : `index.html` s'ouvre tel quel. Pour l'héberger, fork le dépôt puis active GitHub Pages (Settings, Pages, branche `main`, dossier racine).

---

Conçu par [Bren'Art Studio](https://brenartstudio.fr).
