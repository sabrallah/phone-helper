# 📱 PhoneHelper Pro — Baromètre Smartphones MarocPhone

Dashboard dynamique officiel consacré aux smartphones neufs scellés et reconditionnés A+ certifiés de [MarocPhone](https://marocphone.com/neuf/smartphones).

> **Données 100% Dynamiques** : Toutes les informations — prix, remises, ruptures, palmarès des meilleures ventes, diagnostics des pannes les plus connues et seuils de rentabilité — sont calculées dynamiquement d'après les technologies embarquées et synchronisées en direct avec MarocPhone.

## 📄 Fonctionnalités

- **🔥 Top Ventes Maroc 2026 (Les plus vendus)** : palmarès dynamique basé sur les volumes réels du marché marocain (Redmi 13C n°1 volume entrée de gamme, Galaxy A17 n°1 ventes Samsung, Note 13/17 Pro, iPhone 13 A+ n°1 reconditionné, S24 Ultra n°1 flagship Android). Chaque modèle intègre un indice de demande, son prix en direct et sa panne n°1.
- **🛠️ Pannes les plus connues & guide atelier dynamique** :
  - Statistiques ventilées automatiquement d'après la part d'écrans OLED/AMOLED (pannes d'écran ~46%), d'appareils A+ et de batteries haute capacité (pannes batterie ~25%), et de charge rapide 67W-120W (nappes USB-C ~18%).
  - Tableau atelier avec diagnostic par smartphone, composant prioritaire à stocker, indice de réparabilité et **seuil de rentabilité calculé en direct à 35% du prix neuf MarocPhone du jour**.
- **🧮 Calculateur de rentabilité réparation** : connecté en direct aux prix MarocPhone. Évalue instantanément si une réparation est rentable pour le client vs rachat d'un smartphone neuf ou A+.
- **Catalogue complet & interactif** : 30 smartphones (22 neufs + 8 reconditionnés A+) avec visuels produits officiels, stockage (Go), RAM, réseau 4G/5G, prix TTC, anciens prix barrés, remises, disponibilité, panne la plus connue et liens directs vers les fiches MarocPhone.
- **Tableau de bord KPI (8 indicateurs)** : volume du catalogue, prix moyen et médian neuf, prix moyen reconditionné A+, écart moyen neuf vs A+, fourchette tarifaire, meilleure remise %, plus grande économie en DH, taux de disponibilité et économies cumulées.
- **📈 Statistiques & distribution du marché** : 3 graphiques Chart.js (répartition par marque, distribution des prix neufs par segment, taux de remise moyen par marque) + barres de gammes et de disponibilité par marque.
- **🔍 Recherche, filtres & double affichage** : filtrage rapide par marque en un clic via pilules, bascule vue Tableau (`☰`) et vue Grille e-commerce (`⊞`).

## ⟳ Synchronisation en direct (1 clic)

Le bouton **Synchroniser en direct** interroge en temps réel les pages officielles de MarocPhone via des proxys CORS haute disponibilité (Jina Reader en priorité, avec formats HTML/DOMParser) et actualise **l'intégralité du dashboard** :

- prix actuels, anciens prix barrés et statuts de disponibilité (en stock / rupture de stock) ;
- détection et intégration automatique de nouveaux smartphones ajoutés au catalogue ;
- recalcul instantané de tous les KPIs, graphiques, barres, classements Top Ventes, diagnostics de pannes et seuils du calculateur.

La dernière synchronisation est automatiquement mise en cache dans le `localStorage` du navigateur pour une restauration instantanée au chargement.

## 🚀 Déploiement

Le projet est hébergé et déployé automatiquement sur **GitHub Pages** via GitHub Actions (`.github/workflows/pages.yml`).
Chaque commit poussé sur la branche `main` déclenche le déploiement.

URL publique : https://sabrallah.github.io/phone-helper/

## ©

sabrallah — sabrallah1991@gmail.com • Données : marocphone.com
