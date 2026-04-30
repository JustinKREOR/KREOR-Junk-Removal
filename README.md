# KREOR Junk Removal

Site web officiel de KREOR Junk Removal — service de débarras et collecte de déchets.

## Structure

- `index.html` — page d'accueil (copie de `landing.html`)
- `landing.html` — page d'atterrissage principale
- `conditions-utilisation.html` — conditions d'utilisation (FR)
- `politique-confidentialite.html` — politique de confidentialité (FR)
- `politique-cookies.html` — politique de cookies (FR)
- `privacy.html` — privacy policy (EN)
- `assets/` — images et logos

## Déploiement

Le site est déployé sur Vercel. Tout push vers la branche `main` déclenche un nouveau déploiement automatique si le repo est lié à Vercel.

## Développement local

Le site est statique (HTML + CSS + JS via React UMD). Pour le tester localement:

```bash
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```
