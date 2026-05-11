**a. How much data your publisher program will send to the message broker in one run?**
Dalam satu kali eksekusi (`cargo run`), program ini mengirimkan 5 buah data event (Amir, Budi, Cica, Dira, dan Emir) ke message broker.

**b. The url of: "amqp://guest:guest@localhost:5672" is the same as in the subscriber program, what does it mean?**
Hal ini menandakan bahwa publisher dan subscriber saling terhubung melalui instans RabbitMQ yang sama persis. Publisher menulis pesan ke dalam antrean di broker tersebut, dan subscriber akan mengeksekusi (*consume*) antrean di broker yang identik.

## Running RabbitMQ as message broker
![alt text](image.png)

## Sending and processing event
![alt text](image-1.png)

## Monitoring chart based on publisher
![alt text](image-2.png)
