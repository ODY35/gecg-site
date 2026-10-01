# GECG website

Site du Gabonese Entrepreneurs Club in Ghana (une seule page : `index.html`).

## Voir hors ligne (VS Code)
1. Dézipper le dossier, puis `File > Open Folder` dans VS Code.
2. Installer l'extension **Live Server**, clic droit sur `index.html` > **Open with Live Server**.
   (Ou simplement double-cliquer sur `index.html` : la page s'ouvre dans le navigateur.)

## Ajouter les vraies photos
- Equipe : les photos sont deja dans `assets/team/`; pour en changer, remplacer le fichier (meme nom).
- Galerie : mettre les images dans `assets/gallery/`, puis ajouter `data-src="assets/gallery/photo1.jpg"` sur chaque bouton `.g`.

## Mettre en ligne sur GitHub Pages
1. Creer un depot sur github.com (ex. `gecg-site`).
2. Dans le dossier : `git init`, `git add .`, `git commit -m "GECG website"`,
   `git branch -M main`, `git remote add origin https://github.com/TON-COMPTE/gecg-site.git`, `git push -u origin main`.
3. GitHub > Settings > Pages > Branch `main` / dossier `/ (root)` > Save.
4. Le site sera sur `https://TON-COMPTE.github.io/gecg-site/`.
5. Domaine gecg.org : l'ajouter dans Pages > Custom domain, puis configurer les DNS.

## Formulaire de contact
Il ouvre l'application mail du visiteur avec le message prerempli vers info@gecg.org.
Pour recevoir les messages directement, brancher un service comme Formspree ou Web3Forms.
