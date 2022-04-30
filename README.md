<h1>BigBookSmallPythonProjects / Django-rest examples</h1>

<p>to start django rest:</p>
<p>cd django_rest</p>
<p>python manage.py runserver</p>
<p>to start another app run: python manage.py startapp {app_name}</p>

<p>To run any command inside your app prefix it with</p>

```
 docker compose run web ${command}
```

<p>docker-compose run web python manage.py makemigrations polls</p>
<p>docker-compose run web python manage.py migrate</p>

To access database run:

```
docker exec -it django_db_1 psql -U postgres
```
