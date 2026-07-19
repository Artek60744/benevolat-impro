# Lamia Zegrir — Site vitrine

Site vitrine statique de **Lamia Zegrir**, consultante freelance en stratégie de
communication et conduite du changement (Paris · remote & hybride).

Site 100 % statique : une seule page (`index.html`), Tailwind CSS chargé via CDN et polices
Google Fonts. Aucune étape de build n'est nécessaire.

## Structure de la page

Hero → L'enjeu → Accompagnements (services) → Ma méthode → Réalisations → À propos →
Repères (preuve sociale) → Contact.

## Aperçu en local

```bash
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```

## À compléter

- **Images** : les 4 visuels sont des placeholders (voir les commentaires `TODO` dans
  `index.html`). Remplacer notamment celui de la section « À propos » par la photo pro.
- **Liens** : LinkedIn, mentions légales et politique de confidentialité pointent vers `#`.

## Déploiement — GitHub Pages

Le site est déployé via **Deploy from a branch** :

1. Pousser sur la branche `main`.
2. Dépôt → **Settings → Pages** → *Build and deployment* → Source : **Deploy from a branch**
   → Branch : `main` / `/ (root)` → **Save**.

Le site est alors servi sur `https://<username>.github.io/<repo>/` (comptez 1 à 2 min pour le
premier déploiement).

Le fichier `.nojekyll` désactive le traitement Jekyll et garantit que tous les fichiers sont
servis tels quels.
