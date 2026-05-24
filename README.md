# Starlink — Internet partout

Page vitrine statique (HTML) pour présenter Starlink : connexion satellite, camping-car, van, habitation, application mobile et installation simple.

## Lien public (GitHub Pages)

Après publication, la page est disponible à :

`https://<votre-identifiant-github>.github.io/starlink-vitrine/`

## Lien de parrainage

Tous les boutons « Commander » pointent vers :

https://starlink.com/residential?referral=RC-DF-11577924-53788-13

Pour modifier le code de parrainage, éditez les URLs dans `index.html`.

## Déploiement GitHub Pages

1. Créez un dépôt public `starlink-vitrine` sur GitHub.
2. Poussez ce dossier (`main`).
3. **Settings → Pages → Build and deployment** : source **Deploy from a branch**, branche **main**, dossier **/ (root)**.
4. Attendez 1–2 minutes ; l’URL ci-dessus sera active.

## Prévisualisation locale

Ouvrez `index.html` dans un navigateur, ou :

```powershell
cd C:\Users\socra\Projects\starlink-vitrine
python -m http.server 8080
```

Puis ouvrez http://localhost:8080
