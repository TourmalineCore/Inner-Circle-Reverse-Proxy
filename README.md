# Inner-Circle-Reverse-Proxy
We develop different parts of the frontend in isolation, but we want to bring all those parts together into one application.
In order to do that we configured reverse-proxy, the rules of which are described [**here**](https://github.com/TourmalineCore/Inner-Circle-Reverse-Proxy/blob/master/nginx.conf).
Depending on the route a certain part of the frontend gets rendered. This behavior allows us to handle a set of applications as a single

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
