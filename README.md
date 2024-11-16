# Aplikasi Pertambahan Dua Angka

Aplikasi ini memungkinkan pengguna untuk memasukkan dua angka, menjumlahkannya, dan menampilkan hasilnya. Aplikasi ini juga memiliki fitur untuk menghapus input dan keluar dari aplikasi.

## Fitur

1. **Input Dua Angka**: 
   - Pengguna dapat memasukkan dua angka ke dalam `JTextField`.
2. **Pertambahan**:
   - Saat tombol **Tambah** ditekan, aplikasi akan menampilkan hasil pertambahan kedua angka.
3. **Penghapusan Input**:
   - Saat tombol **Hapus** ditekan, nilai di `JTextField` akan dihapus, dan fokus akan diarahkan kembali ke input angka pertama.
4. **Keluar dari Aplikasi**:
   - Tombol **Keluar** memungkinkan pengguna menutup aplikasi dengan mudah.
5. **Validasi Input**:
   - Input numerik akan divalidasi untuk memastikan hanya angka yang diperbolehkan.

## Komponen GUI

Aplikasi ini menggunakan beberapa komponen GUI berbasis Java Swing, yaitu:
- **`JFrame`**: Untuk jendela utama aplikasi.
- **`JPanel`**: Sebagai wadah komponen GUI.
- **`JLabel`**: Untuk label teks.
- **`JTextField`**: Untuk input angka.
- **`JButton`**: Untuk tombol operasi seperti Tambah, Hapus, dan Keluar.

## Logika Program

1. **Penambahan Dua Angka**:
   - Input dari dua `JTextField` dijumlahkan dan ditampilkan.
2. **Validasi Input**:
   - Hanya menerima angka sebagai input menggunakan `KeyAdapter`.

## Event Handling

1. **`ActionListener`**:
   - Menangani aksi pada tombol:
     - **Tambah**: Menghitung dan menampilkan hasil pertambahan.
     - **Hapus**: Menghapus input dan mengarahkan fokus ke input pertama.
     - **Keluar**: Menutup aplikasi.
2. **`KeyAdapter`**:
   - Membatasi input hanya angka pada `JTextField`.
3. **`FocusListener`**:
   - Membersihkan `JTextField` saat mendapatkan fokus.

## Variasi Fitur

- Membatasi input pada `JTextField` hanya berupa angka menggunakan **`KeyAdapter`**.
- Menampilkan pesan error untuk input yang tidak valid menggunakan **`JOptionPane`**.
- Membersihkan `JTextField` secara otomatis menggunakan **`FocusListener`** saat mendapatkan fokus.

## Cara Menggunakan

1. Jalankan aplikasi.
2. Masukkan dua angka pada kolom input.
3. Tekan tombol:
   - **Tambah**: Untuk menampilkan hasil pertambahan.
   - **Hapus**: Untuk menghapus input dan mengatur ulang fokus.
   - **Keluar**: Untuk menutup aplikasi.

---

### Catatan

Aplikasi ini dibangun menggunakan Java Swing. Pastikan Anda memiliki JDK yang terinstal untuk menjalankan aplikasi ini.

- Muhammad Hidayat 2210010354
- Latihan 1
