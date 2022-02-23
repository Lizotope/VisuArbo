# VisuArbo

# Etape 1 : 
Déziper le .zip sous un folder VisuArbo.

# Etape 2 : 
Créer le fichier json contenant le path dont on veut visualiser l'arborescence et le mettre sous le répertoire VisuArbo. Pour cela,, lancer sous le répertoire VisuArbo la commande : python3 folder_to_json.py ./Arbo_a_visualiser > VisuArbo.json
Ici nous avons choisi de visualiser toute l'arborescence sous le dossier "Arbo_a_visualiser", dossier enfant du path sous lequel le script folder_to_json.py est lancé.

# Etape 3 : 
Créer un serveur sous le répertoire VisuArbo avec la commande :  python3 -m http.server

# Etape 4 : 
Dans un navigateur, taper l'url : localhost:8000/ , c'est la page index.html qui se lance. 

# Etape 5 : 
Jouer avec l'arbre. 
