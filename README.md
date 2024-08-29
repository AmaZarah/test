

# COMMENT CREER UN PROJET DJANGO

1- Créer un dossier

2- ouvrir le dossier avec un editeur de Code

3- créer un environnement virtuel avec la comment: PYTHON -M VENV NOM DE L'ENVIREONNEMENT

4- Activé l'environnement : NOM ENVIRONNEMENT\Scripts\activate

5- installation de django avec la commande: pip install python

6- creer un projet django : django-admin staratproject nom du projet

7- creer une application django: python manage.py startapp nom de l-application

8-apres avoir creer le projet et les applications un dossier se crée qui prend le nom du projet django avec les fichiers:
 - setting.py dans lequel ajoute nos applications pour que le projet puisse prendre en compte nos application, connection à la base de donnée,  
 - urls.py 
 - manage.py
 - pycache
 -migrate

9 dans chaque application creer nous avons plusieurs dossiers par defaut:
 - views.py
 - admin.py 
 __init__
 -tests.py
 - apps.py

#INTEGRATIONN D'UN PROJET

1- creation des dossiers Templates et Static dans chaque application

2- créer un fichier urls.py dans chaque application

3- dans la views de chaque application definir des fonctions selon le besoin

4- dans l'urls.py de chaque application definir le lien de a route et creation d'une Appname

5- pour la verification 
  dans le terminal 
   -active l'environnement
   etre à la racine de notre projet avec la commande cd non du projet
   lancer le serveur avec la commande : python manage.py runserver

# pour la definition des fonctions:
 
  def non de fonction(request)

#pour les urls


