# inPulse Club

Landing page statique du club HIIT & Fitness **inPulse Club** (Paris 17e).

Site 100 % statique : une seule page (`index.html`), Tailwind CSS chargé via CDN et polices
Google Fonts. Aucune étape de build n'est nécessaire.

## Aperçu en local

```bash
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```

## Déploiement — GitHub Pages

Le site est déployé via **Deploy from a branch** :

1. Pousser sur la branche `main`.
2. Dépôt → **Settings → Pages** → *Build and deployment* → Source : **Deploy from a branch**
   → Branch : `main` / `/ (root)` → **Save**.

Le site est alors servi sur `https://<username>.github.io/<repo>/` (comptez 1 à 2 min pour le
premier déploiement).

Le fichier `.nojekyll` désactive le traitement Jekyll et garantit que tous les fichiers sont
servis tels quels.
