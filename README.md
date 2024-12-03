# streambuilder_tyase

## Praktikum 6: StreamBuilder

### Langkah 1: Buat Project Baru

### Langkah 2: Buat file baru stream.dart

<img src = assets/gambar_1.jpg>

### Langkah 3: Tetap di file stream.dart

<img src = assets/gambar_2.jpg>

### Langkah 4: Edit main.dart

<img src = assets/gambar_3.jpg>

### Langkah 5: Tambah variabel

<img src = assets/gambar_4.jpg>

### Langkah 6: Edit initState()

<img src = assets/gambar_5.jpg>

### Langkah 7: Edit method build()

<img src = assets/gambar_6.jpg>

### Langkah 8: Run

**Soal 12**

- Jelaskan maksud kode pada langkah 3 dan 7 !

  - Langkah 3

    Kode tersebut membuat stream angka acak menggunakan Stream.periodic. Setiap detik, stream menghasilkan angka acak antara 0 hingga 9 dengan menggunakan objek Random. Metode getNumbers mengembalikan stream yang mengirimkan angka secara berkala dengan interval satu detik.

  - Langkah 7

    Kode menggunakan StreamBuilder untuk menampilkan data dari numberStream secara real-time. Jika ada error, mencetak "Error!" di konsol. Jika ada data, menampilkannya di tengah layar dengan teks besar. Jika tidak ada data, menampilkan widget kosong.

- Capture hasil praktikum Anda berupa GIF dan lampirkan di README.

    <img src = assets/gambar_7.gif>

- Lalu lakukan commit dengan pesan "W12: Jawaban Soal 12".
