# Crear la imagen reverseproxy


`cd generic-deployment`

Crear la imagen reverseproxy

`docker build -t reverseproxy .`

Levantar la infraestructura completa

`docker-compose up -d`


navegar a http://localhost:8080 y después a http://localhost:8081
