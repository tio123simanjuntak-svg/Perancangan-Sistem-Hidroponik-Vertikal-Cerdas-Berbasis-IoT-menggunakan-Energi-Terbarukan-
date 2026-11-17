Keterbatasan lahan, perubahan iklim, dan tingginya kebutuhan energi menjadi tantangan dalam pertanian modern. Proyek ini merancang sistem hidroponik vertikal cerdas yang hemat lahan, efisien, dan ramah lingkungan.
Tujuannya yaitu, membangun sistem hidroponik vertikal yang dapat dipantau dan dikontrol secara otomatis melalui IoT, serta ditenagai energi terbarukan (panel surya) agar berkelanjutan.

⚙️ Cara Kerja Sistem
1. Sensor suhu, kelembapan, TDS, membaca kondisi lingkungan dan nutrisi tanaman.
2. ESP32 memproses data dan mengendalikan pompa secara otomatis maupun manual.
3. Data dikirim ke server dan database, lalu ditampilkan pada dashboard web secara real-time.
4. Panel surya dan baterai menyuplai daya sistem, dengan status pengisian dan level baterai yang ikut dipantau.

🛠️ Tools & Teknologi yang Digunakan
a. Perangkat Keras (IoT)

1. ESP32 sebagai mikrokontroler dan modul WiFi
2. Sensor suhu & kelembapan (misalnya DHT22)
3. Sensor TDS 
4. Pompa air dengan modul relay
5. Panel surya, baterai, dan modul pengisian (solar charger)
6. Sensor arus/tegangan untuk memantau panel surya dan baterai

b. Pengembangan Web

1. Frontend: HTML, CSS, JavaScript
2. Backend: [PHP / Node.js / Python Flask]
3. Database: [MySQL / Firebase]
4. Komunikasi data: [HTTP REST API / MQTT]

c. Perangkat Lunak Pendukung

1. Arduino IDE / PlatformIO untuk pemrograman ESP32
2. Visual Studio Code sebagai code editor
3. GitHub untuk version control
