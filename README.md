# Projet-M1-Bases-De-Donnees
Projet en NoSQL sur MongoDB avec interface graphique en Python

# Pré-requis
Installez MongoDB 

Installez Pymongo ( pip install pymongo dans powershell )

Installez Tkinter ( pip install tkinter )

Téléchargez le fichier movies_mongodb.json 

# Chargement du jeu de données json et lancement du daemon MongoD sur le port 27017  
Dans un terminal lancez les commandes suivantes: 

cd "C:\Program Files\MongoDB\Server\4.0\bin\"  % remplacez par le chemin adéquat

mongoimport --db movies --collection set "...\movies_mongodb.json"

mongod 


