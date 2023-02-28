# Inner-Circle-Reverse-Proxy
Docker service for local development of the Inner-Circle project

# Install
To use this service, you need to install:
1. [**Docker**](https://www.docker.com/)

# Before you start 
Make sure the following services are locally deployed on your computer: 
1. [**Inner-Circle-Auth**](https://github.com/TourmalineCore/Inner-Circle-Auth) 
2. [**Inner-Circle-Ui**](https://github.com/TourmalineCore/Inner-Circle-UI)
3. [**Inner-Circle-Account-Management**](https://github.com/TourmalineCore/Inner-Circle-Account-Management)

# Start 
Run the command 
```
docker compose up -d
```

After open **localhost:7000**. Now on this localhost you will redirect traffic. The changes you make in the code will automatically be updated 
