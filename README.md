pip install -r requirements.txt

python manage.py migrate

python manage.py createsuperuser --username teaba --email teaba@ayar.com

python manage.py drf_create_token teaba

python manage.py runserver

http://127.0.0.1:8000/hello/ >>> authentiation error !!!

##to be authinticated
1-download modheader extension for your browser ( i use chrome )
2- check my messages on messenger
