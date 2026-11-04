# 📱 PhoneHelper Pro — Baromètre Smartphones MarocPhone

Dashboard dynamique officiel consacré aux smartphones neufs scellés et reconditionnés A+ certifiés de [MarocPhone](https://marocphone.com/neuf/smartphones).

> **Objectif 100% Dynamique** : Toutes les métriques affichées sont calculées en direct et sourcées exclusivement depuis MarocPhone. Aucune donnée éditoriale, spéculative ou statique (guides techniciens ou estimations de pannes fictives supprimés).

## 📄 Fonctionnalités

- **Catalogue complet & interactif** : 30 smartphones (22 neufs + 8 reconditionnés A+) avec visuels produits officiels, stockage (Go), RAM, réseau 4G/5G, prix TTC, anciens prix barrés, remises (DH et %), disponibilité en stock et liens directs vers les fiches MarocPhone.
- **Tableau de bord KPI (8 indicateurs)** : volume du catalogue, prix moyen et médian neuf, prix moyen reconditionné A+, écart moyen neuf vs A+, fourchette tarifaire, meilleure remise %, plus grande économie en DH, taux de disponibilité en stock et économies cumulées au catalogue.
- **📈 Statistiques & distribution du marché** : 3 graphiques Chart.js (répartition par marque, distribution des prix neufs par segment, taux de remise moyen par marque) + barres de répartition des gammes et taux de disponibilité par marque.
- **🏷️ Insights quantitatifs en temps réel** : promotions actives, état des ruptures de stock nominatives, comparatif de décote Neuf vs Reconditionné A+ et capacités de stockage dominantes.
- **🧮 Simulateur de prix & analyseur d'économies** : analyse individuelle de chaque smartphone, ratio Prix / Go, test d'adéquation au budget et vérification de disponibilité.
- **🔥 Top Bonnes Affaires & Opportunités** : classements dynamiques par plus forte remise (%), plus grande économie (DH), petits prix (< 2 000 DH) et nouveautés 2026.
- **🔍 Recherche, filtres & tri instantanés** : par mot-clé, par état (neuf / A+), par marque, par disponibilité (en stock / rupture) et par critères de prix ou d'économie.

## ⟳ Synchronisation en direct (1 clic)

Le bouton **Synchroniser en direct** interroge en temps réel les pages officielles de MarocPhone via des proxys CORS haute disponibilité (Jina Reader en priorité, avec formats HTML/DOMParser) et actualise **l'intégralité du dashboard** :

- prix actuels, anciens prix barrés et statuts de disponibilité (en stock / rupture de stock) ;
- détection et intégration automatique de nouveaux smartphones ajoutés au catalogue ;
- recalcul instantané de tous les KPIs, graphiques, barres, classements et simulateur.

La dernière synchronisation est automatiquement mise en cache dans le `localStorage` du navigateur pour une restauration instantanée au chargement.

## 🚀 Déploiement

Le projet est hébergé et déployé automatiquement sur **GitHub Pages** via GitHub Actions (`.github/workflows/pages.yml`).
Chaque commit poussé sur la branche `main` déclenche le déploiement.

URL publique : https://sabrallah.github.io/phone-helper/

## ©

sabrallah — sabrallah1991@gmail.com • Données : marocphone.com
