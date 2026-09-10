# Peningkat Video FSR Online Gratis

Tingkatkan resolusi klip dengan upscaling FSR adaptif tepi di browser Anda.

HTML: https://grepcut.com/id/tools/video-upscaler

## Baca Ini Dulu: FSR Mempertajam Tepi, Bukan Menciptakan Detail

Atur ekspektasi Anda sebelum memulai. FSR membuat tepi lebih bersih saat memperbesar klip, tetapi pada rekaman yang sudah lembut, bitrate rendah, atau tidak fokus, perbaikannya seringkali marginal, karena hanya ada sedikit informasi tepi nyata yang dapat direkonstruksi.

FSR adalah upscaler spasial, bukan AI. Ia tidak dapat menambahkan detail yang tidak pernah ditangkap. Membangun kembali tekstur yang tidak ada di sumber Anda memerlukan model super-resolusi AI, yang merupakan alat yang berbeda. Gunakan upscaler ini untuk memperbesar dengan bersih dan mempertajam tepi, bukan untuk memulihkan detail yang hilang.

## Cara Upscale Video Online di Browser Anda

1. **Unggah klip Anda**: Letakkan file MP4, MOV, WebM, atau MKV ke area unggah.
2. **Pilih 2×, 3×, atau 4×**: Pilih faktor upscale yang sesuai dengan timeline, ekspor sosial, atau tata letak HD Anda.
3. **Ekspor MP4 Anda**: Unduh MP4 yang telah di-upscale, atau buka di GrepCut Studio untuk teks, potongan, dan penyelesaian.

Upscaling berjalan secara lokal di browser Anda, sehingga video Anda tetap di perangkat Anda.

## Gunakan FSR Upscaling Saat Klip Anda Terlalu Kecil

Jika klip Anda direkam pada 480p, 720p, atau dalam jendela screen-capture kecil, klip tersebut bisa terlihat terlalu kecil di dalam suntingan HD. Upscaling meningkatkan dimensi piksel sebelum Anda mengekspor, sehingga video Anda sesuai dengan timeline 1080p, unggahan YouTube, atau preset sosial tanpa peregangan manual di editor lain.

GrepCut melakukan upscale dengan FSR (AMD FidelityFX Super Resolution). Alih-alih peregangan halus biasa, FSR merekonstruksi tepi saat memperbesar, sehingga garis dan kontur tetap lebih tajam dibandingkan dengan penskalaan bikubik. Ini menjadikannya pilihan praktis untuk rekaman ponsel terkompresi, klip tutorial, dan repost yang diekspor terlalu kecil.

### Terbaik untuk:

- **Rekaman ponsel lama**: Bawa klip 480p atau 720p mendekati tata letak HD dengan tepi yang lebih bersih sebelum diposting.
- **Rekaman layar**: Buat jendela tangkapan kecil lebih mudah ditempatkan dalam suntingan tutorial atau presentasi.
- **Repost sosial**: Ubah ukuran klip vertikal yang kembali dari aplikasi lain dengan resolusi lebih rendah.

## Bagaimana FSR Upscaling Bekerja, dan Apa yang Bisa dan Tidak Bisa Diperbaiki

FSR adalah upscaler spasial: ia bekerja dari satu frame di depannya, tanpa vektor gerak, buffer kedalaman, atau model AI. Ia berjalan dalam dua pass GPU. Pertama, EASU (Edge-Adaptive Spatial Upsampling) meresampling frame dengan cara yang sadar arah, mendeteksi bagaimana gradien tetangga berbeda sehingga tepi direkonstruksi alih-alih hanya diburamkan. Kemudian RCAS (Robust Contrast-Adaptive Sharpening) menambahkan penajaman terkontrol yang mengangkat detail tanpa mendorong halo atau memperkuat noise.

Karena FSR menggunakan shader biasa dan tidak pernah melihat frame lain, ia memperlakukan setiap frame dengan cara yang sama dan menjaga konsistensi ekspor Anda. Namun, ini bukan super-resolusi AI. Jika sumber Anda buram parah, sangat terkompresi, atau kehilangan detail halus, FSR dapat menyesuaikan frame yang lebih besar dengan tepi yang lebih tajam, tetapi tidak dapat membangun kembali tekstur yang tidak pernah ditangkap.

### Di balik layar:

- **EASU**: Resample adaptif tepi yang merekonstruksi tepi saat memperbesar, lebih tajam dari bilinear atau bikubik.
- **RCAS**: Pass penajaman adaptif kontras, diterapkan secara otomatis, yang menambah ketajaman pada tepi nyata sementara area datar dibiarkan saja.

Untuk rekaman yang sangat lembut, coba ekspor uji pendek terlebih dahulu. Jika pratinjau sudah terlihat terlalu lembut, faktor yang lebih kecil seringkali terlihat lebih alami daripada peregangan 4× yang keras.

## Perbandingan FSR dengan Penskalaan Biasa

| Metode | Cara penskalaan | Hasil tipikal |
| --- | --- | --- |
| Nearest-neighbor | Menduplikasi piksel terdekat. | Tepi kotak-kotak, keras seperti tangga. |
| Bilinear atau bikubik | Merata-ratakan piksel di sekitarnya. | Lebih halus, tetapi tepi terlihat lembut. |
| FSR (EASU + RCAS) | Resample adaptif tepi ditambah penajaman sadar kontras. | Tepi lebih bersih dan tajam tanpa model AI. |

FSR merekonstruksi tepi daripada hanya menghaluskannya, tetapi seperti semua metode spasial, ia bekerja dengan detail yang sudah ada di klip Anda.

## Faktor Upscale Mana yang Harus Dipilih?

Faktor yang tepat tergantung pada seberapa jauh klip Anda dari ukuran yang dibutuhkan. Faktor yang lebih besar menciptakan lebih banyak piksel untuk direkonstruksi, sehingga sumber yang lembut menunjukkan batasnya lebih cepat pada 4× daripada pada 2×.

### Pilih faktor Anda:

- **2×**: Tes pertama yang aman saat klip Anda hanya membutuhkan peningkatan ukuran sedang.
- **3×**: Berguna saat klip kecil perlu mengisi lebih banyak kanvas HD.
- **4×**: Terbaik untuk klip pendek di mana Anda membutuhkan dimensi maksimum dan bisa menunggu sedikit lebih lama.

Mulailah dengan 2× jika Anda tidak yakin, lalu coba lagi dengan faktor yang lebih besar jika sumber Anda memiliki cukup detail untuk bertahan.

## Pratinjau Sama dengan Ekspor Anda

FSR melakukan upscale dan penajaman secara otomatis, jadi tidak ada yang perlu dikonfigurasi. Pilih faktor, periksa hasilnya, dan ekspor. EASU menangani pembesaran adaptif tepi dan RCAS menambahkan penajaman tetap yang sesuai di atasnya.

Pratinjau sebelum dan sesudah menjalankan pipeline FSR yang sama dengan ekspor, jadi apa yang Anda lihat adalah apa yang ada di MP4 Anda. Perbesar pratinjau untuk menilai ketajaman tepi sebelum Anda melakukan render penuh.

Jika pratinjau masih terlihat lembut setelah upscaling, itu biasanya berarti detailnya tidak ada di sumber sejak awal, dan faktor yang lebih rendah mungkin terlihat lebih alami.

## Jaga Privasi Video Anda Saat Menguji

Alat video online sering meminta Anda mengunggah seluruh file sebelum Anda dapat melihat hasilnya. Upscaler ini berjalan di browser Anda sebagai gantinya, sehingga rekaman Anda tidak meninggalkan perangkat Anda selama pemrosesan.

Ini berguna saat klip Anda berisi konten layar pribadi, rekaman sosial yang belum dirilis, draf klien, atau rekaman kelas. Anda dapat menguji faktor, mengunduh MP4, dan melanjutkan pengeditan tanpa mengirim file asli ke server.

Klip yang lebih panjang dan ekspor 4× tergantung pada kecepatan perangkat Anda. Untuk pemeriksaan cepat, potong klip terlebih dahulu atau uji bagian pendek sebelum memproses video penuh.

## Video Upscaler Sekilas

### Advantages

- Berjalan secara lokal di browser Anda tanpa unggahan.
- FSR merekonstruksi tepi, sehingga hasilnya terlihat lebih tajam daripada penskalaan bikubik.
- Upscaling EASU dan penajaman RCAS diterapkan secara otomatis, tidak ada yang perlu dikonfigurasi.
- Preset 2×, 3×, dan 4× membuat pilihan tetap sederhana.
- Ekspor MP4 gratis tanpa watermark.

### Disadvantages

- Ini adalah upscaler spasial, bukan AI, sehingga tidak dapat menciptakan detail yang tidak ditangkap.
- Sumber yang sangat buram atau sangat terkompresi masih bisa terlihat lembut.
- Ekspor 4× yang panjang bisa memakan waktu lebih lama pada perangkat yang lebih lambat.
- Jika browser Anda tidak memiliki WebGL2, ia akan kembali ke skala bikubik biasa.

> FSR 1 tidak melihat data frame sebelumnya untuk meningkatkan upscaling-nya tetapi hanya meregangkan setiap gambar yang terisolasi, menggunakan teknik seperti deteksi tepi untuk membantu menentukan cara terbaik meregangkan gambar.
>
> PCGamesN

## FAQ Video Upscaler

### Bisakah Anda upscale video online tanpa mengunggahnya?

Ya. Video Anda diproses secara lokal di browser Anda, sehingga file tetap di perangkat Anda.

### Apakah FSR sama dengan upscaling AI?

Tidak. FSR adalah upscaler spasial yang berjalan pada shader biasa dan bekerja dari satu frame. Ia merekonstruksi tepi dengan EASU dan menajamkan dengan RCAS, tetapi tidak menggunakan jaringan saraf, sehingga tidak dapat menciptakan detail seperti yang dicoba oleh super-resolusi AI.

### Apa perbedaan FSR dengan upscaling bikubik?

Bikubik merata-ratakan piksel di dekatnya, yang memperbesar frame tetapi meninggalkan tepi yang lembut. FSR melihat bagaimana gradien tetangga berubah dan meresampling di sepanjang tepi, sehingga garis dan kontur tetap lebih tajam, kemudian RCAS menambahkan penajaman terkontrol di atasnya.

### Apakah FSR akan membuat video buram Anda menjadi tajam?

Ini dapat membuat tepi terlihat lebih bersih dan menambah sedikit ketajaman, tetapi perbaikannya seringkali marginal pada rekaman yang lembut, dan tidak dapat memulihkan detail yang hilang dari sumber yang buram, bitrate rendah, atau tidak fokus. Memulihkan detail yang tidak ada memerlukan upscaler AI.

### Faktor upscale mana yang harus Anda gunakan?

Gunakan 2× untuk percobaan pertama yang aman, 3× saat klip Anda membutuhkan peningkatan ukuran yang lebih kuat, dan 4× untuk klip pendek resolusi rendah di mana Anda membutuhkan output terbesar.

### Bisakah Anda upscale video 480p untuk suntingan 1080p?

Ya. Anda dapat memperbesar klip sebelum menempatkannya di timeline HD. FSR menjaga tepi lebih bersih daripada peregangan biasa, meskipun hasilnya mungkin masih terlihat lebih lembut daripada rekaman 1080p asli karena aslinya memiliki lebih sedikit piksel.

### Apakah Anda perlu menyesuaikan pengaturan apa pun?

Tidak. FSR melakukan upscale dengan EASU dan menajamkan dengan RCAS secara otomatis, jadi Anda cukup memilih faktor dan mengekspor. Pratinjau sebelum dan sesudah menggunakan pipeline yang sama dengan ekspor.

### Format video apa yang dapat diimpor, dan apakah ada watermark?

Anda dapat mengimpor file MP4, MOV, WebM, dan MKV, dan mengekspor MP4 yang telah di-upscale tanpa watermark.

## Sumber & bacaan lebih lanjut

- [Ikhtisar GPUOpen AMD tentang FidelityFX Super Resolution 1 (EASU dan RCAS)](https://gpuopen.com/fidelityfx-superresolution/)
- [Manual teknik upscaling spasial FSR 1 GPUOpen AMD](https://gpuopen.com/manuals/fidelityfx_sdk/techniques/super-resolution-spatial/)
- [FidelityFX Super Resolution 1.0 demystified (panduan shader)](https://jntesteves.github.io/shadesofnoice/graphics/shaders/upscaling/2021/09/11/amd-fsr-demystified.html)
- [Tom's Hardware: menguji kinerja dan kualitas gambar FSR](https://www.tomshardware.com/news/amd-fidelityfx-super-resolution-fsr-performance-tested)
- [Thread forum guru3D: FSR 1 bagus untuk apa adanya](https://forums.guru3d.com/threads/fsr-1-is-great-actually-for-what-it-is.453779/)
- [Thread Reddit tentang mengapa rekaman yang diperbesar bisa terlihat buram](https://www.reddit.com/r/premiere/comments/1asd5id/scaling_up_video_to_a_higher_resolution_makes_it/)
- [Ikhtisar Wikipedia tentang metode penskalaan gambar](https://en.wikipedia.org/wiki/Image_scaling)

## Selesai Upscaling? Poles Suntingan Penuh

Buka MP4 yang telah di-upscale di GrepCut Studio untuk memotong timeline, menambahkan teks, menyesuaikan tampilan, dan mengekspor video akhir di browser Anda.

## Alat Terkait

- [Ubah Ukuran Video](https://grepcut.com/id/tools/resize-video) - skalakan klip Anda berdasarkan persentase.
- [Ubah Kecepatan Video](https://grepcut.com/id/tools/change-video-speed) - perlambat atau percepat rekaman Anda.
- [Buramkan Video](https://grepcut.com/id/tools/blur-video) - lembutkan latar belakang atau sembunyikan area sensitif.
