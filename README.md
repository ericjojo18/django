Pour la création d'un projet d'un django:

-  installer python dans son ordinateur via son site https://www.python.org/downloads/ ou par invite de commande
-  creér un dossier pour le projet
-  A l'interieur du dossier nous devons créer un environnenement virtuelle en ligne de commande: python3 -m venv venv
-  nous activez notre environnement virtuelle:
  * sur macos: source venv/bin/activate
  * sur windows: venv/Scripts/activate
-  Pour installer nos dependances en lignes de commande: pip install requests
-  pour frise nos dependanes : pip freeze > requirements.txt
-  pour installer django : pip install django
-  pour créer un projet django: django-admin startproject Monetab
-   pour lance notre projet django : python manage.py runserver
-  pour creer une application django: python manage.py startapp student
-   pour inserer notre application django dans notre projet, nous devons ouvrir notre projet monetab et aller dans notre fichier settings.py
-  Dans le fichier settings.py, nous aurons une partie INSTALLED_APPS dans laquelle nous allons inserer notre application student.apps.StudendtConfig
-  Dans le fichier urls.py de notre projet Monetab, nous aurons les différents vue de notre application
-  Dans notre application student, nous allons créer notre fichier urls.py pour inserer nos différents vue de notre application
-  Dans notre application student, nous allons dans notre fichier views.py qui va etre notre controller pour la redrection vers nos templates
-  Dans notre application student, nous allons da 
