# Tambahkan Audio ke Video Online

Seret video dan file audio - GrepCut mengganti soundtrack tanpa meng-encode ulang gambar. Tidak ada data yang meninggalkan perangkat Anda.

HTML: https://grepcut.com/id/tools/add-audio-to-video

## Cara Menambahkan Audio ke Video di Browser Anda

1. **Pilih video Anda**: Seret file MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP, atau MPEG ke GrepCut. Video Anda tetap di perangkat Anda.
2. **Pilih audio Anda**: Tambahkan satu file MP3, WAV, AAC, M4A, FLAC, OGG, atau Opus. File ini akan menjadi soundtrack pengganti.
3. **Campur dan ekspor**: Klik Campur & ekspor. GrepCut menggabungkan aliran video dan audio baru Anda menjadi satu MP4.
4. **Unduh hasilnya**: Simpan MP4 dengan tambahan -with-audio pada nama file. Ekspor berhenti pada input yang lebih pendek dari keduanya.

Perlu melapisi musik latar dengan suara asli, menyesuaikan volume, memudarkan audio, atau menyinkronkan trek beberapa frame? Buka [GrepCut Studio](/) sebagai gantinya.

## Apa yang Sebenarnya Diubah oleh Penggantian Audio Ini

Jika Anda sudah memiliki video jadi dan file voiceover, lagu, narasi, atau audio bersih terpisah, Anda tidak perlu editor lengkap hanya untuk mengganti soundtrack. GrepCut mengambil aliran video dari file pertama Anda dan aliran audio dari file kedua, lalu menulisnya menjadi satu MP4.

Soundtrack asli Anda tidak dipertahankan. File audio baru menjadi satu-satunya trek audio dalam ekspor. Ini berguna saat klip Anda sunyi, bising, dibisukan oleh platform, atau diekspor dengan pengambilan audio yang salah.

Aliran video disalin jika memungkinkan, sehingga gambar tidak dikompresi ulang hanya karena Anda mengubah audio. Jika codec video tidak dapat disalin ke MP4 dengan bersih, Anda mungkin memerlukan alur kerja berbeda di editor lengkap.

Ide utamanya sederhana: Anda mengganti satu trek, bukan membangun ulang seluruh suntingan.

## Penggantian Audio vs Penyuntingan Penuh

| Apa yang Anda butuhkan | Gunakan alat cepat ini | Gunakan GrepCut Studio |
| --- | --- | --- |
| Ganti audio kamera yang buruk dengan MP3 atau WAV terpisah | Ya, ini alur kerja utama | Hanya jika Anda juga perlu suntingan |
| Tambahkan voiceover ke rekaman layar yang sunyi | Ya, jika satu file audio cukup | Gunakan untuk penyesuaian waktu |
| Pertahankan audio asli dan tambahkan musik di atasnya | Tidak, audio asli diganti | Ya, gunakan beberapa trek |
| Memudarkan musik masuk atau keluar | Tidak, hanya penggantian cepat | Ya, gunakan kontrol volume |
| Perbaiki audio yang mulai terlambat atau terlalu awal | Tidak ada kontrol sinkronisasi presisi di sini | Ya, sejajarkan di garis waktu |

Gunakan alat cepat saat video dan audio pengganti Anda sudah cocok. Gunakan Studio saat audio Anda memerlukan penyuntingan, pencampuran, atau penyesuaian waktu.

## Input Video dan Audio yang Didukung

Mulai dengan satu file video. GrepCut dibangun di sekitar input MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP, dan MPEG, plus file video lain yang dapat dibaca saat browser dan FFmpeg dapat memprosesnya.

Kemudian tambahkan satu file audio. MP3, WAV, AAC, M4A, FLAC, OGG, dan Opus adalah input audio yang telah diuji. Outputnya selalu MP4, yang membuat hasilnya lebih mudah dibagikan, diputar, dan diimpor ke aplikasi umum.

### Beberapa catatan format praktis:

- **MP4 dan MOV**: baik untuk klip ponsel, rekaman layar, ekspor kamera, dan draf media sosial.
- **WebM dan MKV**: berguna saat sumber Anda berasal dari perekam browser, unduhan, atau alur kerja sumber terbuka.
- **WAV dan FLAC**: baik untuk voiceover bersih atau master musik sebelum MP4 akhir dibuat.
- **OGG dan Opus**: berguna untuk audio yang direkam oleh aplikasi web, game, atau alat media terbuka.

Jika file terbuka tetapi ekspor gagal, penyebab biasanya bukan ekstensi file. Itu adalah codec di dalam wadah.

## Mengapa Ekspor Anda Berhenti di File yang Lebih Pendek

GrepCut memotong ekspor ke input yang lebih pendek sehingga Anda tidak mendapatkan ekor hitam panjang, akhir yang sunyi, atau audio tambahan tersembunyi setelah gambar berakhir. Jika lagu Anda lebih panjang dari klip, lagu dipotong di akhir video. Jika voiceover Anda lebih pendek dari klip, video yang diekspor berakhir saat voiceover berakhir.

Perilaku itu disengaja untuk alat pengganti cepat. Ini menjaga hasil tetap dapat diprediksi tanpa menambahkan pengulangan, bantalan, pemudaran, atau pembuatan keheningan. Untuk pilihan waktu tersebut, gunakan garis waktu penuh di GrepCut Studio.

## Apa yang Anda Dapatkan dengan Penggantian Audio Berbasis Browser

### Advantages

- Video dan audio Anda tetap di perangkat Anda tanpa unggahan.
- Gambar tidak dienkode ulang saat penyalinan aliran dimungkinkan.
- Anda mendapatkan MP4 yang lebih mudah diputar dan dibagikan.
- Anda dapat mengganti audio yang bising, dibisukan, atau salah tanpa membuka garis waktu penuh.
- Anda dapat menggunakan input video umum dan format audio umum.

### Disadvantages

- Hanya satu file audio pengganti yang digunakan.
- Audio asli dihapus, bukan dicampur di bawahnya.
- Perubahan volume, pemudaran, ducking, dan sinkronisasi tepat memerlukan GrepCut Studio.
- File yang sangat besar bergantung pada memori perangkat dan batas browser Anda.
- Beberapa codec yang tidak biasa mungkin perlu konversi sebelum cocok di dalam MP4.

> rendering membuat video menjadi 3 kali lebih besar atau ada penurunan kualitas yang signifikan untuk ukuran file yang sama
>
> Reddit r/davinciresolve

## FAQ Tambah Audio ke Video

### Bisakah Anda mengganti audio di MP4 tanpa merender video lagi?

Ya, saat aliran video dapat disalin ke output MP4. GrepCut mencoba menyalin aliran gambar alih-alih mengenkode ulang, sehingga mengubah soundtrack tidak otomatis berarti kehilangan kualitas gambar.

### Apakah video atau audio Anda akan diunggah?

Tidak. GrepCut menjalankan penggantian audio secara lokal di browser Anda menggunakan FFmpeg yang dikompilasi ke WebAssembly. File Anda tetap di perangkat Anda.

### Bisakah Anda mempertahankan suara asli dan menambahkan musik di atasnya?

Tidak di alat cepat ini. Audio pengganti menjadi satu-satunya soundtrack. Gunakan [GrepCut Studio](/) jika Anda memerlukan musik, dialog, dan efek suara yang diputar bersamaan.

### Apa yang terjadi jika audio Anda lebih panjang dari video Anda?

Ekspor berhenti di akhir file yang lebih pendek. Jika audio Anda berjalan lebih lama dari video, itu dipotong. Jika audio Anda lebih pendek, video berakhir bersamanya.

### Bisakah Anda menyinkronkan audio yang mulai terlalu awal atau terlalu lambat?

Alat ini tidak menyertakan kontrol offset. Jika voiceover Anda memerlukan penyelarasan tingkat bingkai, buka video di [GrepCut Studio](/) dan pindahkan audio di garis waktu.

### Format apa yang bisa Anda tambahi audio?

Anda dapat memulai dengan video MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP, atau MPEG. Audio pengganti Anda bisa MP3, WAV, AAC, M4A, FLAC, OGG, atau Opus. File yang diunduh adalah MP4.

### Mengapa GrepCut mengekspor MP4 alih-alih mempertahankan wadah asli?

MP4 didukung secara luas oleh browser, ponsel, editor, dan aplikasi sosial. Mempertahankan satu wadah output juga membuat alat cepat lebih sederhana dan lebih dapat diprediksi.

### Apakah file Anda akan kehilangan kualitas?

Gambar harus tetap sama saat penyalinan aliran berfungsi. Audio diambil dari file pengganti Anda dan digabungkan ke output, sehingga hasilnya tergantung pada kualitas file audio yang Anda berikan.

## Sumber & bacaan lebih lanjut

- [Diskusi Reddit tentang mengganti audio MP4 tanpa rendering](https://www.reddit.com/r/davinciresolve/comments/1fnsfjb/how_do_i_replace_the_audio_of_an_mp4_without/)
- [Thread Super User tentang mengganti audio di video dengan FFmpeg](https://superuser.com/questions/1137612/ffmpeg-replace-audio-in-video)
- [Thread Super User tentang perilaku panjang audio dan video](https://superuser.com/questions/801547/ffmpeg-add-audio-but-keep-video-length-the-same-not-shortest)
- [Diskusi Reddit tentang menyunting audio tanpa mengenkode ulang video](https://www.reddit.com/r/VideoEditing/comments/v1n6tu/edit_audio_without_reencoding_video/)
- [Dokumentasi FFmpeg tentang penentu aliran dan salinan codec](https://ffmpeg.org/ffmpeg.html)
- [Panduan MDN tentang format wadah media](https://developer.mozilla.org/en-US/docs/Web/Media/Guides/Formats/Containers)

## Ganti Soundtrack Video Anda Secara Pribadi

Buka GrepCut, tambahkan video Anda, tambahkan audio pengganti Anda, dan ekspor MP4 tanpa mengunggah file Anda.

## Alat Terkait

- [Bisukan Video](https://grepcut.com/id/tools/mute-video) - hapus soundtrack sebelum menambahkan yang baru.
- [Pemangkas Video](https://grepcut.com/id/tools/video-trimmer) - pangkas klip sebelum mengganti audionya.
- [Bakar Subtitle SRT](https://grepcut.com/id/tools/burn-srt-subtitles-to-video) - bakar subtitle setelah soundtrack diganti.
