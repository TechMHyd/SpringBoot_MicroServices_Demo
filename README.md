# SpringBoot_MicroServices_ShoppingCart

This Shopping cart Application is designed to Handle Micro Services Functionality. 

Prerequisites
We must have installed the following
•	JDK 1.7 or later
•	Maven 3 or later

Steps to Execute the Poject :
1.Load the maven Projects in Ecclipse IDE.
2.download SpringbootPlugIn for the Market Place
3.Right click on Maven Project > Run as > Maven Install   to resolve the dependencies.
4.Right click on the Project > Run as > springBoot Application.

open browser access : http://localhost:/8000   : Application is running and Project Micro services loads the list of available items from the Product catalog.

All the Services are running on different ports.
We have Integrated JWT Token for authentication and autharization of User. 
1.UI Module Service is responsible for generating JWT Token and shares the token to target services via headers .
2.In the Target Service we parse/validates the JWT Token.
3.On sucessful validatioon of JWT Token , Application  will provides the access to the target service.
