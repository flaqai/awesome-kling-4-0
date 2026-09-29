<div align="center">

# Awesome Kling 4.0 Prompts — Panduan Bahasa Indonesia

52 prompt video orisinal dan siap produksi untuk film, iklan, UGC, dialog, VFX, animasi, makanan, perjalanan, pendidikan, dan media sosial.

[English](README.md) · **Bahasa Indonesia** · [Semua 15 bahasa](docs/LANGUAGES.md)

[Katalog](prompts/README.md) · [Metode lengkap](docs/PROMPT-GUIDE.md) · [Audio multibahasa](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **Status model — 29-09-2026:** Kling 4.0 Flash mulai tersedia dalam akses awal pada 28 September untuk pelanggan Ultra tahunan. Menurut [pengumuman resmi Kling AI](https://sg.linkedin.com/company/kling-ai-api), Kling 4.0 versi lengkap dan akses API direncanakan hadir pada Oktober 2026; tanggal pastinya belum diumumkan. Durasi generasi asli hingga **30 detik** diumumkan untuk versi lengkap dan belum terkonfirmasi sebagai batas yang tersedia di Flash. Prompt yang ada berdurasi 5–15 detik.

## Kling 4.0: fitur baru dan ketersediaan

Menurut [pengumuman resmi Kling AI di X](https://x.com/Kling_ai/status/2104596718067257458), Flash sudah tersedia lebih awal untuk pelanggan Ultra tahunan; model 4.0 lengkap dan API dijadwalkan hadir pada Oktober 2026. Untuk versi lengkap diumumkan durasi hingga 30 detik per generasi, 10 keyframe, 15 referensi multimodal, keluaran hingga 4K/10-bit HDR, audio stereo, serta dukungan bahasa dan aksen yang lebih luas. **Angka-angka ini bukan batas Flash yang sudah terverifikasi.** Ke-52 prompt yang ada memakai garis waktu 5–15 detik. Halaman FLAQ.AI untuk 4.0 [teks-ke-video](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) dan [gambar-ke-video](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) masih bertanda “Coming Soon”, bukan API 4.0 yang sudah aktif.

## Video dan prompt dari X

**Diperiksa pada 29-09-2026.** [Video peluncuran resmi](https://x.com/Kling_ai/status/2104596718067257458) adalah montase keluarga 4.0; total durasinya tidak membuktikan Flash dapat menghasilkan klip sepanjang itu dalam sekali proses. Contoh berikut adalah uji coba menurut pembuatnya, bukan benchmark resmi atau hasil yang diuji ulang secara mandiri oleh proyek ini. Lihat video dan prompt lengkap di unggahan asal; kami tidak menyalinnya.

| Unggahan asal | Teknik prompt yang bisa dicoba |
|---|---|
| [Umesh: kejar-kejaran kucing malam hari, 20 dtk](https://x.com/umesh_ai/status/2104595267794460949) · [prompt asli](https://x.com/umesh_ai/status/2104595270671724936) | Pertahankan satu subjek, rute yang tersambung, dan satu kejadian fisik di tiap lokasi; kamera terus mengikuti tanpa potongan. |
| [OscarAI: konser anime, 20 dtk, dengan prompt](https://x.com/Artedeingenio/status/2104829034299351079) | Pada uji awal, pembuatnya lebih menyukai arahan singkat dan lugas, tetapi mengakui hasilnya tidak sepenuhnya patuh. Coba subjek → perubahan → kamera → akhir. |
| [とすくん: perubahan cuaca, 15 dtk](https://x.com/tokyo_Valentine/status/2104810060811833710) · [prompt asli](https://x.com/tokyo_Valentine/status/2104810064750239987) | Batasi lembar karakter untuk identitas dan pakaian; tentukan waktu perubahan cuaca, cahaya, dan akting secara terpisah. |
| [Alexandra Dekimpe: pengujian alur produksi](https://x.com/HadesDesign/status/2104878440889417957) | Jelaskan gerak mikro yang terlihat, bukan emosi abstrak; gunakan “hanya setelah” untuk urutan sebab-akibat; tulis dialog persis atau minta tanpa dialog. Ini pengamatan pribadi. |
| [Aswin Aji Raj: UGC bahasa Hindi, 20 dtk](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | Prompt lengkap tidak dibagikan. Sebutkan pembicara dan kalimat tepat; tinjau pelafalan, sinkronisasi bibir, dan klaim produk. |
| [@plasm0: perbandingan 3.0/Flash dengan prompt sama](https://x.com/plasm0/status/2104597949485629557) | Pertahankan prompt dan referensi saat uji A/B, catat pengaturan. Sepasang video bukan benchmark formal. |

**Latihan vertikal orisinal 15 detik yang belum diuji** (di luar 52 resep katalog; tidak menyalin teks X):

~~~text
[SUBJEK/REFERENSI] Satu lampu sepeda isi ulang tanpa merek, bodi grafit dof dan satu tombol kuning ambar. Jika ada gambar, gunakan hanya untuk mengunci bentuk lampu.
[ADEGAN/KAMERA] Bengkel sepeda tenang saat senja. Satu pengambilan dekat berkelanjutan dari tangan mekanik ke lampu lalu setang. Cahaya alami dari jendela; tanpa potongan atau perpindahan mendadak.
[0–4 dtk] Letakkan lampu yang belum menyala di samping setang; tampilkan kedua tangan dan dudukan.
[4–8 dtk] Kunci lampu ke dudukan. Hanya setelah bunyi klik penguncian, ibu jari menekan tombol ambar.
[8–12 dtk] Lampu menyala tepat sekali dan menerangi roda depan serta sedikit lantai. Kamera bergeser perlahan ke samping untuk menampilkan berkas cahaya.
[12–15 dtk] Tangan dilepas dari setang; lampu tetap terpasang. Tahan bingkai akhir yang stabil.
[AUDIO/BATASAN] Suasana bengkel, satu klik pemasangan dan satu klik tombol; tanpa ucapan atau musik. Pertahankan bentuk, jumlah tangan, posisi dudukan, dan arah cahaya. Tanpa teks merek, lampu tambahan, atau potongan tanpa alasan.
~~~

Uji arahan singkat dan arahan panjang yang terstruktur. Catat mode, durasi, referensi, dan hasil sebelum menyebut resep “teruji”. Kontribusi orisinal diterima melalui [panduan kontribusi](CONTRIBUTING.md).

## Struktur singkat

```text
[OUTPUT] durasi, rasio, satu pengambilan/multishot, tampilan
[KONTINUITAS] ciri tetap karakter, pakaian, produk, dan properti
[RUANG] lokasi, waktu, cahaya, dan posisi awal
[SHOT BERWAKTU] satu aksi utama + satu tujuan kamera per bagian
[PERFORMA DAN FISIKA] tatapan, napas, kontak, berat, dan inersia
[AUDIO] pembicara, bahasa, nada, ambience, foley, dan musik
[BATASAN] identitas, arah, cahaya, teks, logo, dan deformasi
```

Bahasa Indonesia adalah bahasa dokumentasi proyek, tetapi tidak termasuk dalam daftar bahasa dialog asli Kling 3.0 yang telah diverifikasi. Uji suara pada model aktif atau tambahkan sulih suara yang ditinjau saat pascaproduksi.

## Pilihan cepat

- [Reuni multibahasa](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)
- [Iklan minuman botani](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)
- [Pengejaran fiksi ilmiah](prompts/action-and-vfx.md#1-the-glass-manta-pursuit)
- [Loop komedi payung](prompts/education-documentary-social.md#3-the-infinite-umbrella-problem)

## Tentang FLAQ.AI

> Per 29-09-2026, halaman FLAQ.AI untuk 4.0 [teks-ke-video](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) dan [gambar-ke-video](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) masih bertanda “Coming Soon”. Akses awal Flash di Kling tidak berarti API 4.0 FLAQ.AI sudah tersedia.

[FLAQ.AI](https://flaq.ai/) adalah platform web dan lapisan API terpadu untuk model gambar, video, dan bahasa. Saat ini tersedia halaman [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) dan [Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/). Proyek ini tidak menyatakan Kling 4.0 sudah tersedia. Periksa kontrol, harga, dan dokumentasi API langsung sebelum produksi.
