# App-Attendance-Tracking
![Acceuil](https://user-images.githubusercontent.com/106842102/178103382-4caa8aa6-0682-48d3-b68d-19cf67192289.jpg)

Ce projet consiste à construire un système de présence qui utilise la reconnaissance faciale pour marquer la présence, le temps d'arrivée et le temps d'arrêt des employés. Il couvre des domaines tels que la détection faciale, l'alignement et la reconnaissance, ainsi que le développement d'une application Web pour répondre à divers cas d'utilisation du système tels que l'enregistrement de nouveaux employés, l'ajout de photos à l'ensemble de données de formation, la visualisation des rapports de présence, etc. Ce projet vise à servir de substitut efficace aux systèmes traditionnels de présence manuelle. Il peut être utilisé dans les bureaux d'entreprise, les écoles et les organisations où la sécurité est essentielle.

Ce projet vise à automatiser le système de présence traditionnel où la présence est marquée manuellement. Il permet également à une organisation de conserver numériquement ses enregistrements tels que les heures d'arrivée, les heures de sortie, les temps de pause et les présences. La numérisation du système aiderait également à une meilleure visualisation des données à l'aide de graphiques pour afficher le non. d'employés présents aujourd'hui, le nombre total d'heures de travail de chaque employé et son temps de pause. Ses fonctionnalités supplémentaires constituent une mise à niveau et un remplacement efficaces par rapport au système de présence traditionnel.
# Portée du projet
La reconnaissance faciale prend de plus en plus d'importance dans notre société. Elle a fait des progrès majeurs dans le domaine de la sécurité. C'est un outil très efficace qui peut aider les forces de l'ordre à reconnaître les criminels et les éditeurs de logiciels qui exploitent la technologie pour aider les utilisateurs à accéder à la technologie. Cette technologie peut être développée plus avant pour être utilisée dans d'autres voies telles que les guichets automatiques, l'accès à des fichiers confidentiels ou d'autres documents sensibles. Ce projet sert de base à de futurs projets basés sur la détection et la reconnaissance faciales. Ce projet associe également le développement Web et la gestion de base de données à une interface utilisateur conviviale. En utilisant ce système, n'importe quel bureau d'entreprise, école et organisation peut remplacer leur méthode traditionnelle de maintien de la présence des employés et peut également générer leur rapport de disponibilité (présence) tout au long du mois.

**Le système fonctionne principalement autour de 2 types d'utilisateurs :**
1. Employé
2. Administrateur

**Les fonctionnalités suivantes peuvent être exécutées par l'administrateur :<br>**

• Connexion <br>
• Enregistrer de nouveaux employés dans le système <br>
• Ajouter des photos d'employés à l'ensemble de données de formation <br>
• Former le modèle <br>
• Afficher le rapport de présence de tous les employés. La présence peut être filtrée par date ou par employé. <br>

**Les fonctionnalités suivantes peuvent être exécutées par l'employé : <br>**

• Se connecter <br>
• Marquer son heure d'arrivée et d'arrêt en scannant son visage <br>
• Afficher le rapport de présence de lui-même <br>

# Détection facial
Détecteur facial HOG de Dlib.

# Détection des repères faciaux
Prédicteur de forme à 68 points de Dlib

# Extraction des enrobages faciaux
face_recognition par Adam Geitgey

# Classification de l'intégration inconnue
en utilisant un SVM linéaire (scikit-learn)

# Documentation
Ce dossier contient tous les documents liés aux diagrammes UML.

# Comment exécuter ?
- clonez-le sur votre ordinateur
- créez [un environnement virtuel python](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/) séparé ou utilisez celui par défaut déjà installé sur votre machine
- Télécharger [ce fichier]() de prédicteur de forme à 68 points de Dlib
- placez-le dans le répertoire **``` \Attendance-System-Using-Face-Recognition\face_recognition_data ```**  
- Exécution **``` pip install -r requirements.txt ```**  à l'intérieur de répertoire **``` \Attendance-System-Using-Face-Recognition ```** pour installer les bibliothèques
- Exécuter **``` python manage.py runserver ```** dans le répertoire **``` \Attendance-System-Using-Face-Recognitionle ```**  pour exécuter le projet
- Prendre plaisir !
# Interface d'utilisateur💻
