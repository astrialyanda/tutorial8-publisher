**a. How many data your publlsher program will send to the message broker in one run?** <br>
Program akan mengirimkan 5 data ke message broker dalam satu kali run. `publish_event` dilakukan sebanyak 5x. <br>

**b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?** <br>
Publisher dan subscriber memiliki url yang sama karena keduanya akan tersambung ke amqp yang sama yaitu RabbitMQ. Publisher mengirimkan message untuk queue sedangkan subscriber menerima message dari queue.