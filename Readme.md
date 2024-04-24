1. Publisher program akan mengirim 5 messages dalam sekali panggil. Setiap memanggil di `publish_event` akan dikirim satu message.

2. url `amqp://guest:guest@localhost:5672` sama dengan program subscriber karena keduanya akan terkoneksi ke AMQP message broker yang sama, yaitu RabbitMQ. publisher akan mengirim message untuk suatu queue atau topik, sedangkan subscriber akan menerima message dari queue atau topik tersebut.


#### running RabbitMQ
![alt text](image.png)
