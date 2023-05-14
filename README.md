
# jawaban job interview


Nama : Ibham Bathsyi Hizbullah
NIM : 1207050143


Pada tugas akhir ini saya membuat mini aplikasi dengan tampilan GUI sederhana menggunakan bahasa pemgrograman python.
Pada tugas akhir yang saya buat yaitu memuat hapus background sebuha image. Penggunaan aplikasinya yaitu sebagai berikut

1. User mengunggah image yang akan dihapus backgroundnya.
2. User menekan tombol "delete bg".
3. Setelah background dihapus, user bisa menekan tombol "unduh" untuk mengunduh gambar yang sudah dihapus backgroundnya.
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

# No 1
# Demo Aplikasi Hapus Background
url youtube : https://youtu.be/3WtYrsZmI4Q 

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

# No 2
Cara kerja image processing pada aplikasi yang saya buat adalah sebagai berikut.
Aplikasi ini menggunkan algoritma edge base segmentasi, dimana pada Teknik ini mendeteksi tepi (tracking garis) dalam gambar dan kemudian mencari jalur tepi yang kontinu. Semua elemen yang berada di luar jalur tersebut dianggap sebagai latar belakang. setelah latar belakang teridentifikasi latar belakang tersebut didefinisikan sebagai objek yang dihapus. penghapusan objek tersebut menggunakan modul PIL yang berfungsi untuk memanipulasi gambar.
Deskripsi Algoritma:
1. Pengguna menjalankan fungsi hapus_bg() dengan mengklik tombol atau memanggil fungsi secara manual.
2. Program akan mencoba mengimpor modul rembg yang diperlukan untuk menghapus latar belakang gambar.
3. Pengguna akan diminta untuk memilih gambar input menggunakan dialog file yang disediakan oleh easygui.fileopenbox().
4. Pengguna akan diminta untuk memilih lokasi dan nama file untuk menyimpan gambar hasil penghapusan latar belakang menggunakan dialog file yang disediakan oleh easygui.filesavebox().
6. Gambar input akan dibuka menggunakan PIL.Image.open() dan disimpan dalam variabel input.
7. Proses penghapusan latar belakang akan dilakukan menggunakan fungsi remove() dari modul rembg, dengan parameter gambar input.
8. Gambar hasil penghapusan latar belakang akan disimpan menggunakan output.save(outputPath), di mana output adalah hasil dari pemanggilan remove(), dan outputPath adalah lokasi file yang dipilih oleh pengguna.
10. Pesan berhasil akan ditampilkan menggunakan messagebox.showinfo() untuk memberi tahu pengguna bahwa latar belakang berhasil dihapus.
11. Jika terjadi kesalahan selama proses, pesan error akan ditampilkan menggunakan messagebox.showerror() dengan pesan kesalahan yang spesifik.


# No 3
Aspek kecerdasan buatan pada aplikasi yang saya buat yaitu terdapat pada modul Rembg yang disediakan oleh pemrograman python itu sendiri dimana terdapat pengimplementasian teknik segmentasi alpha dengan deeplearning untuk mengidentifikasi objek manusia dan objek yang bukan manusia. Setelah identifikasi selesai lalu digunakan algoritma edge-based seggmentation seperti yang dipaparkan pada soal no 2.

# No 4
url youtube : https://youtu.be/3WtYrsZmI4Q (menit ke 2:09)

# Demo Aplikasi Penggabungan Audio

url youtube : https://youtu.be/3WtYrsZmI4Q (menit ke 2:11)

1. Pilih menu gabungkan audio pada menu 

![Screenshot (663)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/35cb586a-6d75-4ef5-a063-75d555fc8760)

2. pilih audi pertama yang akan digabung
![Screenshot (667)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/a133cdae-5831-4909-82ac-ac222e155e2e)

3. pilih audio kedua yang akan digabung
![Screenshot (668)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/9fb23874-4d75-44c8-a8c7-fb997a16350e)

4. save audio dan pilih fodler untuk menyimpan, lalu tekan save.

5. jika berhasil akan terlihat seperti gambar!

[Screenshot (669)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/140ee71c-d326-4022-8261-08bc7db60316)



# Demo konversi format audio (mp3 to wav)

url youtube : https://youtu.be/3WtYrsZmI4Q (menit ke 3:56)

1. Tekan menu konversi audio!

[Screenshot (663)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/061504d4-39d8-4f0b-944a-6caf40dc9c4c)

2. pilih audio yang akan dikonversi formatnya.

![Screenshot (672)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/9a9f6022-8a55-4d39-8b8b-b666c3b04b57)

3. berinama file dengan eksistensi sesuai keinginan namafile.mp3/ogg/wav
![Screenshot (674)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/7c4bb2a0-a4ee-4cd8-be88-080451c73b73)

4. jika berhasil maka akan muncul pesan seperti pada gambar dibawah.

![Screenshot (675)](https://github.com/Ibhamb17/psm_tugasakhir/assets/78264829/211493bd-0160-416d-90ce-aeebdd9ad8b4)

# No 5 
Cara kerja audio Processing pada aplikasi yang saya buat adalah sebagai berikut
- Penggabungan Audio :
Pada penggabungan audio disini saya menggunakan teknik siple addition atau penjumlahan sederhana dimana saya mendefinisikan 2 audio kedalam variebel yang berbeda lalu membuat variebel dengan definisi audi_gabungan = audio1 + audio 2.

- Konversi audio : 
Pada konversi audio saya memngkonversikan dari mp3 ke wav dimana format wav itu menggunakan kompressi lossless sedangkan untuk mp3 menggunakan kompresi loosy. pada kompressi mp3 ke wav file yang dihasilkan ukurannya akan lebih besar sekitar 9 s.d 10 kali lipat. hal ini disebabkan karena berikut ini.
- Format MP3 menggunakan kompresi data lossy, yang berarti beberapa informasi frekuensi audio yang dianggap tidak terdengar oleh telinga manusia dihapus atau dikompresi secara signifikan. Ini membantu mengurangi ukuran file MP3 secara drastis dibandingkan dengan format audio yang tidak dikompresi seperti WAV.

- Adapun format WAV merupakan format audio yang tidak dikompresi, yang berarti tidak ada informasi audio yang hilang saat menyimpan file. Setiap sampel audio dalam file WAV disimpan dengan presisi penuh, yang menghasilkan kualitas audio yang lebih baik tetapi juga menghasilkan ukuran file yang lebih besar dibandingkan dengan format yang dikompresi seperti MP3.

Alur kerja :

Deskripsi alur pemrosesan penggabungan audio :

1. Pengguna menjalankan program dengan menjalankan fungsi gabung_audio(), yaitu saat tombol "Gabungkan Audio" ditekan.
2. Program akan menampilkan dialog untuk memilih file audio pertama menggunakan filedialog.askopenfilename(). Jika pengguna tidak memilih file, program akan berhenti.
3. Program akan menampilkan dialog untuk memilih file audio kedua menggunakan filedialog.askopenfilename(). Jika pengguna tidak memilih file, program akan berhenti.
4. Audio pertama akan dimuat menggunakan AudioSegment.from_file() dan disimpan dalam variabel audio.
5. Variabel combined_audio akan diinisialisasi dengan audio pertama.
6. Program akan menampilkan dialog untuk memilih lokasi dan nama file untuk menyimpan audio gabungan menggunakan filedialog.asksaveasfilename(). Jika pengguna tidak memilih lokasi file, program akan berhenti.
7. Audio gabungan akan diekspor ke file dengan format WAV menggunakan combined_audio.export().
8. Pesan berhasil akan ditampilkan menggunakan messagebox.showinfo() untuk memberi tahu pengguna bahwa penggabungan audio berhasil.

Deskripsi alur pemrosesan konversi audio :

1. Pengguna menjalankan program dengan menjalankan fungsi konversi_audio(), yaitu saat tombol "Convert Audio" ditekan.
2. Program akan menampilkan dialog untuk memilih file audio menggunakan filedialog.askopenfilename(). Jika pengguna tidak memilih file, program akan berhenti.
3. Audio akan dimuat menggunakan AudioSegment.from_file() dan disimpan dalam variabel audio1.
4. Variabel convertion_audio akan diinisialisasi dengan audio yang dimuat.
5. Program akan menampilkan dialog untuk memilih lokasi dan nama file untuk menyimpan audio hasil konversi menggunakan filedialog.asksaveasfilename(). Jika pengguna tidak memilih lokasi file, program akan berhenti.
6. Audio hasil konversi akan diekspor ke file dengan format WAV menggunakan convertion_audio.export().
7. Pesan berhasil akan ditampilkan menggunakan messagebox.showinfo() untuk memberi tahu pengguna bahwa konversi audio berhasil.

# No 6
Aspek kecerdasan buatan pada aplikasi yang saya buat adalah dimana pada aplikasi ini digunakan fungsi AudioSegment yang diambil dari modul/library pydub dengan penjelasan sebagai berikut.
1. Pembacaan Format Audio: Fungsi AudioSegment.from_file dapat membaca berbagai format file audio seperti WAV, MP3, FLAC, dan banyak lagi. Aspek kecerdasan buatan digunakan untuk menganalisis dan mengenali format file audio yang diberikan, serta untuk memastikan bahwa data audio dapat diakses dan dimanipulasi dengan benar.

2. Penggabungan dan Pemisahan Audio: AudioSegment menyediakan metode seperti + untuk menggabungkan dua file audio, serta metode  untuk memotong bagian tertentu dari file audio. Aspek kecerdasan buatan digunakan untuk memanipulasi data audio, menggabungkan sampel-sampel suara, atau memotong bagian-bagian tertentu dari file audio dengan presisi yang diperlukan.

3. Konversi Format Audio: AudioSegment mendukung konversi format audio seperti MP3 ke WAV atau sebaliknya. Aspek kecerdasan buatan dapat digunakan untuk menganalisis dan memahami struktur data dalam format audio sumber dan format tujuan, serta melakukan konversi dengan benar.

Pembuatan tugas akhir ini dibantu oleh beberapa konten dari kreator 'kelas terbuka" (youtube) saat belajar menampilkan aplikasi GUI dengan python.
