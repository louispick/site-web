# L'Attrape-Rêves - Parc d'émerveillement

Site web multilingue pour le parc d'émerveillement L'Attrape-Rêves situé à Gravières, Ardèche.

## 🌍 Versions linguistiques

Le site est disponible en trois langues :

- 🇫🇷 **Français** (par défaut) : [https://attrape-reves.pages.dev](https://attrape-reves.pages.dev)
- 🇬🇧 **English** : [https://attrape-reves.pages.dev/en/](https://attrape-reves.pages.dev/en/)
- 🇳🇱 **Nederlands** : [https://attrape-reves.pages.dev/nl/](https://attrape-reves.pages.dev/nl/)

## 📁 Structure du projet

```
.
├── index.html          # Version française (page principale)
├── en/
│   └── index.html     # Version anglaise
├── nl/
│   └── index.html     # Version néerlandaise
├── _redirects         # Redirections Cloudflare Pages
└── wrangler.toml      # Configuration Cloudflare
```

## 🚀 Déploiement

Le site est déployé automatiquement sur **Cloudflare Pages** depuis la branche `main` du dépôt GitHub.

### Commande de déploiement manuel

```bash
wrangler pages deploy . --project-name=attrape-reves --branch=main
```

## 🎨 Caractéristiques

- ✅ Design responsive (mobile, tablette, desktop)
- ✅ Navigation multilingue avec sélecteur de langue
- ✅ Carrousels d'images interactifs
- ✅ Animations fluides
- ✅ Menu mobile
- ✅ Effet glassmorphism
- ✅ Performance optimisée

## 📞 Contact

- **Email** : lattrapereves@mailo.com
- **Adresse** : 514 chemin de la Vernède, 07140 Gravières, Ardèche
- **Facebook** : [lattrapereves07](https://www.facebook.com/lattrapereves07)
- **Instagram** : [@lattrapereves07](https://www.instagram.com/lattrapereves07)

## 🗓️ Ouverture

Le parc ouvrira ses portes en **2026**. Suivez-nous sur les réseaux sociaux pour rester informés !

## 🛠️ Technologies utilisées

- HTML5
- TailwindCSS (via CDN)
- Vanilla JavaScript
- Cloudflare Pages
- Wrangler CLI

## 📝 Licence

© 2025 L'Attrape-Rêves. Tous droits réservés.
