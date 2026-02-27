# 💳 Aegis Bank - Landing Page Mobile-First

[![Netlify Status](https://api.netlify.com/api/v1/badges/xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx/deploy-status)](https://app.netlify.com/sites/your-site-name/deploys)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Projet de conception web (EFP 2026) visant à créer une interface bancaire moderne, 100% fonctionnelle sur mobile, sans scroll et sans framework.

## 🔗 Liens du projet

📍 **Démo Live** : https://x64-a-2026-aarabzakiya.netlify.app/

## 📋 Table des matières

- [Description](#description)
- [Fonctionnalités](#fonctionnalités)
- [Technologies utilisées](#technologies-utilisées)
- [Architecture du projet](#architecture-du-projet)
- [Performance](#performance)
- [Accessibilité](#accessibilité)
- [Responsive Design](#responsive-design)
- [Déploiement](#déploiement)
- [Validation](#validation)
- [Auteur](#auteur)
- [Licence](#licence)

## 📝 Description

Aegis Bank est une landing page mobile-first pour une néobanque fictive. Ce projet démontre une approche moderne de développement web avec du CSS pur, en mettant l'accent sur l'expérience utilisateur mobile et les performances.

## 🚀 Fonctionnalités

- ✅ Interface 100% mobile-first
- ✅ Design sans barre de défilement (no-scroll)
- ✅ Design responsive fluide
- ✅ Animations subtiles et micro-interactions
- ✅ Accessibilité (ARIA, sémantique HTML)
- ✅ Design System avec variables CSS
- ✅ Architecture CSS modulaire (BEM, 7-1 pattern)

## 🛠 Technologies utilisées

- **HTML5** : Structure sémantique et éléments modernes
- **CSS3** : Flexbox, Grid, Variables CSS, Transitions
- **Méthodologie BEM** : Convention de nommage pour les classes CSS
- **Design System** : Variables CSS pour la cohérence visuelle
- **Mixins CSS** : Réutilisabilité du code
- **Responsive Design** : Media queries et unités fluides (clamp, vw)

## 📁 Architecture du projet

```
Aegis-bank-_64/
├── index.html                 # Structure principale
├── style.css                  # Styles globaux et responsive
├── css/
│   ├── main.css              # Point d'entrée CSS
│   ├── components/           # Composants réutilisables
│   │   ├── _button.css
│   │   ├── _card.css
│   │   ├── _footer.css
│   │   ├── _hero.css
│   │   └── _navbar.css
│   ├── utils/                # Helpers et mixins
│   │   ├── _helpers.css
│   │   └── _mixins.css
│   └── vars/                 # Variables CSS
│       ├── _colors.css
│       ├── _components.css
│       ├── _layout.css
│       ├── _spacing.css
│       ├── _typography.css
│       └── index.css
└── assets/                   # Images et icônes
```

## ⚡ Performance

- **Mobile-first** : Optimisé pour les appareils mobiles
- **No-scroll design** : Expérience utilisateur fluide
- **Variables CSS** : Réduction de la duplication
- **Minification** : Fichiers optimisés pour la production
- **Zero frameworks** : Performance maximale sans dépendances

## ♿ Accessibilité

- **HTML5 sémantique** : Structure claire et logique
- **Attributs ARIA** : Amélioration de l'accessibilité
- **Contraste des couleurs** : Respect des ratios WCAG
- **Navigation clavier** : Support complet
- **Labels appropriés** : Pour les éléments interactifs

## 📱 Responsive Design

- **Approche mobile-first** : Base mobile solide
- **Breakpoints stratégiques** : 480px, 768px, 1024px
- **Unités fluides** : `clamp()`, `vw`, `vh` pour l'adaptabilité
- **Flexbox/Grid** : Layouts modernes et flexibles
- **Images responsives** : Adaptation aux différents écrans

## ☁️ Déploiement

- **Plateforme** : Netlify (déploiement continu)
- **Version Control** : Git
- **CI/CD** : Intégration automatique via GitHub
- **HTTPS** : Sécurité garantie
- **CDN** : Distribution optimisée mondiale

## ✅ Validation

- **W3C HTML Validator** : 0 erreurs
- **W3C CSS Validator** : 0 erreurs
- **Principes SOLID CSS** : Maintenabilité et évolutivité
- **Cross-browser testing** : Compatibilité moderne

## 👥 Auteur

**Anonymous** – Designer – 2026

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus d'informations.

---

<p align="center">Made with ❤️ | EFP 2026</p>