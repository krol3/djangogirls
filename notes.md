#Tutorial djangogirls
http://tutorial.djangogirls.org/pt/

python3 python_intro.py

#virtualenv

python --version 
mkproject djangogirls -p /usr/bin/python3

pip install django==1.8.5

django-admin startproject mysite .

python manage.py migrate

##run the app
python manage.py runserver

##criar um aplicativo separado dentro do nosso projeto blog
python manage.py startapp blog

###adicionar nosso novo modelo para nosso banco de dados
python manage.py makemigrations blog

###Django prepara um arquivo de migração que temos de aplicar agora para nosso banco de dados
python manage.py migrate blog

### criar um superuser
python manage.py createsuperuser
admin / admin

#deploy server
http://pythonanywhere.com/
krol / =
virtualenv --python=python3.4 myvenv
source myvenv/bin/activate
##coleta de arquivos estaticos
pip install django whitenoise
python manage.py collectstatic


#git

#Recursos :

https://github.com/ggcarrots/django-carrots
http://django-marcador.keimlink.de/

Author, Twisted chapter for The Architecture of Open Source Applications, Volume II
http://web.mit.edu/jesstess/www/

