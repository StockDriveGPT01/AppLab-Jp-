# AppLab JP V15.4 — Paquet complet prêt pour GitHub Pages

**Application :** AppLab JP — Les outils numériques du Jardinier Paysagiste  
**Version :** 15.4.0 (mini-pelle après 2 minutes d'inactivité)  
**Plateformes :** iPhone/iPad, Android, Windows/macOS via PWA  

## Installation sur le compte GitHub StockDriveGPT01

1. Se connecter à GitHub avec **StockDriveGPT01**.
2. Ouvrir **https://github.com/new**.
3. Choisir le compte propriétaire **StockDriveGPT01** et nommer le dépôt **AppLab-Jp**. Cocher **Public**, puis créer le dépôt.
4. Dans le nouveau dépôt, ouvrir **Add file > Upload files** (ou **uploading an existing file** sur la page vide).
5. **Décompresser ce ZIP sur l'ordinateur.** Sur GitHub, glisser le CONTENU décompressé, pas le fichier ZIP lui-même : `index.html`, `service-worker.js`, `release.json`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `.nojekyll`, et éventuellement les guides.
6. Valider en cliquant sur **Commit changes**.
7. Ouvrir **Settings > Pages**, sélectionner **Deploy from a branch**, puis **main** et **/(root)**, et enregistrer.
8. Dans **Actions**, attendre que `pages build and deployment` réussisse.
9. Adresse attendue : **https://stockdrivegpt01.github.io/AppLab-Jp/** (à vérifier dans Settings > Pages).
10. Installer la PWA depuis le navigateur de chaque appareil : Chrome/Edge (menu Installation), Safari iPhone (Partager > Sur l'écran d'accueil).

IMPORTANT : si vous utilisez **Import repository** à la place de l'import de fichiers, l'URL du dépôt source est :
https://github.com/jchaffanjon07-lang/AppLab-Jp.git
N'UTILISEZ PAS https://jchaffanjon07-lang.github.io/AppLab-Jp/ comme URL source de clonage : c'est une adresse de site et non un dépôt Git.

## Conservation des utilisateurs déjà installés

Le déplacement vers un autre propriétaire GitHub change l'adresse d'origine du stockage. Les installations existantes provenant du site `jchaffanjon07-lang.github.io` ne recevront PAS automatiquement les mises à jour de `stockdrivegpt01.github.io`. Les données locales ne migrent pas automatiquement entre ces adresses. Ne pas supprimer l'ancien dépôt tant que ces utilisateurs n'ont pas été informés et leurs configurations éventuellement sauvegardées.

## Mises à jour ultérieures

- Conserver la même URL pour les utilisateurs du nouveau dépôt.
- Mettre à jour `index.html`, `service-worker.js`, `release.json` et leur numéro de version.
- Conserver `manifest.webmanifest` et les icônes tant qu'ils ne changent pas.
- Ne jamais effacer les données du site ou les applications personnelles des Coteries sans leur accord.

## Contenu de l'archive

- `index.html` : application complète, avec les images officielles intégrées.
- `service-worker.js` : gestion PWA, cache, hors ligne et mises à jour.
- `manifest.webmanifest` : identité de l'application installable.
- `release.json` : numéro et nouveautés de version.
- `icon-192.png`, `icon-512.png` : icônes officielles.
- `.nojekyll` : publication GitHub Pages en mode fichiers statiques.
- `README.md` et `LISEZ_MOI_EN_PREMIER.txt` : aide à la mise en ligne.
- `DOCUMENTATION/` : guide pédagogique illustré (PDF et Word, facultatifs pour l'exécution de la PWA).

## État des fonctionnalités

La V15.4 conserve les 4 applications officielles NOMAD PAGE, TERAPAGE, SKILLSPAGE et AUTO PAGE, l'Atelier, les applications personnelles, la spirale mobile A, l'animation graine vers arbre, le filigrane ARTI.Lab et les mises à jour. Nouveauté : mini-pelle animée après 120 secondes d'inactivité. Aucune fonction de contact, proposition d'application officielle, organigramme ou MAQUETTE LAB n'est ajoutée.
