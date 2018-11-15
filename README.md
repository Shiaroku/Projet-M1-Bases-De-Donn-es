# Projet-M1-Bases-De-Donnees
Projet en NoSQL sur MongoDB avec interface graphique en Python

Activity.mongo contient le code source des exercices de OpenClassroom sur le NoSQL

Movies.exe est un petit programme graphique d'interrogation d'une base de données de films sur des critères simples pour m'entrainer a utiliser json et MongoDB autrement que par des requêtes directes sur Robo3T

(voir http://exercices.openclassrooms.com/assessment/647?id=4462426&slug=maitrisez-les-bases-de-donnees-nosql&login=7398438&tk=197d6beaf9d732115a8db1ecf037698a&sbd=2016-02-01&sbdtk=fa78d6dd3126b956265a25af9b322d55)

# Pré-requis

Installez MongoDB 

Téléchargez les fichiers du projet et notez le chemin du répertoire 


# Chargement du jeu de données json et lancement du daemon MongoD sur le port 27017  

Dans un terminal lancez les commandes suivantes: 

cd "C:\Program Files\MongoDB\Server\4.0\bin\"  (remplacez par le chemin adéquat si différent)

mongoimport --db movies --collection set "...\movies_mongodb.json"

mongod 

# Lancement du programme

Lancez movies.exe 

OU : 

Dans un terminal : (Nécessite Python, le module Pymongo ( pip install pymongo dans powershell ) et le module Tkinter ( pip install tkinter )


python ...filepath.../movies.py



