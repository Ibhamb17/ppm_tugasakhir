
# tugasakhir_psm


Nama : Ibham Bathsyi Hizbullah
NIM : 1207050143

Pada tugas akhir ini saya membuat mini aplikasi dengan tampilan GUI sederhana menggunakan bahasa pemgrograman python.

Aplikasi yang saya buat terdiri dari 3 fitur yaitu sebagai berikut.
1. Hapus backgrounnd image menggunakan fungsi remove pada library rembg untuk menghapus background dan juga menggunakan library PIL untuk memanipulasi gambar sebelum dihapus backgroundnya.
2. Gabung 2 Audio File.
3. Konversi format Audio.
Pada fiture no 2 dan 3 menggunakan fungsi AudioSegment pada library pydub. Dimana penggabungan audio dan konversi menggunakan teknik segmentasi yang dimana algoritmnyanya sudah tersedia pada library tersebut.

Adapun untuk tampilan GUInya saya menggunakan beberapa library seperti tkinter.

lalu mmodul 'os digunakan agar fitur apliaksi program python yang saya buat bisa dijalankan pada sistem operasi menggunakan visual studio code.

Cara menjalankan aplikasi.
1. install python di https://www.python.org/downloads/. install pyhton versi 3.11 kebawah. Disini saya menggunakan python versi 3.10, dikarenakan untuk versi terbaru yaitu versi 3.11 tidak mendukung library 'rembg'.
2. install visual studio code ataupun code editor lainnya.
3. Download source code dari repository ini https://github.com/Ibhamb17/psm_tugasakhir 
4. Buka folder dengan visual studio code.
5. sebelum menjalankan aplikasi ada beberapa library yang sudah diinstall.
6. buka CMD, lalu ubah directory menjadi path c:\users\(nama kopmuter/laptop kalian). Path komputer saya adalah c:\users\12070
7. setelah masuk ke path install beberapa library dengan mengetikan script dibawah pada cmd.
pip install pydub
pip install rembg
pip install tkinter
pip install easygui
8. setelah semua terinstall buka visual studio code.
9. open direktori masuk ke folder yang sudah diunduh di repository git https://github.com/Ibhamb17/psm_tugasakhir
10. Run tugas_akhir.py
 maka akan masuk ke tampilan dibawah
 
Tampilan awal :
![Screenshot (663)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/9467baa4-6e24-41b9-bfdd-969568e0354b)


Demo Aplikasi terdapat pada link youtube dibawah :

hasil :
Tampilan awal :
![Screenshot (663)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/9467baa4-6e24-41b9-bfdd-969568e0354b)


# Demo Aplikasi Hapus Background
Demo fitur hapus background :
1. klik tombol hapus background, lalu pilih gambar mana yang akan dihapus backgroundnya, lalu tekan open
![Screenshot (664)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/a72052c3-5e15-49e7-9664-8e82512b5a05)
2. beri nama file dengan format namafile.png. lalu tekan tombol save.
![Screenshot (665)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/ef7ee4ec-8187-4422-8cfe-e6aedc827ba6)

Hasil Demo :

sebelum dihapus background
![ibham](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/d130dacd-ebbd-45e5-bb7c-4f5c6458cba9)

setelah dihapus background
![dihapus](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/6183f1fd-85c0-4a8a-858c-33f9f4ced27e)


#Demo Aplikasi Penggabungan Audio
1. Pilih menu gabungkan audio pada menu 

![Screenshot (663)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/35cb586a-6d75-4ef5-a063-75d555fc8760)

2. pilih audi pertama yang akan digabung
![Screenshot (667)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/a133cdae-5831-4909-82ac-ac222e155e2e)

3. pilih audio kedua yang akan digabung
![Screenshot (668)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/9fb23874-4d75-44c8-a8c7-fb997a16350e)

4. save audio dan pilih fodler untuk menyimpan, lalu tekan save.

5. jika berhasil akan terlihat seperti gambar!
[Screenshot (669)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/140ee71c-d326-4022-8261-08bc7db60316)



#demo konversi format audio (mp3 to wav)
1. Tekan menu konversi audio!

[Screenshot (663)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/061504d4-39d8-4f0b-944a-6caf40dc9c4c)

2. pilih audio yang akan dikonversi formatnya.

![Screenshot (672)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/9a9f6022-8a55-4d39-8b8b-b666c3b04b57)

3. berinama file dengan eksistensi sesuai keinginan namafile.mp3/ogg/wav
![Screenshot (674)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/7c4bb2a0-a4ee-4cd8-be88-080451c73b73)

4. jika berhasil maka akan muncul pesan seperti pada gambar dibawah.

![Screenshot (675)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/211493bd-0160-416d-90ce-aeebdd9ad8b4)


Pembuatan tugas akhir ini dibantu oleh beberapa konten dari kreator 'kelas terbuka" (youtube) saat belajar menampilkan aplikasi GUI dengan python.
