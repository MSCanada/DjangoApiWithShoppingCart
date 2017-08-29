A Shopping Cart developed with Django Python used to purchase items online, 
Tools: Python, Django, Django Rest 


To Run:
python manage.py runserver

URL: localhost:8000/
API EndPoint: localhost:8000/api/
curl http://localhost:8000/api/tasks/
curl -X POST http://localhost:8000/api/tasks/ -d "title=hello world&description=a whole new world"
curl -X PUT http://localhost:8000/api/tasks/1 -d "title=hello world&description=be nice"
curl -X PUT http://localhost:8000/api/tasks/1 -d "title=hello world&description=be nice&completed=True"
curl -X DELETE http://localhost:9000/api/tasks/1

Reference: https://godjango.com/41-start-your-api-django-rest-framework-part-1/
