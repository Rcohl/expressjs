# ExpressJS

Ce repo contient une appli express.js de type "Hello World" pour tester le déploiement.

## Installation en local

```
git clone https://github.com/Rcolh/expressjs
cd expressjs
npm install
```

### Utilisation

```
node app.js
```

[http://localhost:3000](http://localhost:3000)

## Installation sur Render.com

Prérequis :
-Compte Github

-(optionnel) Forkez un repo sur Github si nécessaire
-Créez un compte sur Render.com [https://dashboard.render.com/](https://dashboard.render.com/)
-Créez un nouveau web service en cliquant sur l'icône +
-Choisissez l'option «build and deploy from a Git repository»
-Cliquez sur « Connect account » dans la section Github à droite
-Tapez votre mot de passe Github
-Sélectionnez le repo que vous voulez publier
-Confirmez les permissions accordées, vous revenez sur le site de Render
-Cliquez sur le bouton « Connect » du repo que vous voulez publier
-Remplissez les champs avec les données suivantes :

General:

Name: sous-domaine-de-votre-appli
Region: Frankfurt (EU Central)
Instance Type: Free

Build & Deploy:

Repository: https://github.com/jibundeyare/src-express
Branch: main
Root Directory: <nc>
Build Filters: <nc>
Build Command: npm install
Start Command: node app.js
