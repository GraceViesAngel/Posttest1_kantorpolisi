# KANTOR POLISI

## DESKRIPSI
Kantor polisi adalah lembaga layanan publik yang menjaga ketertiban, menegakkan hukum, dan melindungi masyarakat; untuk menertibkan alur kerja harian saya membuat sistem manajemen kantor polisi dengan tiga menu utama yang sesuai dengan program saya, yaitu informasi polisi yang mengelola data personel berupa NRP tiga digit, nama, pangkat, dan status aktif atau cuti lengkap dengan operasi tambah, lihat data, detail ringkasan per NRP, ubah, dan hapus; Selanjutnya yaitu jadwal patroli yang merencanakan dan memantau patroli melalui id jadwal berformat huruf J diikuti angka, tanggal pola dd MM yyyy, area, NRP petugas, serta status dijadwalkan atau telah selesai beserta fitur buat jadwal, lihat semua, ubah tanggal atau area, tandai selesai, filter berdasarkan area atau status, dan hapus; serta kasus penyelidikan yang mencatat progres perkara melalui id kasus berformat huruf K diikuti angka, judul, status baru, proses, atau ditutup, dan penyidik NRP dengan fungsi tambah, lihat baik semua maupun per status, ubah status, serta hapus sehingga seluruh informasi terkumpul di satu tempat, pencarian dan pemantauan menjadi cepat dan jelas, dan koordinasi petugas lebih lancar dengan adanya sistem manajemen kantor polisi yang dibuat.



### MASUK PROGRAM
<img width="640" height="382" alt="image" src="https://github.com/user-attachments/assets/b36180b7-d4b5-46f3-a60b-341a554f4e03" />

yang pertama jalankan program untuk mengakses sistem kantor polisi tersebut, setelah program dijalankan akan muncul tampilan atau output dengan tampilan kantor polisi dan selamat datang, lalu muncul menu utama yang ada pada sistem kantor polisi tersebut dengan 3 menu utama yang pertama informasi polisi, yang kedua jadwal patroli, yang ketiga kasus penyelidikan, dan yang keempat keluar. lalu pengguna memilih menu dengan mengetik angka dari angka 1 sampai 4.




#### -> MENGETIK ANGKA 1 (Informasi Polisi)
<img width="640" height="675" alt="image" src="https://github.com/user-attachments/assets/d440d465-193f-413d-8ff1-5b9d4267401c" />


Jika pengguna mengetik angka 1 dan masuk ke Informasi Polisi, sistem membuka kotak Fitur Informasi Polisi yang berisi pilihan untuk menambah data personel baru dengan NRP tiga digit, nama, pangkat, dan status; melihat seluruh data dalam tabel rapi; menampilkan detail ringkasan satu polisi berdasarkan NRP; mengubah data yang sudah ada; menghapus data polisi; serta kembali ke menu utama—semua dijalankan cukup dengan mengetik nomor fitur pada kolom Pilih.


##### FITUR INFORMASI POLISI (1. Tambah data Polisi)
<img width="651" height="431" alt="image" src="https://github.com/user-attachments/assets/8dbe92b6-f009-47ed-91fe-baa170779d6b" />


Setelah masuk kedalam menu informasi polisi sistem akan menampilkan output yaitu fitur informasi polisi, disini ketika pengguna mengetik angka 1 pada fitur informasi polisi yaitu tambah data polisi, disini pengguna akan disuruh untuk menginputkan nrp baru sebanyak 3 angka unik yang berbeda dari polisi lainnya, memasukkan nama, pangkat dan juga status apakah polisi ini aktif atau cuti.


##### FITUR INFORMASI POLISI (2. Lihat data)
<img width="570" height="676" alt="image" src="https://github.com/user-attachments/assets/a06d6b91-b421-4f05-859e-ef1b4a44467c" />


Setelah itu saat pengguna mengetik 2 yaitu lihat data, program akan menampilkan data polisi yang sudah ada, dan juga inputan yang sudah kita buat sebelumnya pada fitur no 1 yaitu tambah data polisi


##### FITUR INFORMASI POLISI (3. Detail ringkasan (by NRP))
<img width="532" height="394" alt="image" src="https://github.com/user-attachments/assets/44e87b9f-ffce-457a-af0e-c824c70e1017" />

setelah itu pengguna berada di menu Fitur Informasi Polisi dan memilih opsi 3 (Detail Ringkasan by NRP); sistem kemudian menanyakan “Masukkan NRP”, misalnya diisi 114, lalu program mencari NRP tersebut di daftar polisi pada ArrayList, dan jika ditemukan akan menampilkan kartu ringkas satu orang dengan format rapi berisi NRP, Nama, Pangkat, dan Status sebagaimana terlihat pada output “NRP: 114, Nama: Naufal Rizqi, Pangkat: Briptu, Status: Aktif”; tampilan berbingkai garis ini memudahkan pengecekan cepat tanpa harus menampilkan seluruh data, sedangkan jika NRP tidak ada maka program akan memberi pesan bahwa data tidak ditemukan dan pengguna dapat kembali memilih fitur lain di menu Informasi Polisi.



##### FITUR INFORMASI POLISI (4. Ubah data)
<img width="537" height="588" alt="image" src="https://github.com/user-attachments/assets/d5bf7d3d-6e90-44f1-b244-7187998b78eb" />



Selanjutnya akan masuk kedalam tampilan menu fitur informasi polisi disini saya memilih opsi 4 (Ubah Data) di menu Fitur Informasi Polisi, lalu sistem meminta NRP yang akan diedit; setelah NRP 101 dimasukkan, program menampilkan isian singkat dengan menampilkan nilai lama sebagai panduan—Nama (Andi Saputra) kemudian diganti menjadi Galuh Anin, Pangkat diisi Kompol, dan Status menjadi Aktif setelah pengguna setelah itu, perubahan akan disimpan pada data polisi dengan NRP 101 dan layar otomatis kembali ke kotak Fitur Informasi Polisi sehingga pengguna bisa langsung melanjutkan memilih fitur berikutnya.



##### FITUR INFORMASI POLISI (5. Hapus data)
<img width="515" height="279" alt="image" src="https://github.com/user-attachments/assets/79d16aba-706f-4912-952d-094a1a867462" />


<img width="549" height="319" alt="image" src="https://github.com/user-attachments/assets/20291e61-7ce4-431e-826c-bafdbdf26a11" />


Selanjutnya jika memilih opsi 5 (Hapus Data Polisi) pada menu Fitur Informasi Polisi, sistem akan meminta NRP yang akan dihapus—misalnya diisi 101 lalu program mencari data dengan NRP tersebut di daftar, menghapusnya jika ditemukan dan kembali ke menu fitur (atau menampilkan pemberitahuan “NRP tidak ditemukan” bila nomornya tidak ada).


##### FITUR INFORMASI POLISI (6. Kembali)
<img width="541" height="567" alt="image" src="https://github.com/user-attachments/assets/f7c5ebb3-c1ea-4d78-8b49-244905615c61" />



Selanjutnya akan masuk kedalam fitur informasi polisi lagi, disini pengguna menekan pilihan 6 (Kembali) di dalam Fitur Informasi Polisi sehingga submenu ditutup tanpa mengubah data apa pun, lalu program langsung memuat ulang layar utama dengan bingkai judul KANTOR POLISI dan sapaan kembali untuk SELAMAT DATANG DI SISTEM KANTOR POLISI. Setelah itu sistem menampilkan Menu Utama yang berisi empat opsi — Informasi Polisi, Jadwal Patroli, Kasus Penyelidikan, dan Keluar — dan kursor berhenti di kolom “Pilih:” menunggu input berikutnya; pada titik ini pengguna bisa melanjutkan ke menu lain dengan mengetik angka 1, 2, atau 3, atau menutup aplikasi dengan mengetik angka 4.



### MASUK KE MENU JADWAL PATROLI
<img width="531" height="563" alt="image" src="https://github.com/user-attachments/assets/9862888b-3167-4a52-85ce-870fc168a70f" />


Selanjutnya dari menu utama, pengguna mengetik angka 2 untuk masuk ke Jadwal Patroli; layar kemudian menampilkan kotak berjudul “JADWAL PATROLI” dengan enam opsi, yaitu membuat jadwal baru dengan mengisi tanggal berformat dd-MM-yyyy, area patroli, dan NRP petugas sehingga sistem otomatis memberi ID berformat J-angka dan status awal “Dijadwalkan”; melihat seluruh jadwal dalam tabel rapi agar tanggal, area, nama petugas, dan status mudah dibaca; mengubah jadwal tertentu dengan memilih ubah tanggal atau ubah area serta dapat menandai Telah Selesai bila patroli sudah dilakukan; memfilter daftar berdasarkan area atau status untuk menampilkan jadwal yang relevan saja; menghapus jadwal dengan memasukkan ID yang sesuai; dan kembali ke Menu Utama bila ingin berpindah ke fitur lain.


##### JADWAL PATROLI (1. Buat jadwal)
<img width="516" height="338" alt="image" src="https://github.com/user-attachments/assets/c11c4c60-dd31-4048-8598-fc771641ef1c" />

<img width="541" height="373" alt="image" src="https://github.com/user-attachments/assets/bec36d0b-4ebe-44a8-9c37-e13044649911" />


Pada layar Jadwal Patroli disini saya memilih opsi 1 (Buat Jadwal), lalu sistem membuka form BUAT JADWAL dan meminta tiga isian berurutan: tanggal dengan pola dd-MM-yyyy (contoh 29-10-2025), area patroli (contoh Perjuangan), dan NRP petugas tiga angka (contoh 110). Setelah diisi, program memeriksa apakah input yang dibuat ini khususnya NRP harus ada di daftar personel kemudian otomatis membuat ID jadwal berformat J-angka, menyimpan data ke ArrayList, dan memberi status awal “Dijadwalkan”. Jadwal yang baru tercatat ini akan muncul saat Lihat Jadwal, dapat diubah tanggal atau areanya, bisa ditandai “Telah Selesai”, difilter berdasarkan area atau status, atau dihapus melalui menu lain; jika NRP tidak ditemukan atau format salah, sistem menolak penyimpanan dan meminta pengguna memperbaiki input.








