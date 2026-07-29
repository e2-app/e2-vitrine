# e2-vitrine

Page d'accueil (vitrine d'aiguillage) du domaine racine **enqueteseducatives.com**.

Point d'entrée statique vers les espaces par public :
- **Scolaire** (actif) → `https://scolaire.enqueteseducatives.com`
- **Entreprise** (à venir, autre serveur)

Associations / Particuliers : reportés (post-décembre 2026), à réintroduire comme
cartes `.soon` dans `index.html` le moment venu.

## Contenu
- `index.html` — page unique, autonome (aucun appel externe, conforme CSP/RGPD).
- `assets/fonts/InterVariable.woff2` — police Inter auto-hébergée (SIL Open Font License).

## Déploiement
Ressource **Coolify** de type *Application* (Git Based), **Build Pack = Static**,
rattachée au domaine apex `enqueteseducatives.com`. Voir §32 du document de référence.
