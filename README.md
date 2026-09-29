# ABENE HOST

Simulation locale d’interface hôtelière inspirée des menus et fenêtres visibles dans Host PMS. L’interface est en portugais pour rester cohérente avec le logiciel de référence.

Ouvrir `index.html` dans un navigateur récent. Aucun serveur ni installation ne sont nécessaires.

Fichiers : `index.html` (structure), `styles.css` (design responsive), `app.js` (navigation et interactions).

La simulation comprend les rubriques observées : Reserva, Front Desk, Contas, Gestão de Canais, Marketing, Reporting et Utilitários. Les listes, indicateurs, réservations, chambres et contacts utilisent exclusivement des exemples fictifs.

Les menus, fenêtres, onglets, raccourcis, recherche globale, filtres, dates, tri, pagination, formulaires, modification d’une réservation, attribution locale d’une chambre, état d’un enregistrement, export CSV et annulation locale sont interactifs. Les exemples créés ou modifiés sont conservés dans le stockage local du navigateur. Une annulation dans la simulation demande une confirmation explicite.

Cette simulation est indépendante de l’adresse Host PMS. Elle ne se connecte pas au PMS et aucune action de la simulation ne crée, ne modifie ou n’annule une réservation réelle. Les exports contiennent uniquement les données fictives de la maquette.

`index.html` est autonome : le style et le script y sont intégrés. Vous pouvez copier ce seul fichier et l’ouvrir sans `styles.css` ni `app.js`. Ces deux fichiers restent dans le dossier comme sources séparées pour faciliter les modifications; ils ne sont ni supprimés ni nécessaires à l’ouverture de l’index autonome.

Ajouts : accueil type bureau bleu, fenêtre complète de création de réservation, fiche de réservation fictive déjà en Check-Out en mode lecture seule, navigation détaillée du menu Check-Out et indicateurs d’état hôtel cliquables. Toutes ces vues fonctionnent localement avec des données fictives; elles ne communiquent pas avec le PMS réel.