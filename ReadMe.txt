C:\>python -m venv e:\pyDjenv
C:\Users\user>pushd E:\Python_Django
E:\Python_Django>python -m pip install --upgrade pip
E:\Python_Django>pip3 install virtualenv
E:\Python_Django>pip3 install virtualenv
E:\Python_Django>virtualenv pyDJ
E:\Python_Django>dir
E:\Python_Django>cd pyDJ
E:\Python_Django\pyDJ>cd script
E:\Python_Django\pyDJ\Scripts>activate
(pyDJ) E:\Python_Django>pip3 install Django
(pyDJ) E:\Python_Django>mkdir DJInventory
(pyDJ) E:\Python_Django>cd DJInventory
(pyDJ) E:\Python_Django\DJInventory>
(pyDJ) E:\Python_Django\DJInventory>django-admin startproject SIMS
(pyDJ) E:\Python_Django\DJInventory\SIMS>python manage.py startapp SIMSApp
PS E:\Python_Django\DJInventory\SIMS> pip install djangorestframework-simplejwt
PS E:\Python_Django\DJInventory\SIMS> python manage.py runserver
PS E:\Python_Django\DJInventory\SIMS> python manage.py createsuperuser
PS E:\Python_Django\DJInventory\SIMS> python manage.py makemigrations
PS E:\Python_Django\DJInventory\SIMS> python manage.py migrate SIMSApp 0001 
pip freeze > requirements.txt 
pip install python-dev-tools
git init
heroku create simsbackendapi(small character)
heroku git:remote -a simsbackendapi
git add .
git commit -m "react-create-app on Heroku"

git push heroku master
heroku open
---------------------database migration on heroku server
$ heroku run python manage.py makemigrations
heroku run python manage.py migrate