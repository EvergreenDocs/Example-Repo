

🚀 Boilerplate et Starter pour Next.js, Tailwind CSS et TypeScript ⚡️ Fabriqué avec l'expérience du développeur en premier: Next.js, TypeScript, ESLint, Prettier, Husky, Lint-Staged, Jest, Testing Library, Commitlint, VSCode, Netlify, PostCSS, Tailwind CSS.

Clonez ce projet et utilisez-le pour créer votre propre projet [Next.js](https://nextjs.org). Vous pouvez vérifier une [démo de modèles Next js](https://creativedesignsguru.com/demo/Nextjs-Boilerplate/).

### Caractéristiques

Expérience du développeur en premier:

- ⚡ [Next.js](https://nextjs.org) pour le générateur de site statique
- 🔥 Vérification des types [TypeScript](https://www.typescriptlang.org)
- 💎 Intégration avec [Tailwind CSS](https://tailwindcss.com)
- ✅ Mode strict pour TypeScript et React 18
- 📏 Linter avec [ESLint](https://eslint.org) (configuration NextJS, NextJS Core Web Vitals, Tailwind CSS et Airbnb par défaut)
- 💖 Code Formatter avec [Prettier](https://prettier.io)
- 🦊 Husky pour les Git Hooks
- 🚫 Lint-staged pour exécuter les linters sur les fichiers Git
- 🚓 Lint git commit avec Commitlint
- 📓 Écrire des messages de commit conformes aux normes avec Commitizen
- 🦺 Test unitaire avec Jest et React Testing Library
- 🧪 Test E2E avec Cypress
- 👷 Exécuter des tests sur la demande de tirage avec GitHub Actions
- 🎁 Génération automatique du journal des modifications avec Semantic Release
- 🔍 Test visuel avec Percy (facultatif)
- 💡 Imports absolus en utilisant le préfixe `@`
- 🗂 Configuration VSCode: débogage, paramètres, tâches et extension pour PostCSS, ESLint, Prettier, TypeScript, Jest
- 🤖 Méta-données SEO, JSON-LD et balises Open Graph avec Next SEO
- 🗺️ Sitemap.xml et robots.txt avec next-sitemap
- ⚙️ [Bundler Analyzer](https://www.npmjs.com/package/@next/bundle-analyzer)
- 🖱️ Déploiement en un clic avec Vercel ou Netlify (ou déploiement manuel vers tout service d'hébergement)
- 🌈 Inclure un thème minimaliste GRATUIT
- 💯 Maximiser le score de phare

Fonctionnalité intégrée de Next.js:

- ☕ Minifier HTML & CSS
- 💨 Rechargement en direct
- ✅ Débogage de cache

### Philosophie

- Toutes les pages Next.js sont générées statiquement par défaut. Vous pouvez facilement passer à SSR en ajoutant `getServerSideProps` à votre page.
- Rien n'est caché de vous, vous avez donc la liberté de faire les ajustements nécessaires pour répondre à vos besoins et préférences.
- Code minimal
- Convivial pour les moteurs de recherche
- 🚀 Prêt pour la production

### Nextless.js SaaS Boilerplate

Créez votre produit SaaS plus rapidement avec [React SaaS Boilerplate](https://nextlessjs.com).

[![React SaaS Boilerplate Next.js](https://creativedesignsguru.com/assets/images/themes/next-js-saas-starter-kit.jpg)](https://nextlessjs.com)

### Thèmes Premium

| [Modèle de page d'accueil Nextjs vert](https://creativedesignsguru.com/landing-green-modern-nextjs-theme/) | [Thème Saas Nextjs pourpre](https://creativedesignsguru.com/landing-purple-modern-react-theme/) |
| --- | --- |
| [![Modèle de page d'accueil Nextjs vert](https://creativedesignsguru.com/assets/images/themes/landing-green-modern-nextjs-theme-xs.png)](https://creativedesignsguru.com/landing-green-modern-nextjs-theme/) | [![Thème de page d'accueil Nextjs bleu](https://creativedesignsguru.com/assets/images/themes/landing-blue-modern-nextjs-theme-xs.png)](https://creativedesignsguru.com/landing-blue-modern-react-theme/) |

Trouvez plus de [Thèmes Nextjs](https://creativedesignsguru.com/category/nextjs/).

### Exigences

- Node.js 14+ et npm

### Mise en route

Exécutez la commande suivante sur votre environnement local:

```shell
git clone --depth=1 https://github.com/ixartz/Next-js-Boilerplate.git my-project-name
cd my-project-name
npm install
```

Ensuite, vous pouvez exécuter localement en mode développement avec rechargement en direct:

```shell
npm run dev
```

Ouvrez http://localhost:3000 avec votre navigateur préféré pour voir votre projet.

```shell
.
├── README.md                       # Fichier README
├── __mocks__                       # Mocks pour les tests
├── .github                         # Dossier GitHub
├── .husky                         # Configuration Husky
├── .vscode                         # Configuration VSCode
├── public                         # Dossier des ressources publiques
├── src
│   ├── layouts                     # Composants de mise en page
│   ├── pages                       # Pages Next JS
│   ├── pages.test                  # Tests de pages Next JS (ceci permet d'éviter que les tests soient traités comme des pages Next.js)
│   ├── styles                      # Dossier des styles
│   ├── templates                   # Modèle par défaut
│   └── utils                       # Fonctions utilitaires
├── tailwind.config.js              # Configuration Tailwind CSS
└── tsconfig.json                   # Configuration TypeScript
```