# KANTOR POLISI

## DESKRIPSI
Kantor polisi adalah lembaga layanan publik yang menjaga ketertiban, menegakkan hukum, dan melindungi masyarakat; untuk menertibkan alur kerja harian saya membuat sistem manajemen kantor polisi dengan tiga menu utama yang sesuai dengan program saya, yaitu informasi polisi yang mengelola data personel berupa NRP tiga digit, nama, pangkat, dan status aktif atau cuti lengkap dengan operasi tambah, lihat data, detail ringkasan per NRP, ubah, dan hapus; Selanjutnya yaitu jadwal patroli yang merencanakan dan memantau patroli melalui id jadwal berformat huruf J diikuti angka, tanggal pola dd MM yyyy, area, NRP petugas, serta status dijadwalkan atau telah selesai beserta fitur buat jadwal, lihat semua, ubah tanggal atau area, tandai selesai, filter berdasarkan area atau status, dan hapus; serta kasus penyelidikan yang mencatat progres perkara melalui id kasus berformat huruf K diikuti angka, judul, status baru, proses, atau ditutup, dan penyidik NRP dengan fungsi tambah, lihat baik semua maupun per status, ubah status, serta hapus sehingga seluruh informasi terkumpul di satu tempat, pencarian dan pemantauan menjadi cepat dan jelas, dan koordinasi petugas lebih lancar dengan adanya sistem manajemen kantor polisi yang dibuat.



### MASUK PROGRAM
<img width="640" height="382" alt="image" src="https://github.com/user-attachments/assets/b36180b7-d4b5-46f3-a60b-341a554f4e03" />

yang pertama jalankan program untuk mengakses sistem kantor polisi tersebut, setelah program dijalankan akan muncul tampilan atau output dengan tampilan kantor polisi dan selamat datang, lalu muncul menu utama yang ada pada sistem kantor polisi tersebut dengan 3 menu utama yang pertama informasi polisi, yang kedua jadwal patroli, yang ketiga kasus penyelidikan, dan yang keempat keluar. lalu pengguna memilih menu dengan mengetik angka dari angka 1 sampai 4.




#### -> MENGETIK ANGKA 1 (Informasi Polisi)
<img width="640" height="675" alt="image" src="https://github.com/user-attachments/assets/d440d465-193f-413d-8ff1-5b9d4267401c" />


Jika pengguna mengetik angka 1 dan masuk ke Informasi Polisi, sistem membuka kotak Fitur Informasi Polisi yang berisi pilihan untuk menambah data personel baru dengan NRP tiga digit, nama, pangkat, dan status; melihat seluruh data dalam tabel rapi; menampilkan detail ringkasan satu polisi berdasarkan NRP; mengubah data yang sudah ada; menghapus data polisi; serta kembali ke menu utama—semua dijalankan cukup dengan mengetik nomor fitur pada kolom Pilih.


#### -> FITUR INFORMASI POLISI (1. Tambah data Polisi)
<img width="651" height="431" alt="image" src="https://github.com/user-attachments/assets/8dbe92b6-f009-47ed-91fe-baa170779d6b" />


Setelah masuk kedalam menu informasi polisi sistem akan menampilkan output yaitu fitur informasi polisi, disini ketika pengguna mengetik angka 1 pada fitur informasi polisi yaitu tambah data polisi, disini pengguna akan disuruh untuk menginputkan nrp baru sebanyak 3 angka unik yang berbeda dari polisi lainnya, memasukkan nama, pangkat dan juga status apakah polisi ini aktif atau cuti.


##### -> FITUR INFORMASI POLISI (2. Lihat data)
<img width="570" height="676" alt="image" src="https://github.com/user-attachments/assets/a06d6b91-b421-4f05-859e-ef1b4a44467c" />


Setelah itu saat pengguna mengetik 2 yaitu lihat data, program akan menampilkan data polisi yang sudah ada, dan juga inputan yang sudah kita buat sebelumnya pada fitur no 1 yaitu tambah data polisi


##### -> FITUR INFORMASI POLISI (3. Detail ringkasan (by NRP))
<img width="532" height="394" alt="image" src="https://github.com/user-attachments/assets/44e87b9f-ffce-457a-af0e-c824c70e1017" />

setelah itu pengguna berada di menu Fitur Informasi Polisi dan memilih opsi 3 (Detail Ringkasan by NRP); sistem kemudian menanyakan “Masukkan NRP”, misalnya diisi 114, lalu program mencari NRP tersebut di daftar polisi pada ArrayList, dan jika ditemukan akan menampilkan kartu ringkas satu orang dengan format rapi berisi NRP, Nama, Pangkat, dan Status sebagaimana terlihat pada output “NRP: 114, Nama: Naufal Rizqi, Pangkat: Briptu, Status: Aktif”; tampilan berbingkai garis ini memudahkan pengecekan cepat tanpa harus menampilkan seluruh data, sedangkan jika NRP tidak ada maka program akan memberi pesan bahwa data tidak ditemukan dan pengguna dapat kembali memilih fitur lain di menu Informasi Polisi.



##### -> FITUR INFORMASI POLISI (4. Ubah data)
<img width="537" height="588" alt="image" src="https://github.com/user-attachments/assets/d5bf7d3d-6e90-44f1-b244-7187998b78eb" />



Selanjutnya akan masuk kedalam tampilan menu fitur informasi polisi disini saya memilih opsi 4 (Ubah Data) di menu Fitur Informasi Polisi, lalu sistem meminta NRP yang akan diedit; setelah NRP 101 dimasukkan, program menampilkan isian singkat dengan menampilkan nilai lama sebagai panduan—Nama (Andi Saputra) kemudian diganti menjadi Galuh Anin, Pangkat diisi Kompol, dan Status menjadi Aktif setelah pengguna setelah itu, perubahan akan disimpan pada data polisi dengan NRP 101 dan layar otomatis kembali ke kotak Fitur Informasi Polisi sehingga pengguna bisa langsung melanjutkan memilih fitur berikutnya.



##### -> FITUR INFORMASI POLISI (5. Hapus data)
<img width="515" height="279" alt="image" src="https://github.com/user-attachments/assets/79d16aba-706f-4912-952d-094a1a867462" />


<img width="549" height="319" alt="image" src="https://github.com/user-attachments/assets/20291e61-7ce4-431e-826c-bafdbdf26a11" />


Selanjutnya jika memilih opsi 5 (Hapus Data Polisi) pada menu Fitur Informasi Polisi, sistem akan meminta NRP yang akan dihapus—misalnya diisi 101 lalu program mencari data dengan NRP tersebut di daftar, menghapusnya jika ditemukan dan kembali ke menu fitur (atau menampilkan pemberitahuan “NRP tidak ditemukan” bila nomornya tidak ada).


##### ->FITUR INFORMASI POLISI (6. Kembali)
<img width="541" height="567" alt="image" src="https://github.com/user-attachments/assets/f7c5ebb3-c1ea-4d78-8b49-244905615c61" />



Selanjutnya akan masuk kedalam fitur informasi polisi lagi, disini pengguna menekan pilihan 6 (Kembali) di dalam Fitur Informasi Polisi sehingga submenu ditutup tanpa mengubah data apa pun, lalu program langsung memuat ulang layar utama dengan bingkai judul KANTOR POLISI dan sapaan kembali untuk SELAMAT DATANG DI SISTEM KANTOR POLISI. Setelah itu sistem menampilkan Menu Utama yang berisi empat opsi — Informasi Polisi, Jadwal Patroli, Kasus Penyelidikan, dan Keluar — dan kursor berhenti di kolom “Pilih:” menunggu input berikutnya; pada titik ini pengguna bisa melanjutkan ke menu lain dengan mengetik angka 1, 2, atau 3, atau menutup aplikasi dengan mengetik angka 4.



### MASUK KE MENU JADWAL PATROLI
<img width="531" height="563" alt="image" src="https://github.com/user-attachments/assets/9862888b-3167-4a52-85ce-870fc168a70f" />


Selanjutnya dari menu utama, pengguna mengetik angka 2 untuk masuk ke Jadwal Patroli; layar kemudian menampilkan kotak berjudul “JADWAL PATROLI” dengan enam opsi, yaitu membuat jadwal baru dengan mengisi tanggal berformat dd-MM-yyyy, area patroli, dan NRP petugas sehingga sistem otomatis memberi ID berformat J-angka dan status awal “Dijadwalkan”; melihat seluruh jadwal dalam tabel rapi agar tanggal, area, nama petugas, dan status mudah dibaca; mengubah jadwal tertentu dengan memilih ubah tanggal atau ubah area serta dapat menandai Telah Selesai bila patroli sudah dilakukan; memfilter daftar berdasarkan area atau status untuk menampilkan jadwal yang relevan saja; menghapus jadwal dengan memasukkan ID yang sesuai; dan kembali ke Menu Utama bila ingin berpindah ke fitur lain.


##### -> JADWAL PATROLI (1. Buat jadwal)
<img width="516" height="338" alt="image" src="https://github.com/user-attachments/assets/c11c4c60-dd31-4048-8598-fc771641ef1c" />

<img width="541" height="373" alt="image" src="https://github.com/user-attachments/assets/bec36d0b-4ebe-44a8-9c37-e13044649911" />


Pada layar Jadwal Patroli disini saya memilih opsi 1 (Buat Jadwal), lalu sistem membuka form BUAT JADWAL dan meminta tiga isian berurutan: tanggal dengan pola dd-MM-yyyy (contoh 29-10-2025), area patroli (contoh Perjuangan), dan NRP petugas tiga angka (contoh 110). Setelah diisi, program memeriksa apakah input yang dibuat ini khususnya NRP harus ada di daftar personel kemudian otomatis membuat ID jadwal berformat J-angka, menyimpan data ke ArrayList, dan memberi status awal “Dijadwalkan”. Jadwal yang baru tercatat ini akan muncul saat Lihat Jadwal, dapat diubah tanggal atau areanya, bisa ditandai “Telah Selesai”, difilter berdasarkan area atau status, atau dihapus melalui menu lain; jika NRP tidak ditemukan atau format salah, sistem menolak penyimpanan dan meminta pengguna memperbaiki input.



#### -> JADWAL PATROLI (2. Lihat jadwal)
<img width="812" height="625" alt="image" src="https://github.com/user-attachments/assets/8baae451-6996-492c-b826-bbdc67188e17" />



disini program akan masuk kembali ke fitur menu pada jadwal patroli disini saya menginput dan mengetikan angka 2 sehingga masuk ke Lihat Jadwal pada menu Jadwal Patroli; sistem kemudian mencetak tabel “DAFTAR JADWAL” dengan kolom yang sejajar id berformat J-angka, Tanggal dalam pola dd-MM-yyyy, Area patroli, Nama Polisi yang otomatis diambil dari NRP dan ditampilkan bersama pangkat di dalam tanda kurung, serta Status yang menunjukkan “Dijadwalkan” atau “Telah Selesai”. Seluruh baris diambil dari ArrayList jadwal yang sudah di-seed maupun yang baru dibuat. Dari tampilan ini pengguna bisa menilai rencana patroli secara cepat, lalu kembali ke menu untuk mengubah jadwal, menandai selesai, memfilter berdasarkan area atau status, atau menghapus jadwal tertentu.



#### -> JADWAL PATROLI (3. Ubah jadwal(Tanggal/Area) & Tandai Telah Selesai)
<img width="570" height="593" alt="image" src="https://github.com/user-attachments/assets/64913aec-7436-41e0-86b1-aff42bd0ded4" />


Selanjutnya kita akan kembali menu Fitur Jadwal Patroli: pengguna memilih opsi 3 (Ubah Jadwal – Tanggal/Area & Tandai Telah Selesai), lalu mengisi ID jadwal yang akan diedit, yaitu j-10; sistem menampilkan sub-pilihan 1) Ubah Tanggal, 2) Ubah Area, 3) Tandai Telah Selesai, 4) Batal, pengguna memilih 1 dan mengetik tanggal baru 18-10-2025, setelah perubahan disimpan program otomatis menampilkan lagi kotak JADWAL PATROLI sehingga pengguna bisa langsung melanjutkan dengan melihat daftar, memfilter, menandai selesai, atau mengubah jadwal lain.


#### -> JADWAL PATROLI (4. Filter Area/Status)
<img width="808" height="501" alt="image" src="https://github.com/user-attachments/assets/66b2ea47-e482-436b-8acc-0e5a42df7563" />

<img width="792" height="482" alt="image" src="https://github.com/user-attachments/assets/bef88f64-290d-49a6-90ac-c3192e5ec3fb" />


Selanjutnya program kembali berada di Jadwal Patroli dan memilih opsi 4 (Filter Area/Status); sistem menampilkan sub-menu filter dengan tiga pilihan, lalu pengguna memilih 1 (Area) dan mengetik area “perjuangan”, sehingga program menyaring data dan menampilkan tabel DAFTAR JADWAL yang hanya berisi patroli di area tersebut—terlihat satu baris hasil dengan ID J-13, tanggal 29-10-2025, area Perjuangan, petugas Joko Susilo (Kompol), dan status Dijadwalkan; jika tidak ada data yang cocok maka tabel akan kosong dan pengguna bisa kembali ke menu untuk mencoba filter lain (Status atau Area + Status) atau membuka Lihat Jadwal untuk melihat seluruh data tanpa penyaringan.


#### -> JADWAL PATROLI (5. Hapus jadwal)
<img width="522" height="594" alt="image" src="https://github.com/user-attachments/assets/f743ff08-88ac-4ff1-9284-6256aa23b696" />

Program akan masuk atau kembali ke Jadwal Patroli dan memilih opsi 5 (Hapus Jadwal). Pertama, ia mengetik ID jadwal: j-13; karena ID tersebut valid dan ada di data, sistem menghapus jadwal itu lalu kembali ke menu Jadwal Patroli tanpa mengubah fitur lain. Setelah itu pengguna mencoba lagi, memilih 5 lalu mengisi ID jadwal: 12le; ID ini tidak sesuai format (seharusnya J-angka, misalnya J-13, huruf J boleh besar/kecil) dan tidak ditemukan di daftar, sehingga program menolak penghapusan dan menampilkan pesan “ID tidak ditemukan.” jadi data masih tetap aman dan tidak ada yang berubah.



#### -> JADWAL PATROLI (6. Kembali)
<img width="525" height="562" alt="image" src="https://github.com/user-attachments/assets/2cb25f2d-e841-421c-b12b-daea3c362341" />


Selanjutnya pilih no 6 (Kembali) pada menu Jadwal Patroli, sehingga submenu ditutup tanpa mengubah data apa pun dan program langsung menampilkan lagi banner KANTOR POLISI serta SELAMAT DATANG DI SISTEM KANTOR POLISI, lalu memunculkan Menu Utama dengan empat opsi—Informasi Polisi, Jadwal Patroli, Kasus Penyelidikan, dan Keluar—serta kursor berhenti di kolom “Pilih:” untuk menunggu input berikutnya (1–4).



#### -> MASUK KE MENU KASUS PENYELIDIKAN
<img width="538" height="540" alt="image" src="https://github.com/user-attachments/assets/7beee38a-e42c-44cf-8f5a-3e747ed8ac21" />


Dari Menu Utama disini ingin masuk kedalam menu kasus penyelidikan dan mengetik angka 3 untuk membuka Kasus Penyelidikan, lalu layar menampilkan kotak berisi pilihan pengelolaan kasus. Di sini pengguna dapat menambahkan kasus baru dengan mengisi judul dan NRP penyidik sehingga sistem otomatis membuat ID K-angka dan memberi status awal Baru; melihat daftar kasus dengan opsi filter sehingga dapat ditampilkan Semua, hanya yang Baru, yang sedang Proses, atau yang sudah Ditutup dalam tabel yang rapi; mengubah status suatu kasus dengan memasukkan ID lalu memilih apakah statusnya menjadi Baru, Proses, atau Ditutup agar perkembangan perkara tercatat; menghapus kasus tertentu dengan memasukkan ID bila datanya tidak lagi diperlukan; atau kembali ke Menu Utama. Seluruh perintah dijalankan dengan mengetik angka 1 sampai 5 pada kolom “Pilih:” sesuai kebutuhan.


#### -> KASUS PENYELIDIKAN (1. Tambah kasus)
<img width="536" height="528" alt="image" src="https://github.com/user-attachments/assets/a76dfc05-42b0-4b18-8a9f-386351833478" />

Selanjutnya jika ingin dan mau menambahkan kasus yang ada tinggal memilih atau mengetik 1 (Tambah Kasus), sehingga program membuka formulir singkat berisi Judul dan Penyidik NRP tiga angka; setelah diisi “Pembunuhan” dan 105, sistem memeriksa format serta memastikan NRP tersebut ada pada data personel, lalu otomatis membuat entri kasus baru dengan ID berformat K-angka dan status awal “Baru”, menyimpannya ke ArrayList, dan mengembalikan layar ke menu Kasus Penyelidikan agar pengguna bisa langsung melanjutkan misalnya melihat daftar kasus, memfilter, mengubah status menjadi Proses atau Ditutup, atau menghapus bila diperlukan.


#### -> KASUS PENYELIDIKAN (2. Lihat Kasus (Filter Status))
<img width="677" height="614" alt="image" src="https://github.com/user-attachments/assets/2822a518-2d20-4be1-9937-ef05777ddaf8" />


<img width="657" height="501" alt="image" src="https://github.com/user-attachments/assets/22b53c19-4e77-4942-b548-fbb040c5ba22" />


Program akan masuk kembali ke menu Kasus Penyelidikan lalu disini jika ingin memilih 2 (Lihat Kasus); sistem akan menampilkan subpilihan Semua, Baru, Proses, Ditutup, dan ketika menekan 1 (Semua) program mencetak blok [SEMUA] berupa tabel rapi dengan kolom ID, Judul, Status, dan Penyidik. Setiap baris memperlihatkan kasus dari seluruh status, ID berformat K-angka, dan NRP penyidik tiga digit; daftar ini memuat data awal sekaligus entri terbaru, misalnya kasus “Pembunuhan” dengan ID K-10, status Baru, dan penyidik 105. Jika pada langkah ini pengguna memilih Baru, Proses, atau Ditutup, maka tabel yang muncul hanya menampilkan kasus sesuai kategori tersebut.



#### -> KASUS PENYELIDIKAN (3. Ubah Status (Baru/Proses/Ditutup))
<img width="580" height="726" alt="image" src="https://github.com/user-attachments/assets/dcf41b35-9d07-47be-ad42-575a9a8c5a34" />




Selanjutnya program akan kembali berada di menu Kasus Penyelidikan disini saya memilih 3 (Ubah Status), lalu mengetik ID kasus: k-4. Sistem menampilkan pilihan status 1) Baru 2) Proses 3) Ditutup, pengguna memilih 3 sehingga status kasus K-4 (Perjudian Ilegal) yang awalnya status ini adalah Proses diperbarui menjadi Ditutup di data. Setelah perubahan disimpan, program kembali ke menu Kasus Penyelidikan; pengguna kemudian memilih 2 (Lihat Kasus) dan menekan 1 (Semua) untuk memastikan hasilnya. Tabel [SEMUA] yang muncul menampilkan seluruh kasus dengan kolom ID, Judul, Status, Penyidik, dan terlihat bahwa K-4 sekarang berstatus Ditutup, menandakan proses ubah status berhasil diterapkan. Jika pada langkah awal ID tidak ditemukan atau formatnya salah, sistem akan menolak pembaruan dan memberi pesan sehingga data tetap aman.


#### KASUS PENYELIDIKAN (4. Hapus kasus)
<img width="469" height="437" alt="image" src="https://github.com/user-attachments/assets/266930d1-4d75-422b-a043-432bc89d4d01" />


Program akan kembali ke menu Kasus Penyelidikan jetika memilih 4 (Hapus Kasus). Pertama disini saya mengetik ID kasus: k-10; karena ID tersebut valid dan ada di data, program akan menghapus tersebut dari lalu kembali ke menu Kasus Penyelidikan. Berikutnya saya ingin mengulangi pilihan 4 tetapi memasukkan ID kasus: 12lw; ID ini tidak sesuai format (seharusnya K-angka, misalnya K-10) sekaligus tidak ada di daftar, sehingga sistem menolak operasi dan menampilkan pesan “ID tidak ditemukan.”. Alur ini menunjukkan bahwa penghapusan mewajibkan ID yang benar dan terdaftar, sehingga data lain tetap aman bila input salah


#### -> KASUS PENYELIDIKAN (5. Kembali)
<img width="483" height="446" alt="image" src="https://github.com/user-attachments/assets/52a9290d-2c28-49d6-9a26-1929480c8e7a" />


Selanjutnya saya mengetik no 5 (Kembali) pada menu Kasus Penyelidikan, sehingga submenu ditutup tanpa mengubah data apa pun dan program menampilkan lagi banner KANTOR POLISI serta SELAMAT DATANG DI SISTEM KANTOR POLISI, lalu muncul Menu Utama dengan empat opsi—1 Informasi Polisi, 2 Jadwal Patroli, 3 Kasus Penyelidikan, 4 Keluar.


## KELUAR DARI PROGRAM
<img width="531" height="364" alt="image" src="https://github.com/user-attachments/assets/b93d27a3-d030-4691-9dee-c3a8feee9718" />

Selanjutnya saya ingin keluar dari program dan mengetik angka 4 (Keluar) di Menu Utama, program menampilkan pesan “Selesai.” dan eksekusi berakhir. Terminal/IDE kemudian mencetak ringkasan proses (BUILD SUCCESS, durasi, dan waktu selesai) sebagai tanda bahwa aplikasi Sistem Kantor Polisi telah ditutup dengan normal tanpa error.
