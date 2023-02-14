# CS-361
CS 361 Project - Microservices Contract

REQUEST DATA
- In order to request data I'll be using Python Sockets, so you need to make sure the localhosts are both the same to be able to request data. You will need to send a request to the server which will display a message that it is receiving a request and that it will generate a random quote that will be requested back to ZenQuotes' API.
<img width="300" alt="Screen Shot 2023-02-13 at 9 13 09 PM" src="https://user-images.githubusercontent.com/102687363/218650001-9112d3bb-0b05-49da-9447-507480536438.png">


RECEIVE DATA
- In order to receive data I had to bind the socket with the same localhost as the clients side and it will stay waiting for about 3 seconds before it can receive the response as the time.sleep is set to 3 seconds. The quote will then be stored for the client.

<img width="300" alt="Screen Shot 2023-02-13 at 9 45 56 PM" src="https://user-images.githubusercontent.com/102687363/218650129-022828bb-3440-4809-86c4-f42b558849b5.png">

UML REPRESENTATION
This is the UML Representation of how the Client requests and receives data to the Server but also how the Server receives it's quotes from ZenQuotes API and returns it back to the client.
<img width="300" alt="Screen Shot 2023-02-13 at 9 41 30 PM" src="https://user-images.githubusercontent.com/102687363/218650062-d25a0b35-4ea3-4157-9040-c82bb8c28630.png">
