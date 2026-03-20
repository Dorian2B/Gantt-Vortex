# Gantt-Vortex

**Gantt-Vortex** est une application web légère et performante conçue pour la planification de projets. Elle permet de jongler instantanément entre une vue **Gantt** interactive et un réseau **MPM (Méthode des Potentiels Metra)** pour une analyse précise du chemin critique.

Entièrement construit en **Vanilla JS, HTML5 et CSS3**, cet outil ne nécessite aucune installation ni dépendance externe.

---

## Fonctionnalités Clés

### 📅 Planification Interactive (Gantt)
*   **Manipulation Directe** : Glissez-déposez les barres pour modifier les dates ou étirez-les pour ajuster la durée.
*   **Gestion des Dépendances** : Créez des liens entre les tâches avec détection automatique des cycles.
*   **Zoom Adaptatif** : Basculez entre les vues Jour, Semaine et Mois.
*   **Sections** : Organisez vos tâches par groupes repliables pour une meilleure lisibilité.

### 🕸️ Analyse Réseau (MPM)
*   **Génération Automatique** : Visualisez votre projet sous forme de noeuds logiques.
*   **Calcul des Marges** : Calcul automatique des dates "au plus tôt" et "au plus tard".
*   **Chemin Critique** : Identification visuelle immédiate des tâches critiques (marge nulle) en rouge.

### 🛠️ Outils & Ergonomie
*   **Mode Sombre/Clair** : Interface moderne avec thèmes interchangeables.
*   **Persistance Locale** : Sauvegarde automatique de votre projet dans le navigateur.
*   **Import/Export** : Support des formats **JSON**, **CSV**, **Excel** et export de la vue en image **PNG**.
*   **Historique** : Système d'annulation (Undo) et de rétablissement (Redo) complet.
*   **Responsive** : Navigation optimisée pour mobile avec une barre de menu dédiée. (Et bien sûr PC)

---

## 🚀 Démarrage Rapide

Comme le projet est contenu dans un fichier unique, l'exécution est immédiate :

1.  Téléchargez le fichier `index.html`.
2.  Ouvrez-le dans n'importe quel navigateur moderne (Chrome, Firefox, Edge, Safari).
3.  Commencez à planifier !

---

## Raccourcis Clavier

| Raccourci | Action |
| :--- | :--- |
| `Ctrl + Z` | Annuler la dernière action |
| `Ctrl + Y` | Rétablir l'action |
| `Ctrl + S` | Forcer la sauvegarde locale |
| `Double-clic` | Modifier une tâche (ou une section) |

---

## Détails Techniques

L'application repose sur une architecture simple mais robuste :
*   **Moteur de calcul** : Gestion automatique du calendrier (jours ouvrés, week-ends personnalisables).
*   **Rendu SVG** : Les dépendances et le graphe MPM sont tracés dynamiquement via SVG pour une netteté parfaite quel que soit le zoom.
*   **Zéro Dépendance** : Pas de React, pas de jQuery, pas de Moment.js. Un code pur, rapide et facile à maintenir.

---

## Licence

Ce projet est sous licence Apache 2.0
