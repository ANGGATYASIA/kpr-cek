# KPR CEK!

Simulasi peluang persetujuan KPR dalam ±2 menit. Jawab 7 pertanyaan,
dapat satu angka estimasi peluang lolos — lengkap dengan rincian
penilaian per faktor dan saran perbaikan.

## Cara pakai

Buka `index.html` di browser, atau akses versi online-nya. Isi tiga langkah:

1. **Profil** — usia, pekerjaan, lama bekerja/usaha
2. **Keuangan** — penghasilan bersih, cicilan berjalan, riwayat kredit (SLIK OJK)
3. **Properti** — harga, DP, tenor, suku bunga

Hasilnya berupa persentase peluang lolos, rincian enam faktor penilaian, dan saran konkret untuk menaikkan peluang.

## Metode penilaian

Enam faktor dengan bobot, mengacu pada praktik umum perbankan di Indonesia:

| Faktor | Bobot |
|---|---|
| Rasio total cicilan terhadap penghasilan (DSR) | 35% |
| Riwayat kredit / SLIK OJK | 20% |
| Jenis pekerjaan | 15% |
| Kesesuaian usia dan tenor | 10% |
| Rasio uang muka (DP) | 10% |
| Masa kerja / usaha | 10% |

Estimasi angsuran memakai rumus anuitas standar. Batas usia akhir kredit mengikuti ketentuan umum bank: 55 tahun (karyawan) dan 60–65 tahun (profesional/wiraswasta, tergantung bank).

## Catatan

Simulasi bersifat edukasi, bukan jaminan persetujuan. Keputusan akhir tetap ada pada analis bank. Seluruh perhitungan berjalan di perangkat pengguna — tidak ada data yang dikirim ke server.
