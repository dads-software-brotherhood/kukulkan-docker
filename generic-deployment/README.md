# Crear la imagen reverseproxy


`cd generic-deployment`

Crear la imagen reverseproxy

`docker build -t reverseproxy .`

Levantar la infraestructura completa

`docker-compose up -d`


navegar a http://localhost:8080 y después a http://localhost:8081


La referencia en Ingles está en:

http://www.bogotobogo.com/DevOps/Docker/Docker-Compose-Nginx-Reverse-Proxy-Multiple-Containers.php

