# Registre Immobilier

Application de gestion locative (cours, maisons, loyers, réparations, quittances)
sous forme d'une page web unique et autonome (`index.html`).

## Déploiement sur GitHub Pages

1. Créez un nouveau dépôt sur GitHub (public ou privé).
2. Ajoutez ce fichier `index.html` (et ce `README.md`) à la racine du dépôt,
   puis validez (commit) et poussez (push) sur la branche `main`.
3. Dans le dépôt : **Settings → Pages**.
4. Sous **Build and deployment**, choisissez **Source : Deploy from a branch**,
   puis **Branch : main** et dossier **/ (root)**. Enregistrez.
5. Au bout de 1 à 2 minutes, le site est en ligne à l'adresse :
   `https://<votre-nom-utilisateur>.github.io/<nom-du-depot>/`

## Installation sur téléphone (Android / iOS)

Une fois le site en ligne, ouvrez son adresse dans Chrome (Android) ou Safari
(iPhone), puis :
- **Android (Chrome)** : menu ⋮ → *Installer l'application* (ou *Ajouter à
  l'écran d'accueil*).
- **iPhone (Safari)** : bouton de partage → *Sur l'écran d'accueil*.

## Fonctionnement des données — important

Cette version est **autonome** : elle ne dépend plus de Claude. Les données
(cours, maisons, loyers, réparations, quittances) sont enregistrées dans le
**stockage local du navigateur** utilisé pour ouvrir la page.

Conséquences à connaître :
- Les données restent sur **cet appareil et ce navigateur uniquement** — elles
  ne sont pas partagées automatiquement entre votre téléphone et votre
  ordinateur, par exemple.
- Vider le cache / les données du navigateur, ou désinstaller l'application,
  **efface les données**.
- Pensez à exporter régulièrement vers Excel (bouton en haut de l'application)
  pour conserver une sauvegarde en dehors du navigateur.

## Mettre à jour l'application plus tard

Si vous redemandez des modifications à Claude, vous recevrez un nouveau
fichier `index.html` : il suffit de remplacer l'ancien dans le dépôt GitHub
(commit + push) pour que le site déployé se mette à jour. Vos données
existantes dans le navigateur ne sont pas affectées par ce remplacement.
