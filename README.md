# Proyek Analisis Bisnis Kimia Farma (2020-2023)
### Dashboard Analisis Pendapatan dan Pertumbuhan

## 📌 Gambaran Umum
Proyek ini menganalisis data transaksi, inventaris, dan cabang **Kimia Farma** untuk mengidentifikasi tren pendapatan dan pertumbuhan bisnis periode 2020-2023.

## 🏢 Tentang Kimia Farma
Perusahaan farmasi terintegrasi dengan jaringan 1.000+ apotek dan klinik di seluruh Indonesia, fokus pada produksi obat-obatan dan layanan kesehatan.

## 🔍 Tujuan Proyek
1. Analisis performa penjualan per cabang
2. Identifikasi produk unggulan
3. Evaluasi strategi diskon
4. Rekomendasi pengembangan bisnis

## 🛠️ Implementasi Teknis
### 1. Sumber Data
Menggunakan 4 tabel utama dari database Kimia Farma:

1. **Tabel Final Transaction**  
   - Berisi: ID transaksi, tanggal, ID cabang, nama pelanggan, ID produk, harga, persentase diskon  
   - Contoh data: Transaksi obat psikotropika dengan diskon 10-15%

2. **Tabel Inventory**  
   - Berisi: ID inventaris, ID cabang, ID produk, nama produk, stok opname  
   - Contoh data: Stok obat anti-inflamasi di cabang Jakarta

3. **Tabel Kantor Cabang**  
   - Berisi: ID cabang, kategori cabang, nama cabang, kota, provinsi, rating  
   - Contoh data: Cabang Apotek Kimia Farma di Surabaya dengan rating 4.5

4. **Tabel Produk**  
   - Berisi: ID produk, nama produk, harga, kategori  
   - Contoh data: Obat KF116 (Psikoleptik) dengan harga Rp850.000

### 2. Proses Analisis
1. **Integrasi Data**: Menggabungkan 4 tabel menggunakan key fields (ID cabang, ID produk)
2. **Transformasi**: 
   - Menghitung nett sales (harga setelah diskon)
   - Kategorisasi produk berdasarkan margin profit
3. **Agregasi**: 
   - Total penjualan per provinsi
   - Performa produk per kategori

## 📊 Hasil Analisis
**Temuan Kunci**:
- Jawa Barat menyumbang 42% total pendapatan
- Produk psikotropika mendominasi penjualan (27%)
- Cabang Subang memiliki transaksi tertinggi

🔗 [Dashboard Lengkap](https://lookerstudio.google.com/reporting/aa849070-5d8b-4de4-a2a3-4f3519941c2a)


## 👩‍💻 Penulis
**Nasywa Syafinka Widyamara**  
Mahasiswi Sistem Informasi Bisnis  
[Portfolio](github.com/nasywasyafinka) | [LinkedIn](linkedin.com/in/nasywasyafinka)
