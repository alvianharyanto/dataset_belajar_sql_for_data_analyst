# dataset_belajar_sql_for_data_analyst
Repo ini berisi dataset  ketika saya belajar sql for data analyst. *semua data yang dilampirkan bukan merupakan data asli (hanya keperluan untuk belajar mengolah data pada PostgreSQL).
order_detail:
1. id → angka unik dari order / id_order
2. customer_id → angka unik dari pelanggan
3. order_date → tanggal saat dilakukan transaksi
4. sku_id → angka unik dari produk (sku adalah stock keeping unit)
5. price → harga yang tertera pada tagging harga
6. qty_ordered → jumlah barang yang dibeli oleh pelanggan
7. before_discount → nilai harga total dari produk (price * qty_ordered)
8. discount_amount → nilai diskon product total
9. after_discount → nilai harga total produk ketika sudah dikurangi dengan diskon
10. is_gross → menunjukkan pelanggan belum membayar pesanan
11. is_valid → menunjukkan pelanggan sudah melakukan pembayaran
12. is_net → menunjukkan transaksi sudah selesai
13. payment_id → angka unik dari metode pembayaran
sku_detail:
1. id → angka unik dari produk (dapat digunakan untuk key saat join)
2. sku_name → nama dari produk
3. base_price → harga barang yang tertera pada tagging harga / price
4. cogs → cost of goods sold / total biaya untuk menjual 1 produk
5. category → kategori produk
customer_detail:
1. id → angka unik dari pelanggan
2. registered_date → tanggal pelanggan mulai mendaftarkan diri sebagai anggota
Payment_detail:
1. id → angka unik dari metode pembayaran
2. payment_method → metode pembayaran yang digunakan
