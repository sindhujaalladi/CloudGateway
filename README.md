# CloudGateway

This cloud gateway is acts as one of the microservice client and it is registered in service registry

example : if any incoming request if contains /order then gateway will navigate that request to OrderService
if any incoming request contains /payment then gateway will naviagte that request to payment service

we will fire the url with port number mentioned in cloud gateway since we mention client services and their url's in cloud gateway .
![image](https://user-images.githubusercontent.com/115841974/205545273-eefc917b-133b-41f5-aa71-91c904734cf5.png)


![image](https://user-images.githubusercontent.com/115841974/205545343-4e076660-3397-4476-aca3-c32bfe67aa1d.png)

this is piece of code where we have mentioned to naviagte the request to corresponding services with url matched.
