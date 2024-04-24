**a. How many data your publlsher program will send to the message broker in one run?** <br>
Program akan mengirimkan 5 data ke message broker dalam satu kali run. `publish_event` dilakukan sebanyak 5x. <br>

**b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?** <br>
Publisher dan subscriber memiliki url yang sama karena keduanya akan tersambung ke amqp yang sama yaitu RabbitMQ. Publisher mengirimkan message untuk queue sedangkan subscriber menerima message dari queue.

**Running RabbitMQ as message broker**
![alt text](<Screenshot (782).png>)

**Sending and and processing events**
![alt text](<Screenshot (785).png>) <br>
![alt text](<Screenshot (787).png>) <br>
Gambar ini menunjukkan ketika publisher di run. Publisher akan mengirimkan data, lalu subscriber yang tersambung akan menampilkan message di console.