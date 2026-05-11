# VoyaDZ — Site web officiel

> Voyages organisés premium depuis Alger 🇩🇿
> Asie · Égypte · Turquie · Omra · Combinés · Algérie

## 🌐 Site en ligne

- **Production :** https://voyadz.com (à venir)
- **Preview :** https://voyadz.netlify.app

## 📂 Structure du projet

```
voyadz-website/
├── index.html              # Page d'accueil
├── vietnam.html            # Produit officiel : Vietnam Summer 2026
├── images/                 # Photos des destinations (à ajouter)
│   ├── vietnam.jpg
│   ├── hochiminh.jpg
│   ├── hoian.jpg
│   ├── hanoi.jpg
│   ├── ninh.jpg
│   ├── halong.jpg
│   ├── hotel1.jpg → hotel5.jpg
│   ├── malaisie-vietnam.jpg
│   ├── kuala-omra.jpg
│   └── sharm-cairo.jpg
└── README.md
```

## 🎨 Identité visuelle

### Palette officielle — Bleu Profond Premium

| Couleur | Usage | Hex |
|---------|-------|-----|
| Navy Profond | Base principale | `#0F2347` |
| Royal Blue | Hover et accents | `#1E40AF` |
| Sky Bright | Accent moderne | `#0EA5E9` |
| Cloud White | Fond léger | `#FAFBFC` |
| Amber Gold | Premium / promos | `#F59E0B` |

### Typographie

- **Inter** (sans-serif moderne) : tous les textes courants, navigation, CTAs
- **Playfair Display** (serif italique) : titres éditoriaux, accents émotionnels

## 🚀 Déploiement Netlify

### Méthode 1 : Connecter le repo GitHub à Netlify (recommandé)

1. Va sur [netlify.com](https://app.netlify.com) → "Add new site" → "Import an existing project"
2. Connecte ton compte GitHub
3. Sélectionne le repo `voyadz-website`
4. Build settings : **rien à configurer** (site statique)
5. Clique "Deploy"
6. Le site est en ligne en 2 minutes sur `https://voyadz.netlify.app`

### Méthode 2 : Drag & Drop

1. Zippe le dossier complet
2. Va sur [app.netlify.com/drop](https://app.netlify.com/drop)
3. Glisse le ZIP dans la zone

## 📨 Formulaire de réservation

Le formulaire Vietnam utilise **Netlify Forms** (gratuit jusqu'à 100 leads/mois).

- ✅ Aucune configuration requise après le déploiement
- ✅ Notification email automatique à chaque nouveau lead
- ✅ Dashboard Netlify pour gérer les réservations
- ✅ Anti-spam intégré (honeypot bot-field)
- ✅ Référence unique générée automatiquement (format VTN-DDMM-XXXX)

### Voir les leads
1. Connecte-toi à Netlify
2. Va dans le site VoyaDZ → onglet "Forms"
3. Tu verras toutes les soumissions du formulaire `reservation-vietnam`

### Configurer les notifications email
1. Settings → Forms → Form notifications
2. Ajoute ton email (ou celui de Stef)
3. À chaque nouveau lead → email instantané avec tous les détails

## 🔧 À configurer après déploiement

- [ ] Remplacer `213XXXXXXXXX` par le vrai numéro WhatsApp de Voya DZ
- [ ] Ajouter les vraies photos dans `/images/`
- [ ] Configurer les notifications email Netlify Forms
- [ ] Brancher un nom de domaine personnalisé (ex: `voyadz.com`)
- [ ] Ajouter Google Analytics pour tracker les visiteurs

## 📞 Numéro WhatsApp

À remplacer dans tous les fichiers HTML :
- Recherche : `213XXXXXXXXX`
- Remplace par : ton vrai numéro (format international sans +)

## 📋 Produits

### ✅ Disponible maintenant
- 🇻🇳 **Vietnam Summer 2026** (12J/11N · Qatar Airways · 449k DA)

### ⏳ Prochainement (overlay "BIENTÔT")
- 🇲🇾🇻🇳 Combiné Malaisie + Vietnam (Kuala + Phu Quoc + Hanoi + Croisière)
- 🇲🇾🕋 Kuala + Langkawi + Omra au retour
- 🇪🇬 Sharm El Sheikh + Le Caire

## 🛠️ Support technique

Pour toute modification du site, contacter l'équipe technique.

---

© 2026 VoyaDZ · Tous droits réservés
