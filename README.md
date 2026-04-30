# Portfolio statique — Théo Andre

Version ultra simple pour GitHub Pages en mode **Deploy from a branch**.

## Déploiement sans npm

1. Dézippe ce dossier.
2. Upload **tout le contenu** à la racine du repo GitHub `portfolio-t`.
3. Va dans `Settings > Pages`.
4. Choisis :
   - Source : `Deploy from a branch`
   - Branch : `main`
   - Folder : `/ (root)`
5. Sauvegarde.

URL attendue : `https://toxatiger.github.io/portfolio-t/`

## Modifier le portfolio

Tout est dans `index.html` : textes, projets, compétences, liens, documents.
Les fichiers PDF/JPEG/XLSX sont dans `fichiers/`.

Aucun `npm install`, aucun build, aucune GitHub Action nécessaire.
