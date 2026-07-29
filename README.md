# Sèvres — date et météo

Petite page statique affichant la date du jour et un relevé météo pour Sèvres (92310, Hauts-de-Seine, France).

- La date et l'heure sont mises à jour en direct dans le navigateur.
- La météo (`index.html`) est un instantané pris au moment de la génération de la page, via [Open-Meteo](https://open-meteo.com) — la page n'appelle aucune API au chargement.

## Aperçu local

Ouvrez `index.html` dans un navigateur, ou servez le dossier :

```sh
python3 -m http.server -d . 8000
```

## Publication (GitHub Pages)

1. Poussez ce dépôt sur GitHub.
2. Dans **Settings → Pages**, choisissez la branche `main` et le dossier `/` (root).
3. La page sera servie à `https://<utilisateur>.github.io/sevres/`.
