# CS-361
CS 361 Project - Microservices Contract

REQUEST DATA
- In order to request data I'll be using Python Sockets, so you need to make sure the localhosts are both the same to be able to request data. You will need to send a request to the server which will display a message that it is receiving a request and that it will generate a random quote that will be requested back to ZenQuotes' API.


RECEIVE DATA
- In order to receive data I had to bind the socket with the same localhost as the clients side and it will stay waiting for about 3 seconds before it can receive the response as the time.sleep is set to 3 seconds. The quote will then be stored for the client.

UML REPRESENTATION
