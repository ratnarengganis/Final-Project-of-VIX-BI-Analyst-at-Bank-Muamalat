# Final-Project-of-VIX-BI-Analyst-at-Bank-Muamalat

### Overview
Repositori ini berisi proyek akhir untuk Program Virtual Intership sebagai BI Analyst di Bank Muamalat x Rakamin Academy. Proyek ini berfokus pada analisis dan visualisasi data penjualan PT Sejahtera Bersama. Melibatkan berbagai tugas seperti menentukan primary key pada 4 tabel yang ada di dataset penjualan yaitu tabel customers, tabel orders, tabel products dan tabel produccategory, kemudian menetapkan hubungan antar tabel, membuat tabel master, mengembangkan dashboard interaktif menggunakan Looker, mencari insigh serta memberikan rekomendasi untuk perusahaan.

### Tujuan
Tujuan dari proyek ini adalah untuk menunjukkan keahlian dalam analisis data, SQL, dan alat visualisasi data seperti Looker. Dengan menyelesaikan tugas-tugas dan menghasilkan insight dan rekomendasi yang berharga, proyek ini menampilkan kemampuan untuk menggunakan data untuk mendukung proses pengambilan keputusan dalam lingkungan bisnis.

### Tugas Proyek
1. Menentukan primary key untuk empat tabel dalam dataset penjualan
2. Menetapkan hubungan antar tabel
3. Membuat tabel master dengan menggabungkan empat tabel awal
4. Mengembangkan dashboard interaktif menggunakan Looker untuk visualisasi data
5. Mendapatkan insight yang berarti dari visualisasi tersebut
6. Memberikan rekomendasi yang actionable untuk meningkatkan strategi penjualan PT Sejahtera Bersama.

### Pengerjaan Tugas 1-5
  #### Tugas 1: Penentuan Primary Key
1. Tabel Customer:
   - Primary Key: CustomerID

2. Tabel Products:
   - Primary Key: ProdNumber

3. Tabel Orders:
   - Primary Key: OrderID

4. Tabel ProductCategory:
   - Primary Key: CategoryID

#### Tugas 2: Hubungan Antar Tabel

1. Hubungan antara "Customers" dan "Orders":
   - Tabel "Customers" memiliki primary key CustomerID.
   - Tabel "Orders" memiliki kolom CustomerID sebagai foreign key yang mengacu pada nilai CustomerID dalam tabel "Customers".
   - Hubungan ini dapat disebut sebagai "one-to-many" karena satu pelanggan dalam tabel "Customers" dapat memiliki banyak pesanan dalam tabel "Orders", tetapi setiap pesanan hanya terkait dengan satu pelanggan.

2. Hubungan antara "Orders" dan "Products":
   - Tabel "Products" memiliki primary key ProdNumber.
   - Tabel "Orders" memiliki kolom ProdNumber sebagai foreign key yang mengacu pada nilai ProdNumber dalam tabel "Products".
   - Hubungan ini dapat disebut sebagai "many-to-one" karena banyak pesanan dalam tabel "Orders" dapat menggunakan produk yang sama dari tabel "Products", tetapi setiap produk hanya memiliki satu entri (pesanan) dalam tabel "Orders".

3. Hubungan antara "Products" dan "ProductCategory":
   - Tabel "ProductCategory" memiliki primary key CategoryID.
   - Tabel "Products" memiliki foreign key Category yang mengacu pada nilai CategoryID dalam tabel "ProductCategory".
   - Hubungan ini dapat disebut sebagai "many-to-one" karena banyak produk dalam tabel "Products" termasuk dalam satu kategori tertentu dalam tabel "ProductCategory", tetapi setiap kategori hanya memiliki satu entri (produk) dalam tabel "Products".

- Tugas 3: Membuat tabel master dengan menggabungkan data dari tabel-tabel yang telah dihubungkan.
- Tugas 4: Mengembangkan dashboard interaktif menggunakan Looker untuk menampilkan visualisasi data penjualan.
- Tugas 5: Melakukan analisis terhadap visualisasi data untuk mendapatkan insight yang relevan.

### Project Files
- [Link Google Sheet](https://docs.google.com/spreadsheets/d/1GI4YFa3cE87rI35UBNYVnAsFaVsaT8HvkpfqrAEzCpg/edit?usp=drive_link) - Raw data penjualan yang digunakan untuk analisis.
- [Link Looker Dashboard](https://lookerstudio.google.com/s/vHJehnkFVRQ) - Dashboard, visualisasi data di Looker Studio.

### Alat yang Digunakan
- Google BigQuery untuk analisis dan manipulasi data.
- Looker untuk visualisasi data interaktif.
