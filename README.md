# Hapcuuiu

Kalkulator proyeksi modal, profit, dan cut loss untuk day trading saham IDX — lengkap dengan jurnal transaksi dan ringkasan bulanan. Satu file HTML statis, tanpa build step, data tersimpan lokal di browser (localStorage).

## Fitur

- **Kalkulator** — hitung jumlah lot maksimal dari modal & harga entry, lalu proyeksi hasil untuk skenario Take Profit maupun Cut Loss (nilai jual, fee, estimasi profit/rugi, modal akhir, Risk:Reward).
- **Jurnal Transaksi** — simpan tiap setup trade, update status (Rencana / Take Profit / Cut Loss / Manual) dan hasil realnya terhitung otomatis.
- **Ringkasan Bulanan** — agregasi otomatis Keuntungan, Kerugian, Net Profit per bulan beserta perbandingan terhadap bulan sebelumnya.

## Menjalankan

Buka `index.html` langsung di browser, atau serve dengan server statis apa saja, misalnya:

```bash
python3 -m http.server 8000
```

lalu buka `http://localhost:8000`.
