# Tugas-BesarKelompok_J
reviu.in adalah aplikasi pencatat ulasan kuliner. Reviewer dapat mengulas banyak restoran, dan satu restoran dapat diulas banyak reviewer, termasuk kunjungan berulang dengan ulasan berbeda. Setiap ulasan dinilai dari rasa, harga, pelayanan, dan suasana.
---

## Struktur Data

| List | Deskripsi |
|----------|--------|
| Parent | Food Reviewer (id reviewer, nama, platform, jumlah pengikut) |
| Child | Restoran (id restoran, nama restoran, alamat, kategori restoran, kisaran harga) |
| Relasi | Riwayat Kunjungan (tanggal kunjungan pertama, tanggal kunjungan terakhir, jumlah
kunjungan, status hubungan) |
| Binary Search Tree | Ulasan Kuliner dengan key rating keseluruhan (id reviewer, id restoran, tanggal
kunjungan, nama menu, rating rasa, rating harga, rating pelayanan, rating suasana,
rating keseluruhan, estimasi biaya, komentar, rekomendasi, status ulasan) |

---

## Fitur / Fungsional Program
### Fungsional Umum
 Fungsionalitas yang harus terpenuhi untuk Multi-Linked list adalah
1. Menyisipkan elemen parent, child dan relasi (first, last, after)
2. Menghapus elemen parent, child dan relasi (first, last, after)
3. Mencari elemen parent, child dan relasi
4. Menampilkan seluruh data pada list (parent, child, relasi)
5. Membuat data dummy untuk masing-masing list minimal 5 data (parent,child)
dan 10 data (relasi)
6. Melengkapi Main Program (interface)

 Fungsionalitas yang harus terpenuhi untuk Binary Search tree
adalah
1. Menyisipkan node berdasarkan key pada masing-masing topik
2. Menghapus node berdasarkan key pada masing-masing topik
3. Mencari node berdasarkan key pada masing-masing topik
4. Menampilkan seluruh data traversal (in-order, pre-order, dan post-order).
5. Menampilkan nilai minimum, maksimum, tinggi pohon, dan jumlah node.
6. Membuat data dummy untuk BST minimal 10 node.
7. Melengkapi Main Program (interface)

### Fungsional khusus
• Mencatat kunjungan dan ulasan kuliner dengan memilih reviewer dan restoran
tersedia serta memperbarui riwayat kunjungan pada relasi reviewer dan
restoran.
• Menyimpan ulasan ke BST berdasarkan rating keseluruhan.
• Menampilkan informasi restoran dengan rating keseluruhan tertinggi.
• Menampilkan total transaksi aplikasi.


### Fungsional tambahan (Bonus)
• Menampilkan informasi restoran dengan rating tertinggi berdasarkan masingmasing aspek (rasa, harga, pelayanan, dan suasana).
• Menampilkan informasi informasi reviewer dengan riwayat kunjungan paling
sedikit.
• Menampilkan riwayat kunjungan dan ulasan seorang reviwer.
---

