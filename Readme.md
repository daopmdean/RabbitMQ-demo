# RabbitMQ demo in c#
## Installation
Programs path on windows 10
```
C:\Users\daopm\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\RabbitMQ Server
```
## Window 10 Command Prompt
Enable rabbitmq management with RabbitMQ Command Prompt
```
rabbitmq-plugins enable rabbitmq_management
```
Track acknowledgment, if forgot BasicAck method, RabbitMQ could consume your RAM
```
rabbitmqctl list_queues name messages_ready messages_unacknowledged
```
To list the exchanges on the server
```
rabbitmqctl list_exchanges
```
You can list existing bindings using
```
rabbitmqctl list_bindings
```