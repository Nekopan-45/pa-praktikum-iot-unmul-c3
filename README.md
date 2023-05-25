# pa-praktikum-iot-unmul-c6
Nama Anggota Kelompok 3 PA IoT:
1. Yanuar Satria Gotama 		      | 2009106013
2. Rivan Abdillah 			          | 2009106025
3. Patricia Chandra 			        | 2009106030
4. Muhammad Rifky Cahyadi Sukri	  | 2009106043

Judul: “MONITORING DAN CONTROLLING SISTEM ANTI MALING”

Deskripsi:
Dalam upaya untuk meningkatkan keamanan rumah, telah dikembangkan sistem yang menggunakan sensor gerak PIR, buzzer, led, dan kontrol smartphone. Sensor gerak akan mendeteksi pergerakan mencurigakan dan memicu bunyi alarm buzzer yang keras. Pengguna juga dapat mengendalikan sistem ini melalui smartphone mereka untuk memberikan perlindungan yang lebih baik terhadap properti pribadi. Sistem ini memberikan solusi praktis dan efektif dalam mencegah tindakan pencurian.

Pembagian Tugas per individu:
1. Persiapan alat (Rifky, Yanuar)
2. Codingan Publisher (Rivan)
3. Codingan Subscriber (Rifky)
4. Pengerjaan board (Rifky, Rivan)
5. Manual book (Patricia, Yanuar)

Komponen yang Digunakan:
1. NodeMCU x 1
2. Breadboard x 2
3. Kabel Jumper Male - Male x 3
4. LED x 1
5. Resistor x 1
6. Buzzer x 1
7. Sensor gerak PIR x 1

Konsul 1 PA IoT / Tanggal 28 April 2023
Aslab Pembimbing : Bang Fahri

Tema	
Monitoring dan Controlling Sistem Anti Maling

Konsep	
Sistem dapat memonitoring serta menghasilkan sinyal berupa suara serta cahaya saat terdeteksi adanya pergerakan yang diterima dari sensor PIR

Cara Kerja
Pengguna sistem dapat menetapkan rentang waktu alarm anti maling tersebut aktif, contohnya saat bepergian keluar rumah dan lainnya.

Jika sistem telah diaktifkan dengan rentang waktu yang telah ditetapkan maka, alat akan mendeteksi bila terjadi pergerakan. Apabila terdeteksi pergerakan pada sensor PIR tersebut, maka buzzer serta lampu led akan menyala dan sistem akan mendapat peringatan bahwa telah terdeteksi pergerakan pada sensor tersebut.


Metode IoT
Sistem dapat dikendalikan menggunakan platform MQTT Panel. Sistem ini dapat mengatur rentang waktu pengaktifan, memonitor output dari alat pendeteksi gerakan tersebut, dan memberikan output peringatan. Sistem ini menggunakan protokol MQTT. (Message Queuing Telemetry Transport)


Komponen yang digunakan
PCB Lubang/Breadboard, Sensor Gerak (PIR), Buzzer, Node MCU, Resistor, Kabel Jumper, LED

BOARD SCHEMATIC
![image](https://github.com/Rifkycahyadi/pa-praktikum-iot-unmul-c6/assets/74778010/8f7d6adf-0df7-43e4-849f-a8eccd3904bd)
![image](https://github.com/Rifkycahyadi/pa-praktikum-iot-unmul-c6/assets/74778010/febefcec-d262-4b60-8441-d5c3bc9a0685)

