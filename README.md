Program Data Diri (Java)
📖 Deskripsi

Program ini merupakan aplikasi sederhana berbasis Java Console yang digunakan untuk meminta input data diri pengguna, seperti nama, jenis kelamin, dan tahun lahir, kemudian menampilkan informasi lengkap beserta umur yang dihitung secara otomatis berdasarkan tahun saat ini.

⚙️ Fitur Program

Input nama pengguna.

Input jenis kelamin (laki-laki atau perempuan).

Input tahun lahir.

Perhitungan umur otomatis menggunakan kelas LocalDate.

Menampilkan hasil berupa nama, umur, dan jenis kelamin lengkap.

🧠 Konsep yang Digunakan

Input/output menggunakan Scanner.

Manipulasi tanggal menggunakan LocalDate untuk mendapatkan tahun saat ini.

Struktur kendali switch untuk mengubah kode gender menjadi deskripsi penuh.

Operasi aritmatika sederhana untuk menghitung umur.

Konversi dan validasi string agar input lebih fleksibel.

💻 Cara Menjalankan Program

Pastikan kamu sudah menginstal Java minimal versi 8.

Simpan kode program dengan nama file codelab.java.

Buka terminal atau command prompt, lalu masuk ke direktori tempat file disimpan.

Jalankan perintah berikut:

javac codelab.java
java codelab


Ikuti petunjuk yang muncul di layar untuk memasukkan data.

🧾 Contoh Output
masukan nama anda : Salva
masukan gender :(l/p) l
masukan tahun lahir anda : 2003
DATA DIRI
nama anda adalah : Salva
umur   anda adalah : 22
gender anda adalah : laki laki

🧩 Catatan

Jika input jenis kelamin tidak sesuai (l atau p), maka program akan menampilkan "tidak diketahui".

Umur dihitung berdasarkan tahun saat ini (menggunakan LocalDate.now()).
