# StudyFlow

Application étudiante statique, compatible avec GitHub Pages.

## Publication sur GitHub Pages
1. Créez un dépôt GitHub public (ou privé si votre offre autorise Pages).
2. Envoyez le fichier `index.html` à la racine du dépôt.
3. Dans **Settings > Pages > Build and deployment**, choisissez **Deploy from a branch**, branche **main**, dossier **/(root)**, puis **Save**.
4. Ouvrez l'adresse GitHub Pages fournie par GitHub après le déploiement.

## Fonctionnalités
- Tableau de bord et indicateurs
- CRUD tâches, contacts, messages et notes
- Cases à cocher, priorités, dates et recherche
- Export/import JSON
- Stockage local du navigateur (`localStorage`)
- Lien Outlook et liens `mailto:`

## Important
Ce site ne lit pas automatiquement la boîte Outlook. Une intégration Microsoft Graph nécessiterait une authentification Microsoft (OAuth), des permissions et une configuration Entra ID, parfois soumise à l'approbation de l'établissement.

Les données ne sont pas synchronisées entre appareils et peuvent disparaître si le stockage du navigateur est effacé. Évitez de saisir des informations sensibles sur un appareil partagé. Effectuez régulièrement un export JSON.
