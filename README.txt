# DJANGO BLOG

docker-compose build docker-compose up

docker-compose run web python dj_test/manage.py makemigrations docker-compose run web python dj_test/manage.py migrate

docker-compose run web python dj_test/manage.py makemigrations blog docker-compose run web python dj_test/manage.py migrate blog

docker-compose run web python dj_test/manage.py createsuperuser