# Prompt pour Claude Code (VS Code)

Copie-colle ce prompt dans Claude Code :

---

Crée un repo GitHub privé "brief-tf1-oec", pousse le contenu du dossier `site-justine-tf1/` (un seul fichier index.html), puis déploie-le sur Netlify avec un mot de passe site-wide "Justineisthebest69002". Étapes :

1. `cd` dans le dossier `site-justine-tf1/` (dans mon workspace actuel)
2. `git init && git add . && git commit -m "Brief TF1 - site mobile"`
3. `gh repo create brief-tf1-oec --private --source=. --push`
4. `npm install -g netlify-cli` (si pas déjà installé)
5. `netlify login` (si pas déjà authentifié)
6. `netlify init` - crée un nouveau site, connecté au repo GitHub brief-tf1-oec
7. `netlify deploy --prod --dir=.`
8. Puis active la protection par mot de passe : `netlify password --password "Justineisthebest69002"` ou bien va dans Site configuration > Access & security > Set site password

Donne-moi l'URL du site une fois déployé.

---
