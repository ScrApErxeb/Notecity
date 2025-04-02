# Application de Notation des Services Web

Cette application permet aux utilisateurs d'évaluer et de noter différents services web. Elle est disponible sur le web et les plateformes mobiles (iOS et Android).

---

## Fonctionnalités principales
- Création de compte et authentification (via email ou réseaux sociaux)
- Recherche et affichage des services web
- Notation et commentaires sur les services
- Classement des services par popularité ou note
- Notifications push pour les mises à jour importantes

---

## Technologies utilisées

### **Frontend Web**
- **Framework/Library** : [React.js](https://reactjs.org/)
- **Langage** : TypeScript
- **UI Framework** : [Tailwind CSS](https://tailwindcss.com/) ou [Material-UI](https://mui.com/)
- **Gestion d'état** : [Redux Toolkit](https://redux-toolkit.js.org/) ou [React Query](https://tanstack.com/query)
- **Tests** : [Jest](https://jestjs.io/) + [React Testing Library](https://testing-library.com/)

### **Mobile**
- **Framework** : [React Native](https://reactnative.dev/)
- **Langage** : TypeScript
- **Navigation** : [React Navigation](https://reactnavigation.org/)
- **UI Framework** : [NativeBase](https://nativebase.io/) ou [React Native Paper](https://callstack.github.io/react-native-paper/)
- **Tests** : [Jest](https://jestjs.io/) + [Detox](https://wix.github.io/Detox/)

### **Backend**
- **Framework** : [Django REST Framework](https://www.django-rest-framework.org/) ou [FastAPI](https://fastapi.tiangolo.com/)
- **Langage** : Python
- **Base de données** : PostgreSQL ou MongoDB
- **Authentification** : JWT (JSON Web Tokens) ou OAuth2
- **Tests** : [Pytest](https://pytest.org/)

### **Infrastructure**
- **Hébergement Frontend Web** : [Vercel](https://vercel.com/) ou [Netlify](https://www.netlify.com/)
- **Hébergement Backend** : [AWS](https://aws.amazon.com/), [Heroku](https://www.heroku.com/) ou [Render](https://render.com/)
- **Base de données** : [AWS RDS](https://aws.amazon.com/rds/), [Supabase](https://supabase.com/) ou [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- **Stockage de fichiers** : [AWS S3](https://aws.amazon.com/s3/) ou [Cloudinary](https://cloudinary.com/)
- **CI/CD** : [GitHub Actions](https://github.com/features/actions)

### **Outils supplémentaires**
- **Gestion de projet** : [Trello](https://trello.com/), [Jira](https://www.atlassian.com/software/jira) ou [Notion](https://www.notion.so/)
- **Suivi des erreurs** : [Sentry](https://sentry.io/)
- **Analytics** : [Google Analytics](https://analytics.google.com/) ou [Mixpanel](https://mixpanel.com/)
- **Notifications** : [Firebase Cloud Messaging](https://firebase.google.com/products/cloud-messaging)

---

## Installation et démarrage

### **Frontend Web**
1. Clonez le dépôt.
2. Accédez au dossier `web` :
   ```bash
   cd web
   ```
3. Installez les dépendances :
   ```bash
   npm install
   ```
4. Lancez l'application :
   ```bash
   npm start
   ```

### **Mobile**
1. Accédez au dossier `mobile` :
   ```bash
   cd mobile
   ```
2. Installez les dépendances :
   ```bash
   npm install
   ```
3. Lancez l'application :
   ```bash
   npm start
   ```

### **Backend**
1. Accédez au dossier `backend` :
   ```bash
   cd backend
   ```
2. Installez les dépendances Python :
   ```bash
   pip install -r requirements.txt
   ```
3. Lancez le serveur :
   ```bash
   python manage.py runserver
   ```

---

## Contribution
Les contributions sont les bienvenues ! Veuillez soumettre une pull request ou ouvrir une issue pour discuter des changements.

---

## Licence
Ce projet est sous licence MIT. Consultez le fichier `LICENSE` pour plus d'informations.