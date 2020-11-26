autoattestation.py est un script qui utilise selenium pour simplifier les déclarations de sortie covid19.

vous devez au préalable installer les dépendances : 

> pip3 install -r requirements

il se base sur un fichier users.ini ou sont les informations des utilisateurs,
et utilise des passage de variables pour faire les choix dans le formulaire 

> ./autoattestation.py -u user[,user2,user3] -h %H:%M -d %Y-%m-%d -m travail,sante,achats

il est possible de préciser plusieurs motifs  en les séparant par des virgules, et il est possible de 
générer la même feuille pour un groupe d'utilisateurs concernés par la sortie en séparant les utilisateurs
par des virgules.

le script génerer un fichier attestations.pdf qu'il ne reste plus qu'a imprimer.



