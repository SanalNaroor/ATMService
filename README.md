# ATMService
To test Moq implementation

I have written a fresh WCF service and a console application to consume that as I dint had any already written application in my home computer. I have uploaded the same in the GitHub at the below mentioned link. This link also contains the JavaScript implementation.

https://github.com/SanalNaroor/ATMService

1.	While implementing this service I have used Ninject for dependency injection, as out of the box WCF does not support a parameterized constructor for the service. 
2.	I have used repository pattern so as to make the database pluggable. 
3.	I have implemented the logging support in the service however, it is not enabled.
4.	I have used Moq framework for the unit test. I have done unit test only for the repository class as the major portion of the logic stays there.
5.	Due to the time constraint , I have stubbed the data within the data access.
6.	The I have done one round of unit testing not a rigorous one.

For the javascript function please download Script.html from the github link mentioned above.

