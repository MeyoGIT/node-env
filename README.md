# 🚀 Environnement de Développement Node.js avec React

## 📌 Description
Ce projet est un environnement de développement structuré et professionnel pour une application Node.js utilisant React. Il inclut des outils modernes tels que Webpack, Babel, ESLint, Jest, Husky et JSDoc, afin d'assurer une qualité optimale du code.

## ⚙️ Installation
### 📋 Prérequis
- [Node.js](https://nodejs.org/) installé (version recommandée : LTS)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

### 🛠️ Étapes d'installation
1. 📥 Cloner le projet :
   ```sh
   git clone <repository_url>
   cd <repository_name>
   ```
2. 📦 Installer les dépendances :
   ```sh
   npm install
   ```

## 📂 Structure du Projet
```
📁 .husky/              # Configuration de Husky pour la convention de commits
📁 docs/                # Documentation du projet
📁 node_modules/        # Dépendances Node.js
📁 public/              # Fichiers publics (index.html, assets...)
📁 src/                 # Code source de l'application React
📁 test/                # Tests unitaires
📝 .babelrc             # Configuration de Babel
🚫 .gitignore           # Exclusions Git (inclut .env)
✅ commitlint.config.js # Configuration de Commitlint
🔍 eslint.config.mjs    # Configuration de ESLint
🧪 jest.config.js       # Configuration de Jest
📖 jsdoc.json           # Configuration de JSDoc
📜 package.json         # Dépendances et scripts
🛠️ webpack.config.js    # Configuration de Webpack
```

## 📜 Scripts npm
Les commandes suivantes sont définies dans `package.json` :

- **🚀 Développement** :
  ```sh
  npm run dev
  ```
  Lance le serveur de développement avec Webpack, ESLint en temps réel et hot reload.

- **🏗️ Build pour production** :
  ```sh
  npm run prod
  ```
  Compile l'application et génère le bundle final après l'exécution des tests.

- **🧪 Exécution des tests** :
  ```sh
  npm run test
  ```
  Exécute les tests unitaires avec Jest et affiche la couverture de test.

- **🔍 Linter** :
  ```sh
  npm run lint
  ```
  Analyse le code avec ESLint selon la norme Airbnb.

- **📖 Documentation automatique** :
  ```sh
  npm run doc
  ```
  Génère la documentation avec JSDoc.

- **⚡ Génération automatique des commits conventionnels** :
  ```sh
  npm run commit
  ```
  Utilise Commitizen pour guider l'utilisateur dans la rédaction de commits conformes à la convention.

## 🛠️ Outils Utilisés
- **🧪 Tests unitaires** : Jest
- **📖 Documentation automatique** : JSDoc
- **📏 Convention de commits** : Husky, Commitlint, Commitizen
- **🔍 Linter** : ESLint (norme Airbnb)
- **📦 Bundler** : Webpack
- **⚡ Transpilation** : Babel
- **🎨 Styles** : SASS
- **⚛️ Framework Frontend** : React.js

## 🤝 Contribution
1. 🔀 Forker le repository
2. 🌿 Créer une branche feature (`git checkout -b feature-nom`)
3. 💬 Commit avec une convention (`npm run commit` pour suivre le format standard)
4. 📤 Push (`git push origin feature-nom`)
5. 📝 Créer une pull request

## 📜 Licence
Ce projet est sous licence MIT.

