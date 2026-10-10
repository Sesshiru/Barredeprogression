# Mes crédits

Petite app pour suivre tes crédits en cours avec des barres de progression vertes.
Elle s'installe sur ton téléphone comme une vraie app et marche aussi hors connexion.

## Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | L'app elle-même |
| `manifest.json` | Nom, couleur et icône de l'app installée |
| `sw.js` | Permet l'ouverture hors connexion |
| `icon-192.png`, `icon-512.png` | Icônes Android |
| `apple-touch-icon.png` | Icône iPhone |

## 1. Mettre l'app sur GitHub

1. Va sur https://github.com/new
2. Nom du dépôt : `mes-credits`, coche **Public**, puis **Create repository**.
3. Sur la page du dépôt, clique sur **uploading an existing file**.
4. Glisse les 6 fichiers (pas le dossier, les fichiers eux-mêmes), puis **Commit changes**.

## 2. Activer GitHub Pages

1. Dans le dépôt : **Settings** → **Pages** (menu de gauche).
2. Sous **Branch**, choisis `main` et le dossier `/ (root)`, puis **Save**.
3. Attends 1 à 2 minutes. Ton app est en ligne à l'adresse :
   `https://TON-PSEUDO.github.io/mes-credits/`

## 3. L'installer sur ton téléphone

**iPhone (Safari obligatoire)**
1. Ouvre l'adresse dans Safari.
2. Bouton **Partager** (carré avec une flèche) → **Sur l'écran d'accueil** → **Ajouter**.

**Android (Chrome)**
1. Ouvre l'adresse dans Chrome.
2. Menu **⋮** → **Installer l'application** (ou **Ajouter à l'écran d'accueil**).

L'icône verte « Crédits » apparaît. L'app s'ouvre en plein écran, sans barre de navigateur.

## À savoir

- Tes crédits sont enregistrés **sur le téléphone**, dans l'app installée. Ils ne sont pas envoyés sur GitHub ni ailleurs. Rien de personnel n'est donc public, même si le dépôt l'est.
- Si tu désinstalles l'app ou vides les données du navigateur, tes crédits sont effacés.
- Pour mettre à jour l'app : remplace `index.html` sur GitHub, et augmente le numéro dans `sw.js` (`mes-credits-v1` → `mes-credits-v2`). Ferme et rouvre l'app deux fois pour voir la nouvelle version.
