# shopMicroServices
Microservice architecture implementation

I will implement example microservice architecture and investigate advantages and disadvantages of this architecture.
This repo will be updated step by step. This is my microservice Journey :)


# Install MongoDb for Catalog Services

- docker pull mongo
- docker run -d -p 27017:27017 --name shopping-mongo mongo

to check if mongo is running

- docker ps

730dccaddaae   mongo     "docker-entrypoint.s…"   4 minutes ago   Up 4 minutes   0.0.0.0:27017->27017/tcp, :::27017->27017/tcp   shopping-mongo

you should see the result something like that..

- docker exec -it shopping-mongo /bin/bash  // -it parameter means interactive terminal
