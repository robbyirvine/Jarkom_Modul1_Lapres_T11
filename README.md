# Jarkom_Modul1_Praktikum_T11
Repositori sebagai Laporan Resmi Soal Praktikum Modul 1 Praktikum Komunikasi Data dan Jaringan Komputer 2020\
Disusun oleh :
```
Kelompok    :   T11
Anggota     :   I Gde Made Bhaskara Jala Dhananjaya (05311840000007)
                Robby Irvine Surya                  (05311840000023)
Departemen  :   Teknologi Informasi
```

# Daftar Isi
Jawaban | Soal | Praktikum | Modul 1 | Jarkom 2020 | 
------------ | ------------- | ------------- | ------------- | ------------- |
[Soal 1](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-1) | [Soal 2](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-2) | [Soal 3](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-3) | [Soal 4](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-4) | [Soal 5](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-4) | 
[Soal 6](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-6) | [Soal 7](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-7) | [Soal 8](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-8) | [Soal 9](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-9) | [Soal 10](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-10) | 
[Soal 11](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-11) | [Soal 12](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-12) | [Soal 13](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-13) | [Soal 14](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-14) | [Soal 15](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11#soal-15) |

## File Pendukung Soal
Terdapat tiga buah file ***.pcapng yang mendukung soal-soal display filter***, yaitu:
- File pertama untuk menjawab soal nomor 1-5 dan nomor 10.
- File kedua untuk menjawab soal nomor 6, 7, dan 9.
- File ketiga untuk menjawab soal nomor 8.

## Soal 1
Sebutkan webserver yang digunakan pada ***"testing.mekanis.me"***!

### Jawaban Soal
- Buka file ***soal_jarkom_modul1_no1-5,10*** di wireshark
- Command filter yang digunakan adalah ***http.host == "testing.mekanis.me"***
- Klik kanan di salah satu paket, klik ***follow***, dan klik ***TCP Stream***
- Hasil terlihat pada bagian server, dan webserver yang digunakan adalah `Server: nginx/1.14.0 (Ubuntu)`

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/1a.jpeg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/1b.jpg)

## Soal 2
Simpan gambar ***"Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpg"***!

### Jawaban Soal
- Buka file ***soal_jarkom_modul1_no1-5,10*** di wireshark
- Klik menu ***File***, klik ***Export Objects***, dan klik ***HTTP***
- Tuliskan `Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpg` di kolom text filter
- Simpan gambar di folder tertentu

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/2a.jpeg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/2b.jpg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/2c.jpg)

## Soal 3
Cari username dan password ketika login di ***"ppid.dpr.go.id"***!

### Jawaban Soal
- Buka file ***soal_jarkom_modul1_no1-5,10*** di wireshark
- Command filter yang digunakan adalah ***http.request.method == POST***
- Kemudian double klik pada salah satu paket, dan lihat di bagian ***HTML Form Url***
- Usernam dan Password sudah dimuat di halaman tersebut, yakni `Username = 10pemuda, Password = guncangdunia`

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/3a.jpg)

## Soal 4
Temukan paket dari web-web yang menggunakan ***basic authentication method***!

### Jawaban Soal
- Buka file ***soal_jarkom_modul1_no1-5,10*** di wireshark
- Command filter yang digunakan adalah ***http.authbasic***
- Double klik pada salah satu paket, keterangan Authentication terletak di bagian ***Hypertext Transfer Protocol***

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/4a.jpg)

## Soal 5
Ikuti perintah di ****aku.pengen.pw!**** Username dan password bisa didapatkan dari file ***.pcapng***!

### Jawaban Soal
- Buka file ***soal_jarkom_modul1_no1-5,10*** di wireshark
- Command filter yang digunakan adalah ***http.host == "aku.pengen.pw"***
- Double klik pada paket yang memiliki panjang ***574***
- Lihat pada bagian ***Authentication dan Credentials***
- Didapatkan username adalah `kakakgamtenk` dan password adalah `hartatahtabermuda`
- Kemudian akses ***aku.pengen.pw*** di browser, lalu masukan username dan password
- Jawab soal yang ada di halaman tersebut

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/5a.jpg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/5b.jpg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/5c.jpg)

## Soal 6
Seseorang menyimpan file zip melalui FTP dengan nama ****"Answer.zip"****. Simpan dan Buka file ***"Open This.pdf"*** di Answer.zip. Untuk mendapatkan password zipnya, temukan dalam file ***zipkey.txt*** (passwordnya adalah isi dari file txt tersebut).

### Jawaban Soal
- Buka file ***soal_jarkom_modul1_no6,7,9*** di wireshark
- Command filter yang digunakan adalah ***ftp-data contains Answer.zip***
- Klik kanan pada paket yang pertama didapatkan (Time Terkecil)
- Klik ***Follow*** lalu klik ***TCP Stream***
- Pada ***Stream*** di bagian kanan bawah, angka tersebut dikurangi ***1***
- Pada ***Show and save data as***, diganti dengan ***RAW***
- Save As sebagai ***Answer.zip***
- Untuk mencari password file ***Answer.zip***, buka file ***soal_jarkom_modul1_no6,7,9***
- Command filter yang digunakan adalah ***ftp-data contains zipkey.txt***
- Klik kanan pada paket yang pertama didapatkan (Time Terkecil)
- Klik ***Follow*** lalu klik ***TCP Stream***
- Pada ***Stream*** di bagian kanan bawah, angka tersebut dikurangi ***1***
- Passwordnya akan terlihat

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/6a.png)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/6b.png)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/6c.png)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/6d.png)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/6e.png)

## Soal 7
Ada 500 file zip yang disimpan ke FTP Server dengan nama ***1.zip, 2.zip, ..., 500.zip***. Salah satunya berisi pdf yang berisi puisi. ***Simpan* dan *Buka*** file pdf tersebut.

### Jawaban Soal
- Buka file ***soal_jarkom_modul1_no6,7,9*** di wireshark
- Command filter yang digunakan adalah ***ftp-data contains Yes.pdf***
- Klik kanan pada paket yang pertama didapatkan (Time Terkecil)
- Klik ***Follow*** lalu klik ***TCP Stream***
- Pada ***Show and save data as***, diganti dengan ***RAW***
- Save As sebagai ***Yes.zip***
- Extract file ***Yes.zip***
- file ***Yes.pdf*** akan terlihat

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/7a.png)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/7b.png)

## Soal 8
Cari objek apa saja yang ***didownload*** (RETR) dari koneksi FTP dengan ***Microsoft FTP Service***!

### Jawaban Soal
- Buka file ***soal_jarkom_modul1_no8*** di wireshark
- Command filter yang digunakan adalah ***ftp.request.command == RETR***
- Klik kanan pada paket yang pertama didapatkan (Time Terkecil)
- Klik ***Follow*** lalu klik ***TCP Stream***
- Objek-objek tersebut akan terlihat 

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/8a.png)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/8b.png)

## Soal 9
Cari username dan password ketika ***login FTP*** pada localhost!

### Jawaban Soal
- Buka file ***soal_jarkom_modul1_no6,7,9*** di wireshark
- Untuk melihat username, command filter yang digunakan adalah ***ftp.request.command == "USER"***
- Username akan terlihat yaitu ***dhana***
- Untuk melihat password, command filter yang digunakan adalah ***ftp.request.command == "PASS"***
- Password akan terlihat yaitu ***dhana123***

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/9a.png)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/9b.png)

## Soal 10
Cari ***file .pdf*** di wireshark lalu download dan buka file tersebut!
clue: "25 50 44 46".

### Jawaban Soal
- Buka file ***soal_jarkom_modul1_no1-5,10*** di wireshark
- Command filter yang digunakan adalah ***tcp contains 25:50:44:46***
- Klik ***Follow*** pada paket tersebut, lalu klik ***TCP Stream***
- Pada ***Show and save data as***, diganti dengan ***RAW***
- Save As sebagai file ***.pdf***
- Buka file ***.pdf*** tersebut

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/10a.png)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/10b.png)

## Soal 11
Filter sehingga wireshark hanya mengambil paket yang ***mengandung port 21***!

### Jawaban Soal
- Aktifkan ***FileZilla Server*** dan ***FileZilla Client***
- Buka wireshark dan aktifkan capture filter ***port 21***
- Buat user baru di FileZilla server
- Hubungkan ***FileZilla Client*** dengan ***FileZilla Server***
- Transfer file dari Client ke Server
- Port 21 telah terdeteksi di display

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/11a.jpg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/11b.jpg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/11c.jpg)

## Soal 12
Filter sehingga wireshark hanya mengambil paket yang ***berasal dari port 80***!

### Jawaban Soal
- Buka wireshark dan aktifkan capture filter ***src port 80***
- Akses ***ajk.if.its.ac.id*** di browser
- Paket yang difilter telah ditampilkan di display

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/12a.jpg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/12b.jpg)

## Soal 13
Filter sehingga wireshark hanya menampilkan paket yang ***menuju port 443***!

### Jawaban Soal
- Buka wireshark dan aktifkan capture filter ***dst port 443***
- Akses ***canva.com*** di browser
- Paket yang difilter telah ditampilkan di display

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/13a.jpg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/13b.jpg)

## Soal 14
Filter sehingga wireshark hanya mengambil paket yang ***berasal dari ip kalian***!

### Jawaban Soal
- Buka command prompt dan ketik ***ipconfig*** untuk mendapatkan IP Local
- Buka wireshark dan aktifkan capture filter ***src (IP Local)***
- Akses ***canva.com*** di browser
- Paket yang difilter telah ditampilkan di display

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/14a.jpg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/14b.jpg)

## Soal 15
Filter sehingga wireshark hanya mengambil paket yang ***tujuannya ke monta.if.its.ac.id***!

### Jawaban Soal
- Buka command prompt dan ketik ***ping*** + ***monta.if.its.ac.id***, didapatkan alamat IP dari website tersebut
- Buka wireshark dan aktifkan capture filter ***dst 103.94.190.11***
- Akses ***monta.if.its.ac.id*** di browser
- Paket yang difilter telah ditampilkan di display

### Dokumentasi Pengerjaan Soal
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/14b.jpg)
![](https://github.com/robbyirvine/Jarkom_Modul1_Praktikum_T11/blob/main/Dokumentasi%20Hasil%20Penyelesaian/15b.jpg)

