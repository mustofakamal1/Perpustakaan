# Perpustakaan

Kelas Pemrograman Lanjut - 02:

  Mustofa Kamal / 1706043020
  
  Muhammad Farhan / 1706042876
  
  
# INSTALLATION

  # A. CLI
    1. Download source code di folder CLI.
    2. Pastikan Anda sudah menginstal IDE C/C++ di komputer Anda (contoh ini menggunakan Dev-C++).
    3. Buka Dev-C++.
    4. Pilih menu File -> Open.
    5. Arahkan ke lokasi Anda menyimpan source code (Perpustakaan CLI.c) yang telah di download. Pilih File. Tekan Open.
    6. Jalankan source code dengan menekan tombol F11.
  
    Dev-C++ : https://sourceforge.net/projects/orwelldevcpp/
  
  # B. GUI
    1. Download semua file di folder GUI.
    2. Pastikan Anda telah menginstal Raylib (https://www.raylib.com/).
    3. Buka Notepad++ for Raylib (ada setelah menginstal raylib) di desktop atau start menu.
    4. Pilih menu File -> Open.
    5. Arahkan ke lokasi Anda menyimpan source code (Perpustakaan.c) yang telah di download. Pilih File. Tekan Open.
    6. Jalankan source code dengan menekan tombol F6.
    7. Saat muncul window baru, pastikan Anda memilih raylib_compile_execute (lihat di bagian kiri bawah). Tekan Ok.

# DESCRIPTION
  
  Program ini merupakan simulasi pendataan buku perpustakaan. Program ini memiliki fungsi untuk mendata buku baru, menghapus, mengurutkan berdasarkan abjad, dan menyimpannya ke file. (Versi CLII hanya Print ke File , sedangkan GUI data yang disimpan akan dibaca kembali).
   
  # A. CLI
    1. Program ini memiliki 6 menu utama yaitu : Insert, View, Sort, Delete, Print to File, dan Exit.
    2. Untuk memilih menu, masukkan angka menu kemudian tekan Enter.
    3. Menu Insert akan menampilkan input data mulai dari Title, Author, ID, dan Tahun. Setiap input tekan Enter untuk melanjutkan.
    4. Menu Insert hanya dapat mengisi satu buku setiap pengisian. Sehingga jika ada lebh dari 1 buku, maka pilih menu insert kembali.
    5. Menu View akan menampilkan data buku yang telah disimpan.
    6. Menu Sort akan mengurutkan buku sesuai abjad (ascending).
    7. Menu Delete akan menghapus buku sesuai dengan judul buku yang ingin dihapus.
    8. Menu Delete akan meminta input buku yang ingin dihapus, kemudian tekan Enter.
    9. Menu Print to file akan mencetak buku ke dalam file pepus.txt, di lokasi yang sama dengan file source code.
    10. Menu Exit akan menghentikan program.
    
  # B. GUI
    1. Program ini memiliki tampilan awal cover selama 2 detik.
    1. Kemudian Program ini akan menampilkan 6 menu utama yaitu : Simpan Buku, Hapus Buku, Urut Buku, Tampilkan Buku.
    2. Untuk memilih menu, masukkan angka menu kemudian tekan Enter. Ketika selesai di salah satu menu, maka tekan F5 untuk kembali ke menu utama.
    3. Menu Simpan Buku akan menampilkan input data mulai dari Judul Buku, Penulis, dan Tahun. Setiap input tekan Enter untuk melanjutkan.
    4. Menu Simpan Buku dapat melakukan pengisian buku sesuai jumlah yang diinginkan.
    5. Menu Hapus Buku menghapus buku sesuai dengan judul buku yang ingin dihapus.
    6. Menu Hapus Buku akan meminta input buku yang ingin dihapus, kemudian tekan Enter.
    7. Menu Urut Buku akan mengurutkan buku sesuai abjad (ascending).
    8. Menu Tampilkan akan menampilkan buku yang telah ditambahkan dan yang sebelumnya tersimpan di file Database.txt d folder resources. Tekan Enter untuk mengupdate data buku ke file, agar tersimpan dan dapat digunakan kembali.
    9. Untuk keluar/menghentikan program tekan ESC.


# Educational Purposes Only
