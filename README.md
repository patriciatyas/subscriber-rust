# Module 9 Reflection

Patricia Herningtyas - 2306152241

### What is amqp?
AMQP (Advanced Message Queuing Protocol) adalah protokol komunikasi standar terbuka yang digunakan untuk pertukaran pesan antar aplikasi atau komponen sistem secara asinkron. Dalam kode tutorial ini, AMQP digunakan sebagai protokol transportasi oleh library CrosstownBus untuk mengirim dan menerima pesan melalui sistem antrian pesan, yang memungkinkan komponen aplikasi berkomunikasi tanpa harus saling terhubung secara langsung.


### What does it mean? guest:guest@localhost:5672, what is the first guest, and what is the second guest, and what is localhost:5672 is for?
String koneksi "amqp://guest:guest@localhost:5672" adalah URL untuk menghubungkan ke server AMQP dengan format [protokol]://[username]:[password]@[host]:[port]. "guest" pertama adalah username default untuk autentikasi ke server AMQP. "guest" kedua adalah password default untuk autentikasi. "localhost:5672" menunjukkan bahwa server AMQP berjalan pada localhost dan dapat diakses melalui port 5672 yang merupakan port default untuk koneksi AMQP.