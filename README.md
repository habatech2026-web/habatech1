<div align="center">

# ⚡ HABATECH

### Infrastructure Télécoms · Fibre Optique · Starlink · Zone Wi-Fi · Création Digitale

[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR_BADGE_ID/deploy-status)](https://app.netlify.com/sites/habatech/deploys)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white)

**Site vitrine professionnel de HABATECH — Conakry, République de Guinée 🇬🇳**

[🌐 Voir le site](#) · [📞 Contacter](#contact) · [🐛 Signaler un bug](../../issues) · [✨ Proposer une amélioration](../../issues)

</div>

---

## 📋 Sommaire

- [À Propos](#-à-propos)
- [Fonctionnalités](#-fonctionnalités)
- [Structure du Projet](#-structure-du-projet)
- [Déploiement](#-déploiement)
- [Configuration GitHub Actions](#-configuration-github-actions)
- [Contact](#-contact)

---

## 🏢 À Propos

**HABATECH** est une entreprise guinéenne spécialisée dans :

| Service | Description |
|---|---|
| 🔵 **Fibre Optique** | FTTH, FTTO, soudure fusion, certification OTDR |
| 🛰️ **Starlink** | Installation, configuration, maintenance satellite |
| 📡 **Zone Wi-Fi** | Hotspot, réseau mesh, portail captif |
| 🔌 **Câblage Réseau** | Infrastructure structurée Cat6A, baies 19" |
| 📷 **Vidéosurveillance** | Systèmes IP 4K, NVR, contrôle d'accès |
| 🛡️ **Cybersécurité** | Firewall, VPN, audit de sécurité |
| 🌐 **Création Digitale** | Sites web, apps mobile, branding, marketing |

**CEO :** Mr. HONORIS HABA

---

## ✨ Fonctionnalités

- 🌌 **Canvas animé interactif** — réseau de particules réactif à la souris
- ⌨️ **Effet typing dynamique** — animation de texte dans le hero
- 📱 **Responsive complet** — mobile (360px) → desktop (1440px+)
- ⚡ **Performance optimisée** — images JPG progressives (−92% de poids)
- 🎨 **Design futuriste** — thème cyber dark avec accents cyan/gold
- 🔄 **Scroll reveal** — animations d'apparition au défilement
- 🍔 **Navigation burger** — menu mobile fluide
- 📊 **Barres de progression** — pour la section Technologies
- 📝 **Formulaire de contact** — avec validation et feedback visuel
- 🔒 **Headers sécurité** — X-Frame, XSS, CSP via Netlify

---

## 📁 Structure du Projet

```
habatech/
│
├── 📄 index.html              # Page principale (HTML sémantique)
│
├── 🎨 css/
│   └── style.css              # Styles complets + responsive breakpoints
│
├── ⚡ js/
│   └── main.js                # Canvas, animations, interactions
│
├── 🖼️ assets/
│   ├── ceo-outdoor.jpg        # Mr. HONORIS HABA — site industriel
│   ├── ceo-outdoor2.jpg       # Mr. HONORIS HABA — variante
│   ├── ceo-datacenter.jpg     # Mr. HONORIS HABA — salle serveurs
│   ├── rack-cables.jpg        # Baie réseau fibre optique
│   ├── tech-rack.jpg          # Technicien câblage rack
│   ├── tech-work.jpg          # Technicien en intervention
│   └── network-diagram.jpg    # Architecture réseau LAN entreprise
│
├── 🚀 .github/
│   └── workflows/
│       └── deploy.yml         # CI/CD → auto-deploy vers Netlify
│
├── ⚙️ netlify.toml             # Config Netlify (cache, headers, redirects)
├── 🚫 .gitignore              # Fichiers exclus du repo
└── 📖 README.md               # Ce fichier
```

---

## 🚀 Déploiement

### Option 1 — GitHub + Netlify (recommandé)

Connexion automatique GitHub → Netlify :

1. **Fork** ou clonez ce repository
2. Sur [Netlify](https://app.netlify.com) → **"Add new site"** → **"Import an existing project"**
3. Connectez votre compte **GitHub** et sélectionnez ce repo
4. Paramètres de build :
   - **Build command :** *(laisser vide)*
   - **Publish directory :** `.`
5. Cliquez **"Deploy site"** ✅

Chaque `git push` sur `main` déclenchera un redéploiement automatique.

### Option 2 — Drag & Drop Netlify

1. Téléchargez le ZIP du projet
2. Allez sur [app.netlify.com/drop](https://app.netlify.com/drop)
3. Glissez le dossier → site en ligne en 30 secondes

### Option 3 — Netlify CLI

```bash
# Installer Netlify CLI
npm install -g netlify-cli

# Se connecter
netlify login

# Déployer
cd habatech
netlify deploy --prod --dir .
```

### Option 4 — Cloner et déployer localement

```bash
# Cloner le repo
git clone https://github.com/VOTRE_USERNAME/habatech.git
cd habatech

# Ouvrir dans le navigateur
open index.html
# ou
npx serve .
```

---

## ⚙️ Configuration GitHub Actions

Le workflow `.github/workflows/deploy.yml` déploie automatiquement sur Netlify à chaque push.

### Ajouter les secrets GitHub

1. Sur GitHub : **Settings → Secrets and variables → Actions → New repository secret**
2. Ajouter ces deux secrets :

| Secret | Comment l'obtenir |
|---|---|
| `NETLIFY_AUTH_TOKEN` | [Netlify → User Settings → Personal access tokens](https://app.netlify.com/user/applications#personal-access-tokens) |
| `NETLIFY_SITE_ID` | Netlify → votre site → Site configuration → Site ID |

### Comportement du workflow

| Événement | Action |
|---|---|
| `push` sur `main` | ✅ Déploiement en **production** |
| `pull_request` | 🔍 Déploiement en **preview** avec commentaire automatique |

---

## 📞 Contact

<div>

| Canal | Coordonnées |
|---|---|
| 📞 Téléphone | +224 627 541 925 |
| 💬 WhatsApp | [+224 627 541 925](https://wa.me/224627541925) |
| ✉️ Email | habatech2026@gmail.com |
| 📧 Email CEO | habahonoris1@gmail.com |
| 📍 Adresse | Conakry, République de Guinée |

</div>

---

<div align="center">

**© 2025 HABATECH — Mr. HONORIS HABA, CEO**

*Conakry, République de Guinée 🇬🇳*

</div>
