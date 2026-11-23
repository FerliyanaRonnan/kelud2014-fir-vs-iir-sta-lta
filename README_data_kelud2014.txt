Data seismik Kelud 2014 - stasiun GE.JAGI, kanal BHZ (vertikal broadband)
Sumber: GEOFON (GFZ) FDSN, jaringan GE (DOI 10.14470/TR560404). Format asli: miniSEED.
Sampling rate : 20 Hz (dt = 0,05 s)
Rentang waktu : 2014-02-13T11:44:45.419538Z s/d 2014-02-13T20:00:06.819538Z UTC (594429 sampel)
Kolom         : waktu_utc | detik_dari_awal | counts (mentah, belum dikoreksi instrumen) | segmen
segmen=warmup  : sebelum 14:00 UTC (hanya untuk mengisi memori filter & jendela LTA)
segmen=analisis: 14:00-20:00 UTC (jendela deteksi)
Catatan: file warm-up & analisis asli tumpang tindih ~21 detik; di CSV ini sudah digabung tanpa duplikasi/gap.
Stasiun: -8.4702, 114.1521, elev 171 m | Gunung Kelud: -7.926, 112.308 | jarak ~211 km
Baca di Python: pd.read_csv('kelud2014_JAGI_BHZ_gabungan.csv')
