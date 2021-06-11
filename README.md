# python-django-bookstore-api-jwt

API Rest created with Python &amp; Django to manage data from a PostgreSQL database with JWT


Routes availables of this API:

`/admin` This is the dashboard that comes with Django to manage data.

`/api` This is the main route of my API

  - `/authors` GET, POST, PATCH, DELETE

  - `/books` GET, POST, PATCH, DELETE

  - `/users` GET, POST, PATCH, DELETE
  
  - `/welcome` This is a route that return a welcome message
  
`/registration` This is the route to register users
`/login` This is the route to login that returns a token
`/logout` This is the route to logout
