#Account service:
![Account Service](images/account_service1.jpg "Account Service")
![Account Service](images/account_service1b.jpg "Account Service")

#Web service:
![Web Service](images/web_service1.jpg "Web Service")
![Web Service](images/web_service1b.jpg "Web Service")

#The service registration service has the two microservices registered:
![Registration Service](images/registration_service.jpg "Web Service")
![Registered 2 microservices](images/registered2microservices.jpg "Registered 2 microservices")

#A second account microservice is running in the port 4444 and it is registered:
![Account Service 2](images/account_service2.jpg "Account Service 2")
![Registered 3 microservices](images/registered3microservices.jpg "Registered 3 microservices")

#A brief report describing what happens when you kill the microservice with port 2222. Can the web service provide information about the accounts? Why?
When that microservice is closed, it returns a refused connection, then it asks the register service in order to obtain a working accounts service, and it responds with the service of port 4444.
