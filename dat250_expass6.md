### Experiment 1: Installation
Chose to do the local installation

### Experiment 2: Hello World
Code: 
<br>
[Receive](https://github.com/vetlemknutsen/DAT250_RabbitMQ/blob/main/src/main/java/org/example/hello_world/Recv.java)
<br>
[Send](https://github.com/vetlemknutsen/DAT250_RabbitMQ/blob/main/src/main/java/org/example/hello_world/Send.java)


Sending hello world: 
<br>
![](images/sent_hello.png)
<br>

Receiving hello world: 
![](images/receive_hello.png)


### Experiment 3: Work Queues
Code: 
<br>
[NewTask](https://github.com/vetlemknutsen/DAT250_RabbitMQ/blob/main/src/main/java/org/example/work_queues/NewTask.java)
<br>
[Worker](https://github.com/vetlemknutsen/DAT250_RabbitMQ/blob/main/src/main/java/org/example/work_queues/Worker.java)

Worker 1 receives first, third and fifth tasks:
<br>
![](images/worker2.png)
<br>
Worker 2 receives second, fourth and last tasks:
<br>
![](images/worker1.png)


### Experiment 4: Topics
Code: 
<br>
[EmitLog](https://github.com/vetlemknutsen/DAT250_RabbitMQ/blob/main/src/main/java/org/example/topics/EmitLog.java)
<br>
[ReceiveLogs](https://github.com/vetlemknutsen/DAT250_RabbitMQ/blob/main/src/main/java/org/example/topics/ReceiveLogs.java)



### Issues
Encountered some problems when trying to run the program as i missed
some dependencies and I had to refresh maven. After that, everything went smooth. 