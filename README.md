# 🌤️ Ciel Ouvert — Météo de la semaine

Application météo 7 jours avec évolution matin · midi · soir, graphique de températures et heures de lever/coucher du soleil.

## 🚀 Déploiement sur GitHub Pages

### Étape 1 — Créer le dépôt

1. Connectez-vous sur [github.com](https://github.com)
2. Cliquez sur **"New repository"** (bouton vert en haut à droite)
3. Nommez-le par exemple `meteo` (ou ce que vous voulez)
4. Laissez-le en **Public**
5. Cliquez **"Create repository"**

### Étape 2 — Uploader le fichier

1. Dans votre nouveau dépôt, cliquez **"uploading an existing file"** (ou "Add file" → "Upload files")
2. Glissez-déposez le fichier **`index.html`**
3. En bas, cliquez **"Commit changes"**

### Étape 3 — Activer GitHub Pages

1. Allez dans **Settings** (onglet en haut du dépôt)
2. Dans le menu gauche, cliquez **"Pages"**
3. Sous *Source*, sélectionnez **"Deploy from a branch"**
4. Choisissez la branche **`main`** et le dossier **`/ (root)`**
5. Cliquez **"Save"**

### Étape 4 — Accéder à votre lien

Après ~1 minute, votre application est disponible à l'adresse :

```
https://<votre-pseudo-github>.github.io/<nom-du-repo>/
```

**Exemple :** `https://jdupont.github.io/meteo/`

---

## 🔧 Fonctionnalités

- 🔍 Recherche par nom de ville (mondial)
- 🌡️ Températures matin (8h), midi (13h), soir (19h)
- 📈 Graphique 5 courbes : matin · midi · soir · max · min
- 🌅 Heures de lever et coucher du soleil pour chaque jour
- 🎨 Teinte de fond adaptée aux conditions météo
- 📱 Responsive (mobile, tablette, desktop)
- ⚡ Aucune clé API requise — données [Open-Meteo](https://open-meteo.com) (gratuit)

## 📁 Structure

```
/
└── index.html   ← fichier unique, tout-en-un (HTML + CSS + JS)
```

Aucune dépendance npm, aucun build, aucun serveur — fonctionne directement dans le navigateur.
