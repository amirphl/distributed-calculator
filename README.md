# distributed calculator
a distributed calculator written in java
## Execution
* First, run server part:
```
java -jar receiver.jar <port>
```
* now run client:
```
java -jar sender.jar <ip-of-receiver> <port-of-receiver>
```

## Example on localhost
```
java -jar receiver.jar 56478
java -jar sender.jar 127.0.0.1 56478
``` 

## Note
only one client can connect to server.