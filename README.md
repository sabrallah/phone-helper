# 📱 PhoneHelper Pro — Baromètre smartphones Maroc

Dashboard HTML autonome consacré aux smartphones neufs et reconditionnés A+ de [MarocPhone](https://marocphone.com/neuf/smartphones).

## 📄 Contenu

- **Catalogue complet** : 30 modèles (22 neufs + 8 reconditionnés A+) avec prix, anciens prix, remises, disponibilité et liens produits
- **Dashboard KPI** : prix moyens neuf/A+, fourchette, meilleure remise, ruptures, marques
- **📈 Statistiques marché** : 3 graphiques Chart.js (marques, distribution des prix, remises) + barres de gammes et taux de pannes
- **🔥 Top ventes Maroc 2026** : 10 neufs + 2 reconditionnés A+
- **🛠️ Guide technicien** : stock prioritaire, pannes fréquentes, seuils de rentabilité, check-list imprimable
- **🧮 Calculateur de rentabilité** : verdict immédiat selon le prix neuf, la pièce et la main d'œuvre

## ⟳ Mise à jour en 1 clic

Le bouton **Mise à jour** importe les données de MarocPhone via des proxys CORS (Jina Reader + secours) et actualise **toute la page** :

- prix actuels, anciens prix barrés et statut rupture / prix sur demande ;
- nouveaux produits éventuels ajoutés au catalogue ;
- KPIs, insights, barres, graphiques, Top ventes, tableau technicien, calculateur et catalogue.

La dernière synchronisation est conservée dans le `localStorage` du navigateur.

## 🚀 Déploiement

Le repo est déployé automatiquement sur **GitHub Pages** via GitHub Actions (`.github/workflows/pages.yml`).
Chaque push sur `main` déclenche un nouveau déploiement.

URL publique : https://sabrallah.github.io/phone-helper/

> Le fichier principal est `index.html` à la racine du repo.

## ©

sabrallah — sabrallah1991@gmail.com
