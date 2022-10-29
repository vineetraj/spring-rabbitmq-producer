# spring-rabbitmq-producer
A simple producer-consumer pattern application.

-----------------
### How to Use :
-----------------

#### Run the following Docker commands in terminal :
docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management

docker ps 

- Now, it will show the container named as 'some-rabbit' running in terminal.
------------------------------------------------------------------------------------------------------------

- Login to http://localhost:15672/
Enter username & password as 'guest'
You will be able to see the RabbitMQ dashboard.
------------------------------------------------------------------------------------------------------------

- Run this application in intelliJ IDEA.
------------------------------------------------------------------------------------------------------------

- Send Post request via Postman or any other rest client on:
http://localhost:9000/publish with your message body
-------------------------------------------------------------------------------------------------------------

- Run the spring-rabbbitmq-consumer application in intelliJ IDEA.
You will be able to see the message in that application console.
