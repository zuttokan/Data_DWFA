# <a  href="https://openclassrooms.com/fr/paths/717-developpeur-web](https://openclassrooms.com/fr/paths/324/projects/861/assignment"  title="openclassrooms"><img  src="https://upload.wikimedia.org/wikipedia/fr/0/0d/Logo_OpenClassrooms.png"  alt="openclassrooms"  width="35px"  height="31px"></a> Project 8 - Openclassrooms -DATA Analyst

# A study on drinking water worldwide for DWFA / POWER BI


## The project contain the following technologie:

- <a  href="https://powerbi.microsoft.com/fr-fr/landing/free-account/?ef_id=_k_CjwKCAjwgsqoBhBNEiwAwe5w0xHF6dl-56uE6OvotfT4_Y1yXaR1tkNPf6B996vkV4ech5QHHN2YKBoC4icQAvD_BwE_k_&OCID=AIDcmms35ch80f_SEM__k_CjwKCAjwgsqoBhBNEiwAwe5w0xHF6dl-56uE6OvotfT4_Y1yXaR1tkNPf6B996vkV4ech5QHHN2YKBoC4icQAvD_BwE_k_&gclid=CjwKCAjwgsqoBhBNEiwAwe5w0xHF6dl-56uE6OvotfT4_Y1yXaR1tkNPf6B996vkV4ech5QHHN2YKBoC4icQAvD_BwE"  title="Power_BI"><img  src="https://github.com/get-icon/geticon/raw/master/icons/nodejs-icon.svg"  alt="Power BI"  width="25px"  height="21px"> Power BI</a>
- <a  href="https://www.microsoft.com/fr/microsoft-365/powerpoint"  title="Power_Point"><img  src="https://github.com/get-icon/geticon/blob/master/icons/microsoft-office-powerpoint.svg"  alt="Power Point"  width="25px"  height="21px">Power Point</a>


### Visionner la video du projet

https://youtu.be/yceB1LkwV_s

## Backend

### Cloner le repository:

- Faites un git clone ou téléchargez la version Zip

```
Git clone https://github.com/zuttokan/Groupomania
```

### Lancer le serveur:

- Depuis votre terminal ouvrez une ligne de commande :

```
cd backend (Dirige dans le bon dossier)
npm install (Permet d'installer toutes les dépendences)
node server (Lance le serveur)
```

### Créer à la racine du backend un fichier .env contenant les variables suivantes :

SECRET_DB = (informations de votre base de données)

PORT = (Le port ou votre serveur sera hébérgé)

TOKEN_SECRET = ( Votre clé secret de décodage du Token)

isAdmin = (l'adresse mail spécifique au compte administrateur)

## Frontend

### Démarrer le front:

- Depuis votre terminal ouvrez une ligne de commande :

```
cd frontend (Dirige dans le bon dossier)
npm install (Permet d'installer toutes les dépendences)
ng serve (Lance le front)

```

### Pour accéder à l'interface du site:

- Ouvrir le navigateur a l'adresse http://localhost:4200/

### Fonctionnalités utilisateurs:

<ul>
  <li>Inscription ou connexion via l'email avec un mot de passe.</li>
  <li>Partager des posts contenant du texte et une image.</li>
  <li>L'affichage des posts se fait de magniére antéchronologique.</li>
  <li>Chaque post contient sont datage de création ainsi que le mail de sont créateur.</li>
  <li>Chaque utilisateur à la possibilité de modifier ou supprimer ses propres posts.</li>
  <li>Il est possible de liker un post (ou de le retirer).</li>
</ul>

- Un compte Administrateur est présent afin de faire de la modération.
  Il a la possibilité de modifier ou de supprimer les posts utilisateurs, ainsi qu'en créer si necéssaire.

### Fonctionnalités techniques:

<ul>
<li>La session de l’utilisateur persiste durant sa connection.</li>
<li>Les données de connexion sont sécurisées.</li>
</ul>

### Identité graphique:

<ul>
<li>La police d'éciture est Lato</li>
<li>La palette de couleur principale utiliser est :Primaire : #FD2D01 / Secondaire : #FFD7D7 /Tertiaire : #4E5166
</li>
</ul>

## Page de connection et inscription
![connexiongroupo](https://user-images.githubusercontent.com/100352779/189333971-4b95eab9-a5cd-4cc1-9eff-53c21e0a2980.jpg)

## Page des messages
![page messages](https://user-images.githubusercontent.com/100352779/189334272-0e4a5a35-54a4-4f3c-84e6-ece199e9297b.png)
