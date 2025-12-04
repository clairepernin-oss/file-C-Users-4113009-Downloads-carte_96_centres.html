# Carte — centres

But : page HTML affichant des centres (markers Leaflet) — préparation pour publication via GitHub Pages.

Contenu ajouté dans la branche `publish-prep` :
- `index.html` : version nettoyée et prête à publier (les markers détaillés ont été retirés en attendant validation finale).
- `LICENSE` : licence pour le code (MIT).
- `DATA_LICENSE.md` : proposition de licence pour les données (CC BY 4.0).
- `PII_SCAN.md` : rapport de scan automatique pour détection de données personnelles / secrets.

Instructions pour visualisation locale :
1. Cloner le dépôt et basculer sur la branche `publish-prep` :
   git clone https://github.com/clairepernin-oss/file-C-Users-4113009-Downloads-carte_96_centres.html.git
   git checkout publish-prep
2. Ouvrir `index.html` dans un navigateur (double-clic) ou servir depuis un serveur local (p.ex. `python -m http.server 8000`).
3. Pour publier via GitHub Pages : dans les paramètres du dépôt, activez Pages en pointant sur la branche `publish-prep` (ou fusionnez en `main`/`gh-pages` selon votre workflow).

Attributions :
- Tuiles : OpenStreetMap (attribution incluse).
- Librairies : Leaflet, Leaflet.markercluster, Leaflet.awesome-markers, jQuery, Bootstrap, FontAwesome (CDN).

Avant publication finale :
- Confirmer que vous avez le droit de republier les données (licenses/provenance).
- Valider la licence choisie pour le code et pour les données.
- Confirmer si vous souhaitez que j'insère les markers originaux dans `index.html` (après anonymisation si nécessaire).