# KALKULATOR KADAR BAJA (KG/HEKTAR)

## Deskripsi

Ini adalah aplikasi web ringkas yang dibangunkan untuk membantu pekebun dan petani mengira kadar taburan baja mereka dalam unit piawai **Kilogram per Hektar (kg/ha)**. Ia secara automatik melakukan penukaran unit luas dari **Ekar ke Hektar**.

## Formula Utama

Aplikasi ini menggunakan formula penukaran dan pengiraan berikut:

```
Total Berat Baja (kg) = Berat per Karung (kg) * Jumlah Karung

Total Luas (Hektar) = Luas Kawasan (Ekar) * 0.404686

Kadar Taburan (kg/ha) = Total Berat Baja (kg) / Total Luas (Hektar)
```

## Cara Menggunakan

1. Buka fail `index.html` dalam mana-mana pelayar web moden.
2. Masukkan nilai ke dalam tiga medan input berikut:

   * **Berat Baja Per Karung (kg):** Berat bersih setiap karung baja.
   * **Jumlah Karung Baja:** Bilangan karung yang akan digunakan.
   * **Luas Kawasan yang Ditabur (ekar):** Saiz kawasan tanah dalam ekar.
3. Hasil pengiraan (**kg per Hektar**) akan dipaparkan secara automatik di bahagian bawah.
4. Gunakan butang **Reset Data** untuk mengosongkan semua medan input dan memulakan pengiraan baharu.

## Struktur Fail

Projek ini terdiri daripada satu fail HTML, CSS, dan JavaScript:

* `index.html`: Fail utama dan satu-satunya yang mengandungi keseluruhan logik kalkulator.
* `output.css`: Fail style CSS.

---

Selamat Mengira dan Selamat Berkebun! 🌱
