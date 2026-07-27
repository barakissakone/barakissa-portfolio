# Portfolio — Barakissa Kone

Portfolio React (Vite) présentant le profil, les compétences, les expériences,
les projets et la formation de Barakissa Kone.

## Lancer le projet en local

```bash
npm install
npm run dev
```

Puis ouvre l'adresse affichée dans le terminal (en général `http://localhost:5173`).

## Construire pour la mise en ligne

```bash
npm run build
```

Le résultat est généré dans le dossier `dist/`, prêt à être déployé (Netlify,
Vercel, GitHub Pages, etc.).

## Structure

```
index.html          → page HTML de base
src/main.jsx         → point d'entrée React
src/App.jsx          → tout le portfolio (une seule page)
src/index.css        → reset CSS minimal
```

## Personnaliser

- Compétences, expériences, projets et formation : tableaux `SKILLS`,
  `EXPERIENCES`, `PROJECTS` en haut de `src/App.jsx`.
- Couleurs et typographies : variables CSS au tout début de la constante
  `CSS` dans `src/App.jsx` (`--bg`, `--yolo`, `--teal`, etc.).
- Visuels des projets : composants `KaizenMedia`, `DashboardMedia`,
  `KHopesMedia` — remplace-les par de vraies captures d'écran (`<img src="..." />`)
  dès que tu en as.
