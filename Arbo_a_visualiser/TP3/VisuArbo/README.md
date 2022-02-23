# VisuArbo

# Etape 1 : 
Créer le fichier json contenant le path dont on veut visualiser l'arborescence et le mettre sous le répertoire VisuArbo. Pour cela,, lancer sous le répertoire VisuArbo la commande : python3 folder_to_json.py ./ > VisuArbo.json
Ici nous avons choisi de visualiser toute l'arborescence à partir du dossier sous lequel le script folder_to_json.py est lancé)
python3 folder_to_json.py /home/liz/Documents/MS_Big_Data_TP_et_projets > VisuArbo.json

# Etape 2 : 
créer un serveur sous le répertoire VisuArbo avec la commande :  python3 -m http.server

# Etape 3 : 
Dans un navigateur, taper l'url : localhost:8000/ , c'est la page index.html qui se lance. 

# Etape 4 : 
Jouer avec l'arbre. 
