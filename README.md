# Dewiwulan15.github.io
pertama kita akan membuat Dockerfile terlebih dahulu, pertama buat direktori yang akan berisi Dockerfile dan semua file yang diperlukan. tulis konten yang ada pada modul untuk membuat File. pada baris pertama kita akan mendefinisikan image dasar.
intruksi RUN pada baris akan memperbarui indeks apt, menginstal paket “redis-server” dan membersihkan cache apt. Perintah yang digunakan dalam instruksi, sama dengan perintah yang Anda gunakan untuk install redis di server Ubuntu.
Instruksi EXPOSE mendefinisikan port tempat server redis akan listens.
instruksi CMD untuk mengatur perintah default yang akan dieksekusi ketika container berjalan.
Buat file index.html di dalam direktori files. Isikan kode untuk menampilkan nama atau nim ke dalam index.html
Buat file default.conf dan nginx.conf yang ada dimodul
setelah itu membuat repository baru, kemudian membuat nama repository dengan username.github.io, kemudian klik creat repository.
lalu mengcopy url repository dan menggunakan git bash untuk mengclone url tadi, kemudian pindahkan web statis yang kita buat kedalam satu file yang telah kita buat atau clone dari git bash. lalu melanjutkan dengan beberapa perintah yang telah ada di modul sampai di push -u origin master, disini ada proses upload pada git bash dan kemudian kita akan mengecek kembali repository yang telah kita buat sebelumnya dan mengakses web statis yang telah kita buat sebelumnya. 
kemudian buka docker dan buat repository baru, lalu sambungkan akses dengan github kita kemudian create. setelah itu Setelah kita berada pada tab Build Details maka terdapat status build image dari github. Disini jika status berubah menjadi “Success” maka build image dari github sudah selesai. 
Untuk test apakah image bisa dijalankan, kita menggunakan enviroment yang lainnya menggunakan “katacoda.com” dan jalankan perintah “docker run -d -p 8000:80 --name nim-anda nama-image”. Klik tanda “+” pada terminal kemudian pilih “Select port to view on Host 1”  Klik tanda “+” pada terminal kemudian pilih “Select port to view on Host 1” Jika muncul nama dan nim anda masing-masing maka container berhasil dijalankan.
