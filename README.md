# dercio-food
Back End microservices for dercio-food app.

In this project I implemented a back end composed by two microservices: Food Request and Payments.
I mounted the two microservices, built the APIs, used isolated data bases, and separated the packages by layers of responsability.
Used migrations to create SQL and version the the Data Bases. 
Also, with Service Discovery and Registry, registed the microservices so that they could discover each other by the names only, using Eureka.
Even implemented Load Balancing and included Gateway to the App, and elaborated syncronous comunication beteween the two microservices.
Dealth with failures when Food Request service is down.
