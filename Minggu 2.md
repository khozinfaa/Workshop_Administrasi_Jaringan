## Tugas Minggu KE (2)

## Nama : Muh Khozinatul Asror
## Kelas : 2 D4-IT-A
## NRP : 3121600026

# TUGAS IDENTIFIKASI
**Identifikasi kernel**

Kernel adalah inti dari sistem operasi Linux/Unix yang mengelola sumber daya komputer dan berfungsi sebagai perantara antara aplikasi dan perangkat keras.
"Perintah 'uname -a' menampilkan semua informasi sistem seperti host, versi kernel, arsitektur, dan tanggal kompilasi kernel. 'Uname -r' hanya menampilkan nomor versi kernel yang sedang digunakan."

[![Screenshot-2023-03-04-214703.png](https://i.postimg.cc/q7TGz7wH/Screenshot-2023-03-04-214703.png)](https://postimg.cc/FYTS6NwT)

- 4 adalah nomor utama kernel, yang menunjukkan bahwa ini adalah kernel seri 4.
- 15 adalah nomor minor kernel, yang menunjukkan bahwa ini adalah kernel seri 15 dari seri 4.
- 0 adalah nomor revisi kernel, yang menunjukkan bahwa ini adalah revisi pertama dari kernel seri 15.
- 204 adalah nomor pembangunan kernel, yang menunjukkan bahwa ini adalah build ke-204 dari revisi pertama dari kernel seri 0.


**Identifikasi directory structure**

proses untuk memahami struktur direktori atau folder dalam sistem operasi dan memahami struktur ini sangat penting bagi pengguna Linux karena dapat membantu mereka untuk mengelola file dan direktori dengan lebih efektif.
struktur direktori Ubuntu Linux terdiri dari beberapa direktori utama yang masing-masing memiliki fungsi dan tujuan tertentu. Beberapa direktori utama yang penting di antaranya adalah:

[![Screenshot-2023-03-04-220117.png](https://i.postimg.cc/tJ34XP38/Screenshot-2023-03-04-220117.png)](https://postimg.cc/T5P60KHc)

    /: Direktori root atau induk, merupakan direktori utama di mana semua direktori dan file lainnya berada.
    /bin: Direktori binari, berisi file biner yang terkait dengan sistem operasi dan program dasar yang diperlukan untuk menjalankan sistem.
    /etc: Direktori konfigurasi, berisi file konfigurasi sistem dan program.
    /home: Direktori home, berisi folder pengguna, termasuk folder dokumen, musik, video, dan lain-lain.
    /lib: Direktori library, berisi file library yang dibutuhkan oleh program.
    /opt: Direktori optional, berisi program yang tidak berasal dari paket resmi Ubuntu.
    /tmp: Direktori temporary, berisi file sementara yang dihasilkan oleh sistem dan program.
    /usr: Direktori user, berisi file dan direktori yang digunakan oleh pengguna.
    /sys: Direktori berkas sistem (system)
    /var: Direktori variable, berisi file yang berubah-ubah, seperti file log, basis data, dan cache.

**identifikasi perbedaan sudo dan su**

Kedua perintah "sudo" dan "su" digunakan untuk memperoleh hak akses superuser di sistem Linux dan terdapat 2 perbedaan penting antara keduanya.

"su" digunakan untuk mengubah identitas pengguna menjadi akun superuser atau akun lain dengan memasukkan kata sandi superuser, sedangkan "sudo" digunakan untuk menjalankan perintah sebagai akun superuser dengan memasukkan kata sandi pengguna sendiri. Penggunaan "sudo" lebih aman karena tidak memerlukan masuk ke akun superuser secara langsung dan membatasi potensi kerusakan atau kesalahan. "sudo su" dapat digunakan untuk masuk ke folder saat ini sebagai superuser.

[![Screenshot-2023-03-04-221029.png](https://i.postimg.cc/TwhfmT2C/Screenshot-2023-03-04-221029.png)](https://postimg.cc/62skxJvv)

**identifikasi jenis repository**

repository Linux adalah kumpulan paket perangkat lunak yang dirancang untuk bekerja dengan distribusi Linux tertentu. Repositori ini biasanya dikelola oleh pengembang distribusi dan berisi paket perangkat lunak yang telah diuji dan diverifikasi untuk bekerja dengan versi Linux tersebut.

Berikut jenis repository yang berada di linux :
- deb cdrom adalah repository dari CD/DVD instalasi Ubuntu.
- deb http://id.archive.ubuntu.com/ubuntu/ kinetic main restricted adalah repository utama (main) Ubuntu, yang berisi paket-paket utama untuk sistem operasi Ubuntu.
- deb http://id.archive.ubuntu.com/ubuntu/ kinetic-updates main restricted adalah repository Ubuntu untuk pembaruan (updates) dari paket-paket di repository utama.
- deb http://id.archive.ubuntu.com/ubuntu/ kinetic universe adalah repository Ubuntu untuk paket-paket yang tidak disupport secara resmi oleh Ubuntu, namun tetap terbuka untuk diakses oleh pengguna.
- deb http://security.ubuntu.com/ubuntu kinetic-security multiverse adalah repository Ubuntu untuk pembaruan keamanan (security) dari paket-paket di repository multiverse.
- deb http://security.ubuntu.com/ubuntu kinetic-security universe Ini adalah repository Ubuntu untuk pembaruan keamanan (security) dari paket-paket di repository universe.
- deb http://security.ubuntu.com/ubuntu kinetic-security main restricted Ini adalah repository Ubuntu untuk pembaruan keamanan (security) dari paket-paket di repository utama.


[![Screenshot-2023-03-05-004450.png](https://i.postimg.cc/SR0zZMbj/Screenshot-2023-03-05-004450.png)](https://postimg.cc/1nHtX4tZ)

**identifikasi perintah apt**

[![Screenshot-2023-03-05-010237.png](https://i.postimg.cc/HWXCFyCH/Screenshot-2023-03-05-010237.png)](https://postimg.cc/3W86vWRb)

- apt update : Memperbarui daftar paket dan metadata yang tersedia di repository.
- apt upgrade : Menginstall paket-paket baru yang tersedia dan mengupgrade paket yang sudah terinstall.
- apt install : Menginstall paket baru.
- apt remove : Menghapus paket yang sudah terinstall.
- apt autoremove : Menghapus paket-paket yang tidak lagi dibutuhkan oleh sistem.
- apt search : Mencari paket yang tersedia di repository.
- apt show : Menampilkan informasi detail tentang paket yang tersedia di repository.
- apt list : Menampilkan daftar paket yang sudah terinstall.
- apt full-upgrade : Menginstall paket-paket baru dan mengupgrade paket-paket yang sudah terinstall dengan menyelesaikan semua ketergantungan (dependencies) yang dibutuhkan.
- list - menampilkan daftar paket berdasarkan nama paket
- search - mencari dalam deskripsi paket
- show - menampilkan detail paket
- install - menginstall paket
- reinstall - menginstall ulang paket
- remove - menghapus paket
- autoremove - menghapus otomatis semua paket yang tidak terpakai
- update - memperbarui daftar paket yang tersedia
- upgrade - mengupgrade sistem dengan menginstal/mengupgrade paket-paket
- full-upgrade - mengupgrade sistem dengan menghapus/menginstal/mengupgrade paket-paket
- edit-sources - mengedit file informasi sumber
- satisfy - memenuhi string dependensi