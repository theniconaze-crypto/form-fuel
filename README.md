# Form & Fuel — Coach Nutrition & Musculation

Outil web autonome (HTML/CSS/JS, aucune dépendance serveur) pour générer un plan nutrition + musculation personnalisé, avec suivi de poids/mensurations et export PDF.

## Mise en ligne avec GitHub Pages

1. Crée un nouveau dépôt GitHub (ou utilise un dépôt existant).
2. Glisse-dépose les fichiers de ce dossier (`index.html` et `.nojekyll`) à la racine du dépôt — via l'interface web GitHub ("Add file" → "Upload files").
3. Valide le commit (bouton "Commit changes").
4. Va dans **Settings → Pages**.
5. Dans "Build and deployment", choisis **Source : Deploy from a branch**, branche `main`, dossier `/ (root)`.
6. Sauvegarde. Après 1-2 minutes, l'outil est accessible à une adresse du type :
   `https://<ton-nom-utilisateur>.github.io/<nom-du-depot>/`

## Notes

- Toutes les données (profils, historique de poids/mensurations) sont sauvegardées **localement dans le navigateur** (localStorage) — rien n'est envoyé sur un serveur. Chaque appareil/navigateur a donc son propre stockage.
- L'export PDF utilise la fonction d'impression native du navigateur (bouton "Imprimer / Exporter en PDF" → choisir "Enregistrer au format PDF" ou, sur iPhone/iPad, utiliser l'icône de partage dans l'aperçu d'impression).
- Le fichier `.nojekyll` évite que GitHub Pages n'applique un traitement Jekyll inutile au fichier.
