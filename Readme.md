1. Publisher program akan mengirim 5 messages dalam sekali panggil. Setiap memanggil di `publish_event` akan dikirim satu message.

2. url `amqp://guest:guest@localhost:5672` sama dengan program subscriber karena keduanya akan terkoneksi ke AMQP message broker yang sama, yaitu RabbitMQ. publisher akan mengirim message untuk suatu queue atau topik, sedangkan subscriber akan menerima message dari queue atau topik tersebut.


#### running RabbitMQ
![alt text](image.png)

#### sending and processing event
![alt text](image-1.png)
![alt text](image-2.png)
menunjukkan kondisi pengiriman dan pemrosesan event yaitu pengiriman message queue ketika publisher di run. Subscriber yang sedang terhubung menangkap message tersebut dan mencetaknya di terminal

#### monitoring chart
![alt text](image-3.png)
terdapat spike pada chat yang menandakan terjadinya event pada interval waktu spike tersebut terbentuk