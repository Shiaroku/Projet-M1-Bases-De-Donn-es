# Projet-M1-Bases-De-Donnees
Projet en NoSQL sur MongoDB avec interface graphique en Python

# Pré-requis
Installez MongoDB 

Installez Python

Installez le module Pymongo ( pip install pymongo dans powershell )

Installez le module Tkinter ( pip install tkinter )

Téléchargez les fichiers du projet et notez le chemin du répertoire 

# Chargement du jeu de données json et lancement du daemon MongoD sur le port 27017  
Dans un terminal lancez les commandes suivantes: 

cd "C:\Program Files\MongoDB\Server\4.0\bin\"  (remplacez par le chemin adéquat si différent)

mongoimport --db movies --collection set "...\movies_mongodb.json"

mongod 

# Lancement du programme
Dans un terminal :

python ...filepath.../movies.py



