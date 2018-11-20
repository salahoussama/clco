Projet de semestre

1.	L'architecture global de l'application :
   
Modèle : des traitements et des données

Dans le modèle, on trouve à la fois les données et les traitements à appliquer à ces données. Ce bloc contient donc des objets Java d'une part, qui peuvent contenir des attributs (données) et des méthodes (traitements) qui leur sont propres, et un système capable de stocker des données d'autre part. Rien de bien transcendant ici, la complexité du code dépendra bien évidemment de la complexité des traitements à effectuer par votre application.
 
Vue : des pages JSP

Une page JSP est destinée à la vue. Elle est exécutée côté serveur et permet l'écriture de gabarits (pages en langage "client" comme HTML, CSS, Javascript, XML, etc.). Elle permet au concepteur de la page d'appeler de manière transparente des portions de code Java, via des balises et expressions ressemblant fortement aux balises de présentation HTML. 

Contrôleur : des servlets

Une servlet est un objet qui permet d'intercepter les requêtes faites par un client, et qui peut personnaliser une réponse en conséquence. Il fournit pour cela des méthodes permettant de scruter les requêtes HTTP. Cet objet n'agit jamais directement sur les données, il faut le voir comme un simple aiguilleur : il intercepte une requête issue d'un client, appelle éventuellement des traitements effectués par le modèle, et ordonne en retour à la vue d'afficher le résultat au client.

2.	L'architecture de la couche donnée :
3.	La manière de gestion des demandes des clients :
4.	Les technologies choisies pour le développement :

•	  JEE :    est une technologie développée par Sun puis Oracle pour le développement d'applications distribuées en java. JEE repose sur JSE et est à destination des plateformes web. C'est une norme décrivant tous les éléments pour le fonctionnement d'une application distribuée  
•	HTML : est le langage de balisage conçu pour représenter les pages web.
•	SQL : est un langage informatique Normalisé servant à exploiter des bases des données relationnelles. La partie langage de manipulation des données de SQL permet de rechercher, d'ajouter, de modifier ou de supprimer des données dans les bases de données relationnelles.

•	FRAMEWORK : ensemble de bibliothèques structure en mvc .

•	 Spring.

•	Hibernate

•	Jsf

                                    
