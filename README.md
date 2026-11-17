# HR Leave Portal: Monitoring Jadwal Cuti Pegawai
HR Leave Portal membantu HRD manajer memantau jadwal cuti pegawai berdasarkan
tanggal, bulan, dan tahun yang dipilih. Fitur ini hanya untuk monitoring
(melihat data), tanpa proses pengajuan atau persetujuan cuti.

## Fungsi Utama
- **Memilih periode cuti**: HRD manajer memilih tanggal, bulan, dan tahun, lalu
  sistem menampilkan pegawai yang mengajukan cuti pada periode tersebut.
- **Melihat pengajuan cuti**: setiap pengajuan menampilkan nama pegawai, jabatan,
  periode cuti, lama cuti, jenis cuti, dan status (Diajukan, Disetujui, Ditolak).
- **Melihat riwayat dan sisa cuti**: dengan memilih nama pegawai, HRD manajer
  dapat melihat riwayat cuti pegawai tersebut dan sisa cuti pada tahun berjalan.
- **Ringkasan periode**: jumlah pengajuan, jumlah pegawai yang cuti, dan total
  hari cuti pada periode yang dipilih.

## Cara Menggunakan
1. Buka file `hrd.html` di browser.
2. Pilih **bulan** dan **tahun** (pilih **tanggal** untuk melihat satu hari tertentu).
3. Lihat daftar pegawai yang cuti pada periode tersebut.
4. Klik nama pegawai untuk melihat riwayat cuti dan sisa cuti tahun berjalan.

## Catatan
- Data pegawai dan cuti pada versi ini berupa data contoh (dummy) yang tertanam
  di dalam halaman, sehingga tidak memerlukan server atau instalasi apa pun.
- Sisa cuti dihitung dari jatah cuti tahunan (12 hari) dikurangi cuti tahunan
  yang diajukan atau disetujui pada tahun berjalan.
- Modul ini berdiri sendiri dan terpisah dari modul pemesanan tiket (Travel).

## Developer
Raven Ravellyn Sulistyo
