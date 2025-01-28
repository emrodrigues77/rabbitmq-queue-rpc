# RabbitMQ RPC Queue

PHP simplest study on RabbitMQ RPC queues, with a basic UI for receiving results. 

## How to run

### Run RabbitMQ
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:4.0-management

### To start server
php rpc_server.php

### To request a fibonacci number run the client:
php rpc_client.php

### To see a fibonacci number in the UI
Start the server and navigate to index.html
