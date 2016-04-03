#Tutorial djangogirls
http://tutorial.djangogirls.org/pt/
http://tutorial.djangogirls.org/pt/django_orm/

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

#deploy server pythonanywhere
http://tutorial.djangogirls.org/pt/deploy/
http://pythonanywhere.com/
krol / =
http://krol.pythonanywhere.com/admin/

virtualenv --python=python3.4 myvenv
source myvenv/bin/activate
##coleta de arquivos estaticos
pip install django whitenoise
python manage.py collectstatic

python manage.py migrate
python manage.py createsuperuser
krol3 / email

krol.pythonanywhere.com
virtualenv : /home//my-first-blog/myvenv/
 which python
/home/krol/djangogirls/myvenv/bin/python

WSGI protocol

## update in the cloud
git pull
python manage.py collectstatic

#Recursos :

https://github.com/ggcarrots/django-carrots
http://django-marcador.keimlink.de/



