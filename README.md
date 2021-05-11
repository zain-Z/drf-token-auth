pip install -r requirements.txt

python manage.py migrate

python manage.py createsuperuser --username zain --email zain@api.com

python manage.py drf_create_token zain

python manage.py runserver

http://127.0.0.1:8000/hello/ >>> authentiation error !!!

##to be authinticated
1-download modheader extension for your browser ( i use chrome )
