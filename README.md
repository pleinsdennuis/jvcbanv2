# jvcbanv2

#### Requirements
Pour exécuter / installer le programme, vous aurez besoin de :
NodeJS avec NPM installé.

#### Téléchargement des dépendances
Après avoir cloné le code source depuis Github, vous devez exécuter la commande suivante (DEPUIS LE DOSSIER DU PROJET CLONÉ) pour télécharger toutes les dépendances (ws, express, etc.) :
```
npm install axios express generic-pool ws
```
```
npm install nodemon --save-dev
```

Ensuite dans server.js, ajouter le cookie coniunctio
Dans public/main.js, modifier la ligne de l'ip du serveur local et mettez la votre, trouvable en faisant :

```
ip a |grep 192
```
sur linux, pour windows aucune idée.


#### Exécution du serveur
Après avoir téléchargé toutes les dépendances et modifier les lignes du cookie et du serveur, vous pouvez exécuter le serveur avec la commande suivante :
```
npm run dev
```
![screenshot_projet](https://image.noelshack.com/fichiers/2023/02/6/1673704923-ppppp.png)

Ouvrez votre navigateur et allez sur `http://localhost:8080` pour lancer ce foutu vérificateur de pseudo ban.
