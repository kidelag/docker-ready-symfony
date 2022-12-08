1. docker-compose up -d
2. docker exec -it www_docker_symfony bash
   3. cd html/
   4. composer create-project symfony/skeleton:"6.2.*" project 
   5. cd project
   6. composer require webapp

Go to http://localhost:8741/