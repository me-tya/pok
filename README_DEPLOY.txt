Keuangan Keluarga — GitHub Ready v40

Upload/replace SEMUA file dalam folder ini ke root repo GitHub Pages.
Firebase config sudah tertanam di app.js.

Perubahan v40:
- Nilai dasar Reksadana editable langsung: Unit, Harga Beli/Unit, Nilai Beli, NAB Hari Ini/Unit, Nilai Saat Ini.
- Nilai Beli <-> Harga Beli/Unit dihitung dua arah dari Unit.
- Nilai Saat Ini <-> NAB Hari Ini/Unit dihitung dua arah dari Unit.
- Total Nilai Beli dan Selisih Nilai tetap formula otomatis.
- Tombol edit ringkas pada metrik Reksadana membuka editor nilai dasar seluruh produk.
- Nilai 0 Deposito/Asuransi pada Ringkasan Aset dapat langsung mulai diisi lewat tombol edit.
- Tetap mempertahankan hierarchy Pengeluaran, kolom Sumber, edit sub-sub header, Firestore, CRUD, dan fitur portfolio sebelumnya.

Setelah commit, tunggu GitHub Pages selesai deploy lalu Ctrl+F5.


v41: Kolom Sumber + dropdown sumber dana diterapkan lintas Penerimaan, Pengeluaran, dan Aset; source tersimpan ke Firestore.


v42: Sync Schroder hanya mencoba kanal resmi Bank Mandiri/Livin (tanpa BCA/Bareksa). Jika gagal, modal Update NAB Manual otomatis dibuka.
