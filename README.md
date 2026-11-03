# SunuButik & NABOU AI 🇸🇳

> **SunuButik** est une plateforme e-commerce locale conçue pour le Sénégal, propulsée par **NABOU AI**, une assistante intelligente bilingue (Wolof/Français) intégrée via l'API Meta Llama.

---

## 🚀 À propos du projet
Développé dans le cadre du **Meta Global AI Developer Hackathon 2026**, SunuButik s'attaque à un défi majeur du commerce de proximité à Diourbel et au Sénégal : la double barrière numérique et linguistique. De nombreux commerçants locaux et clients communiquent principalement en wolof, ce qui rend les solutions e-commerce classiques inadaptées.

### 🌟 Fonctionnalités Clés
* **Assistant bilingue NABOU :** Permet aux utilisateurs d'interagir naturellement en wolof et en français pour rechercher des produits ou négocier.
* **Mise en relation locale :** Connecte directement les clients, les commerçants de quartier et les livreurs.
* **Recherche contextuelle :** Permet de trouver rapidement les boutiques les plus proches proposant le meilleur prix.

---

## 🛠️ Architecture Technique
* **Frontend :** Flutter (application mobile multiplateforme)
* **Backend :** Python avec **FastAPI** pour une gestion rapide et asynchrone des requêtes.
* **Intelligence Artificielle :** Intégration de l'API Meta Llama pour propulser les capacités de traitement bilingue de NABOU.
* **Base de données / Sécurité :** PostgreSQL, authentification JWT.

---

## 📂 Structure du Dépôt
```text
sunubutik-nabou-ai/
│
├── backend/          # API FastAPI en Python & logique IA (Meta Llama)
├── mobile/           # Application Flutter (UI, parcours client/commerçant)
├── docs/             # Documentation technique et maquettes
└── README.md         # Documentation du projet
