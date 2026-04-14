# SWPlan — Plan de Switch Réseau

Outil de planification visuelle pour switches réseau. Configurez vos VLANs, assignez des ports (access, tagged, trunk), créez des agrégats LACP et exportez votre plan en PNG ou PDF.

**Démo en ligne :** [swplan.antoninpomies.fr](https://swplan.antoninpomies.fr)

---

## Installation locale

Aucune installation requise. Le projet est un fichier HTML autonome.

1. Téléchargez `index.html`
2. Ouvrez-le dans votre navigateur

> Une connexion internet est nécessaire au premier chargement pour récupérer les dépendances (Tailwind CSS, html2canvas, jsPDF via CDN).

---

## Fonctionnalités

- Modèles de switch : 8, 16, 24, 48 ports avec ports SFP
- Création et gestion de VLANs (ID, nom, couleur, description)
- Modes de port : Untagged (U), Tagged (T), Trunk + VLAN natif
- Agrégats LACP / LAG
- Export PNG et PDF avec légende complète
- Sauvegarde / chargement de configuration (JSON)
- Mode sombre
- Undo / Redo

---

---

# SWPlan — Network Switch Planner

Visual planning tool for network switches. Configure VLANs, assign ports (access, tagged, trunk), create LACP aggregates and export your plan as PNG or PDF.

**Live demo:** [swplan.antoninpomies.fr](https://swplan.antoninpomies.fr)

---

## Local installation

No installation required. The project is a standalone HTML file.

1. Download `index.html`
2. Open it in your browser

> An internet connection is required on first load to fetch dependencies (Tailwind CSS, html2canvas, jsPDF via CDN).

---

## Features

- Switch models: 8, 16, 24, 48 ports with SFP ports
- VLAN creation and management (ID, name, color, description)
- Port modes: Untagged (U), Tagged (T), Trunk + native VLAN
- LACP / LAG aggregates
- PNG and PDF export with full legend
- Configuration save / load (JSON)
- Dark mode
- Undo / Redo
