# Planner 12+1 — v2.6 (GitHub Pages Ready)

Ce dossier est prêt pour un déploiement **sans Terminal** via l’interface web de GitHub.
Voir les étapes dans ce README une fois que tu as créé un dépôt vide.

## Étapes (interface web)
1) Crée un dépôt public (ex: `planner12`) sur GitHub.
2) Clique **Add file → Upload files**.
3) **Dézippe** ce fichier sur ton ordi et **glisse-dépose le contenu** dans la page d’upload
   (tu peux glisser-d&eacute;poser des **dossiers** entiers comme `icons/`).
4) Clique **Commit changes**.
5) Va dans **Settings → Pages** → Source: *Deploy from a branch* / Branch: `main` `/ (root)` → **Save**.
6) Attends 1–2 min, l’URL ressemblera à `https://TON_UTILISATEUR.github.io/TON_DEPOT/`.

## Fichiers importants
- `index.html` : page principale
- `manifest.webmanifest` : PWA
- `service-worker.js` : cache hors-ligne de base
- `icons/` : icônes PWA
- `.nojekyll` : empêche Jekyll d’ignorer certains fichiers

Bon déploiement !
