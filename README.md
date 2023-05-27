# **PROJET RESEAU INTRANET**

## **Projet :**

Projet de conception d'une infrastructure réseau intranet pour les élèves et associations de l'école d'ingénieur EPF.

## **Introduction**

Aujourd'hui, la communication d'informations entre les élèves de l'EPF se fait essentiellement sur Facebook.
Chaque élève de l'EPF est quasiment obligé de télécharger Facebook en arrivant dans l'école. La majorité des groupes de discussions créés par les élèves pour échanger avec les camarades de classe se font sur des groupes Messenger (Facebook). De même, les actualités et informations diffusées par les différentes associations se font sur Facebook.

La gestion des données est également gérée pour chaque association par divers moyens, souvent sur des services cloud américains, différents d'une association à l'autre.
La protection des informations appartenant à l'EPF est par conséquent grandement négligée lors des échanges entre les élèves.

De plus, il y a un manque important de visibilité des actions en cours par les associations. Nous pouvons prendre comme exemple les cours d'initiation à Arduino, organisez par M. Khaled Sahli et l'association LEAP. Malgré les mails envoyés par Monsieur Sahli, peu d'élèves ont eu connaissance de ces cours et sont venus.

En plus de la communication associative très compliquée, les associations sont en manque d'autres outils, comme l'association Apostro'Phi qui a besoin de plus d'espaces de stockage pour héberger leurs vidéos, le BDJ qui n'a pas les moyens d'héberger des serveurs de jeux, cellule IPN junior qui doit héberger une base de données pour leur projet Revis'It...

De nombreuses actions d'optimisation, protection, visibilité... peuvent être réalisées pour améliorer la vie des élèves de l'EPF. D'où l'idée de ce projet.

### Cahier des charges :

- Le site web principale devra contenir les éléments suivants :
    - Une page de connexion afin de vérifier la légitimité de l'utilisateur, et prendre connaissance du rôle de l'utilisateur (admin d'une association, du site, membre de l'administration, alumnis...)
    - Une page principale affichée lors de la connexion comprenant :
        - Un fil d'actualité avec les actualités en cours et à venir que l'utilisateur a décidé de suivre.
    - Une page de profil avec les informations de l'utilisateur (nom, prénom, mail, groupes suivis...)
    - Système de recherche de groupes, associations, élèves...
    - Liste des différents groupes :
        - Les groupes devront contenir leur fil d'actualité, ainsi que le lien, s'il existe, de leur page web.
        - Intranet indépendant de la vie administrative, cependant un groupe sera à prévoir pour représenter l'administration de l'école, notamment pour les différentes informations que l'école fournit pour la vie étudiante et associative.
	- Page de mentions légales / CGU avec toutes les informations nécessaires pour respecter le cadre légal
	- Page de contacts / crédits (personnes ayant participés au projet)
<br>

- Système de communication entre les différents groupes ou personnes
	- Incluant les discussions de groupe de promos, comme les discussions individuelles entre élèves
	- Possibilité de créer des groupes avec les élèves que l'on souhaite.
	- Possibilité d'envoyer des fichiers (avec un système plus adapté au transfert de fichier que messenger.)
	- Echanges chiffrés et sécurisés.
<br>

- Site d'association pour IPN Jr :
	- Site web :
		- la page principale descriptive de l'association
		- la page pour leurs articles
		- la page de contact / recrutements
	- Drive ergonomique pour leur projet Revis'It (base de données des anciens cours, exercices, évaluations...)
<br>


## **Déroulement du projet**

- Implémenter les structures de données
- Analyse de l'API des 4A et décision de partir de leur API, ou de refaire tout notre backend de 0.
- Création de l'infrastructure backend
	- De notre site principal (peut-être en se basant sur l'API des 4A)
	- Du site IPN Jr
	- Du projet Revis'It
	- Du système de communication
- Développer l'interface utilisateur (frontend)
	- De notre site principal
	- Du site IPN Jr
	- Du projet Revis'It
	- Du système de communication
- Connexion entre le frontend et le backend
- Définir les CGU
- Tests de sécurité
<br>
