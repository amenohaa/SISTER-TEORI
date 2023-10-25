# SISTER-TEORI

24/10/2023


Program Static Huffman Compression adalah program yang digunakan untuk mengompresi data menggunakan metode kompresi Huffman yang statis. Metode kompresi Huffman adalah teknik yang digunakan untuk mengurangi ukuran data dengan menggantikan simbol-simbol dalam data dengan kode biner yang lebih pendek untuk simbol-simbol yang muncul lebih sering, dan kode yang lebih panjang untuk simbol-simbol yang muncul lebih jarang.

Berikut adalah langkah-langkah umum dalam program Static Huffman Compression:

Pengumpulan Statistik:

Program pertama-tama akan melakukan pemindaian (scan) data yang akan diompresi untuk mengumpulkan statistik tentang seberapa sering masing-masing simbol muncul dalam data. Statistik ini akan digunakan untuk membangun pohon Huffman.
Membangun Pohon Huffman:

Berdasarkan statistik yang telah dikumpulkan, program akan membangun pohon Huffman statis. Pohon Huffman adalah struktur berhirarki yang digunakan untuk menentukan kode Huffman untuk masing-masing simbol. Simbol-simbol yang muncul lebih sering akan memiliki kode yang lebih pendek, sementara simbol-simbol yang muncul lebih jarang akan memiliki kode yang lebih panjang.
Pembuatan Tabel Kode:

Setelah pohon Huffman dibangun, program akan menghasilkan tabel kode yang mengaitkan setiap simbol dengan kode Huffman yang sesuai.
Kompresi Data:

Data asli akan diompresi dengan menggantikan setiap simbol dengan kode Huffman yang sesuai dari tabel kode. Ini akan menghasilkan data yang lebih pendek.
Penyimpanan Tabel Kode:

Untuk dekompresi nanti, program akan menyimpan tabel kode bersamaan dengan data yang telah diompresi. Ini penting agar data dapat didekompresi dengan benar.
Penyimpanan Data Kompresi:

Data yang telah diompresi dan tabel kode akan disimpan dalam suatu format yang dapat dibaca kembali nanti untuk proses dekompresi.
Dalam program Static Huffman Compression, pohon Huffman dan tabel kode biasanya dibangun sebelum data dikompresi, dan mereka tetap statis selama seluruh proses kompresi dan dekompresi. Ini berbeda dari metode Huffman dinamis di mana pohon Huffman dapat berubah selama kompresi berlangsung, yang memungkinkan penanganan lebih baik untuk data yang memiliki statistik yang berubah-ubah.

Program Static Huffman Compression sangat berguna untuk mengompresi data yang memiliki statistik simbol yang stabil dan tidak berubah seiring waktu. Namun, untuk data yang berubah secara dinamis, metode kompresi Huffman dinamis mungkin lebih cocok.
