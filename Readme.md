# RabbitMQ demo in c#
## Window 10 Command Prompt
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