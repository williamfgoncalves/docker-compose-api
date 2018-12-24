## Docker Compose: Node API

This application is a use case of studies Docker Compose.

I create this application with Node and Jquery. The database of use is MongoDB.

The objective of my application is created CRUD comands of clients.

My docker compose create a 3 containers, one container of my backend in NodeJS, one container of my Frontend with Nginx and one container of my database with MongoDB.

I expose my Backend in PORT 3000 and my Frontend in PORT 80.

To running this application in your local machine apply this comands in root path:
 
 - `docker-compose up`

 Note: You should have **Docker** and **Docker-Compose** installed on your local machine