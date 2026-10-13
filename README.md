# 🏮 Anaïs-ya — site web responsive

Site vitrine d'un restaurant japonais **fictif** situé dans le 17e arrondissement de Paris, réalisé en **HTML et CSS** dans le cadre de mon BTS SIO option SLAM.
L'objectif : créer un site de plusieurs pages qui s'adapte à toutes les tailles d'écran.

## ✨ Ce que montre ce projet

- **3 pages reliées** : accueil, carte (entrées, ramen, desserts) et réservation
- **Responsive « mobile first »** : le site est d'abord pensé pour le téléphone, puis adapté avec deux *media queries*
  - téléphone : 1 colonne et menu burger
  - tablette (≥ 700 px) : 2 colonnes
  - ordinateur (≥ 1024 px) : 3 colonnes et menu en ligne
- **Menu burger 100 % CSS**, sans JavaScript, grâce à une case à cocher cachée (`:checked`)
- **Mise en page** avec **Flexbox** (en-tête, bandeau) et **CSS Grid** (cartes)
- **Formulaire de réservation** validé par HTML5 : `required`, `type="email"`, `type="date"`, `type="time"` avec heures min/max, `pattern` pour le téléphone, bordure rouge si un champ est invalide
- **Mascotte (un chat kawaii) dessinée uniquement en CSS** : `border-radius`, pseudo-éléments `::before` / `::after` pour les oreilles, animation `@keyframes`
- **Variables CSS** pour les couleurs, afin de modifier tout le thème en une ligne
- **Accessibilité** : textes alternatifs, labels sur tous les champs, animations désactivées si l'utilisateur le demande (`prefers-reduced-motion`)

## 🚀 Voir le site

Ouvre simplement `index.html` dans ton navigateur : il n'y a rien à installer.

## 🗂️ Organisation

```
anais-ya/
├── index.html     # accueil
├── carte.html     # la carte du restaurant
├── contact.html   # formulaire de réservation
└── css/
    └── style.css  # une seule feuille de style pour tout le site
└── images/
    └── anais.jpg  # photo de la section « Le mot de la cheffe »
```

## 👩‍💻 Autrice

**Anaïs Billaud**, étudiante en BTS SIO option SLAM. Anaïs-ya (« chez Anaïs » en japonais) est un restaurant imaginaire créé pour ce projet : l'adresse, le téléphone et les avis sont fictifs.
