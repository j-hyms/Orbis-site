# 🪐 Orbis – Site vitrine

Site web de présentation du bot Discord **[Orbis](https://github.com/j-hyms/Orbis)**, un bot de gestion et de modération pour serveurs Discord.

🔗 **Site en ligne :** `https://j-hyms.github.io/Orbis-site/` 

---

## ✨ Aperçu

Le site se compose de trois pages, sans rechargement :

| Page | Contenu |
|------|---------|
| **Accueil** | Présentation du bot, chiffres animés et fonctionnalités principales |
| **Le bot** | Description complète : commandes, exemples, installation, hébergement, dépannage, et lien de téléchargement du README |
| **Contact** | Formulaire de contact et liens utiles |

**Points forts :**
- Bandeau de navigation fixe en haut de page
- Thème sombre et thème clair (bouton ◐)
- Design responsive (ordinateur, tablette, mobile)
- Un seul fichier, sans dépendance ni outil de build

---

## 📁 Structure

```
orbis-site/
├── index.html    # Le site complet (HTML, CSS et JavaScript)
└── README.md     # Ce fichier
```

---

## 🚀 Utilisation en local

Aucune installation n'est nécessaire : ouvrez simplement `index.html` dans votre navigateur.

Pour le servir avec un petit serveur local :

```bash
npx serve .
```

---

## 🌐 Mise en ligne avec GitHub Pages

1. Envoyez le contenu du dossier sur un dépôt GitHub (par exemple `orbis-site`).
2. Allez dans **Settings → Pages**.
3. Dans **Build and deployment**, choisissez **Deploy from a branch**.
4. Sélectionnez la branche `main` et le dossier `/ (root)`, puis **Save**.
5. Après une à deux minutes, le site est accessible à l'adresse `https://j-hyms.github.io/Orbis-site/`.

Le site fonctionne aussi sur Netlify, Cloudflare Pages ou n'importe quel hébergeur de fichiers statiques.

---

## ⚙️ Personnalisation

Tout se modifie dans `index.html` :

| Élément | Où le changer |
|---------|---------------|
| Adresse email de contact | Variable `EMAIL` au début du `<script>` |
| Couleurs et thème | Variables CSS au début du `<style>` (`--acc`, `--acc2`, `--bg`…) |
| Textes des pages | Sections `<section class="page" id="p-…">` |
| Lien de téléchargement du README | Bouton « Télécharger le README » dans la page *Le bot* |

> **Formulaire de contact :** il n'utilise pas de serveur. Il ouvre l'application de messagerie du visiteur avec le message pré-rempli (`mailto:`). Pour recevoir les messages directement, vous pouvez le connecter à un service comme Formspree ou Netlify Forms.

---

## 🤖 À propos du bot Orbis

Orbis est un bot **Node.js + discord.js v14** qui gère la modération, les rôles, les salons et les membres via des commandes slash : `/mod`, `/role`, `/salon`, `/membre`, `/config` et `/aide`.

Code source et documentation complète : **[github.com/j-hyms/Orbis](https://github.com/j-hyms/Orbis)**

---

## 📬 Contact

- Issues : [github.com/j-hyms/Orbis/issues](https://github.com/j-hyms/Orbis/issues)
- Email : `jules.prod.dev@gmail.com` *(à adapter)*

---

## 📄 Licence
