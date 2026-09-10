# Pemangkas Video Online Gratis

Potong video hingga bagian yang Anda butuhkan dalam waktu kurang dari 2 detik. Menggunakan salinan stream lossless yang selaras dengan keyframe, semuanya terjadi secara lokal di browser Anda tanpa unggahan dan tanpa kehilangan kualitas.

HTML: https://grepcut.com/id/tools/video-trimmer

## Cara Memotong Video di Browser Anda

1. **Tambahkan video Anda**: Letakkan file Anda ke pemotong atau klik untuk menjelajah. Video Anda dimuat secara lokal ke pratinjau.
2. **Pilih bagian yang diinginkan**: Seret gagang awal dan akhir, lalu pratinjau rentang sebelum mengekspor.
3. **Ekspor potongan Anda**: Buat MP4 yang dipotong menggunakan salinan stream selaras keyframe, atau lanjutkan mengedit di GrepCut Studio.

Butuh beberapa potongan, teks, musik, atau menghapus bagian tengah? Buka klip di [GrepCut Studio](/).

## Mengapa Video Anda Diekspor dengan Sangat Cepat

Saat Anda hanya perlu memotong awal atau akhir klip, mengunggah seluruh file ke server terasa sia-sia. GrepCut menyimpan file Anda di perangkat dan memotongnya langsung di browser.

Pemotong menggunakan WebCodecs dan MediaBunny untuk membaca file media, menyalin paket video dan audio yang sudah dienkode, dan menggabungkannya kembali ke MP4 baru. Karena browser Anda tidak perlu mendekode dan mengenkode ulang setiap frame, ekspor biasanya selesai dalam hitungan detik.

### Anda mendapatkan potongan cepat karena GrepCut menghindari bagian paling lambat dari pengeditan:

- **Tanpa transkode penuh**: Rentang yang dipilih disalin dari stream sumber, bukan dienkode ulang dari awal.
- **Tanpa antrean unggah**: File Anda tetap lokal, sehingga Anda tidak menunggu unggahan server sebelum pemotongan dimulai.
- **Tanpa penurunan kualitas generasi**: Jalur salinan stream mempertahankan media terenkode asli dalam rentang yang diekspor.

## Apa Arti Pemotongan Selaras Keyframe bagi Anda

Video terkompresi bukan sekadar tumpukan gambar utuh. Sebagian besar frame bergantung pada frame di sekitarnya, dan keyframe adalah titik aman di mana pemutaran dapat dimulai dengan bersih.

Itulah mengapa pemotong salinan stream lossless dapat menjepret potongan Anda ke keyframe terdekat yang dapat digunakan, bukan memotong pada frame sembarang. Anda mendapatkan MP4 yang cepat dan sesuai standar, tetapi awal atau akhir yang diekspor bisa sedikit lebih awal atau lebih lambat dari posisi gagang.

Jika Anda membutuhkan pemotongan tepat frame, efek visual, transisi, atau potongan di tengah klip, gunakan editor penuh, bukan pemotong satu rentang.

## Pemotong Browser vs Pemotong Online Tradisional

| Yang Anda butuhkan | Pemotong Video GrepCut | Pemotong server biasa |
| --- | --- | --- |
| Privasi | Video Anda tetap di perangkat Anda | Video Anda diunggah sebelum diproses |
| Kecepatan | Salinan stream cepat untuk satu rentang kontinu | Waktu unggah ditambah pemrosesan server |
| Kualitas | Mempertahankan kualitas sumber untuk rentang yang disalin | Mungkin mengenkode ulang dan menambah penurunan generasi |
| Presisi potongan | Diselaraskan dengan keyframe video yang aman | Dapat tepat frame jika server mengenkode ulang |
| Penggunaan terbaik | Menghapus dengan cepat awal atau akhir klip | Edit yang lebih berat, perubahan format, atau ekspor tepat frame |

Pilih GrepCut saat Anda menginginkan potongan pribadi, cepat, tanpa unggah. Pilih editor penuh saat edit Anda membutuhkan waktu tepat frame atau beberapa rentang terpisah.

## Sebelum Anda Memotong

### Advantages

- File Anda tidak diunggah ke server.
- Pratinjau diperbarui saat Anda menyesuaikan rentang.
- Salinan stream menjaga rentang yang dipilih pada kualitas sumber.
- Tanpa watermark, tanpa akun, dan tanpa instalasi.

### Disadvantages

- Titik potong diselaraskan dengan keyframe terdekat.
- File yang sangat besar bergantung pada memori perangkat Anda.
- Alat ini hanya menjaga satu rentang kontinu.
- Anda memerlukan browser dengan dukungan WebCodecs.

> Anda hanya dapat memotong video pada keyframe (tanpa encoding)
>
> Diskusi Reddit r/ffmpeg

## FAQ Pemotong Video

### Apakah video Anda diunggah saat dipotong?

Tidak. File Anda diproses secara lokal di browser Anda, sehingga tidak meninggalkan perangkat Anda.

### Apakah pemotongan akan menurunkan kualitas video Anda?

Tidak ada penurunan kualitas yang terjadi pada jalur salinan stream. GrepCut menyalin media terenkode dari rentang yang Anda pilih dan menggabungkannya kembali ke MP4 baru.

### Mengapa potongan Anda tidak tepat frame?

Pemotongan video lossless harus menghormati keyframe. Jika waktu awal atau akhir yang Anda pilih berada di antara keyframe, GrepCut menyelaraskan potongan ke titik aman terdekat sehingga MP4 yang diekspor dapat diputar dengan benar.

### Bisakah Anda memotong bagian tengah video?

Pemotong ini hanya menjaga satu rentang kontinu. Jika Anda perlu menghapus bagian tengah atau membuat beberapa potongan, buka klip di [GrepCut Studio](/).

### Bisakah Anda memotong file video besar?

Ya, tetapi browser dan memori perangkat Anda tetap berpengaruh. Karena file ditangani secara lokal, video yang sangat besar dapat dibatasi oleh komputer Anda, bukan oleh batas unggah.

### Browser mana yang paling baik?

Gunakan browser dengan dukungan WebCodecs, seperti Chrome, Edge, atau Opera. Jika browser Anda tidak mendukung API media yang diperlukan, pemotong mungkin tidak berjalan.

### File apa yang Anda dapatkan setelah memotong?

Anda mengekspor MP4 yang berisi rentang kontinu yang dipilih. Tujuannya adalah file yang dapat diputar secara luas tanpa mengunggah atau mentranskode seluruh video Anda.

## Sumber & bacaan lebih lanjut

- [Diskusi Reddit tentang memotong video tanpa enkode ulang pada keyframe](https://www.reddit.com/r/ffmpeg/comments/10tj7nu/can_you_only_cut_videos_without_reencoding_on/)
- [Diskusi Reddit tentang memotong video tanpa enkode ulang](https://www.reddit.com/r/ffmpeg/comments/1qag2ug/trimming_video_without_reencoding/)
- [Diskusi Super User tentang memotong video tanpa atau dengan enkode ulang minimal](https://superuser.com/questions/1850814/how-to-cut-a-video-with-ffmpeg-with-no-or-minimal-re-encoding)
- [Diskusi Super User tentang pemotongan video cepat dan salinan stream](https://superuser.com/questions/1643484/fast-and-relatively-accurate-cutting-from-a-video)
- [Ikhtisar API WebCodecs MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [MediaBunny toolkit media browser](https://mediabunny.dev/)

## Potong Klip Anda, Lalu Lanjutkan Mengedit

Gunakan pemotong untuk potongan pribadi dan cepat. Saat klip Anda membutuhkan teks, musik, perubahan tata letak, atau garis waktu penuh, buka di GrepCut Studio dan terus bangun di browser.

## Alat Terkait

- [Potong Video](https://grepcut.com/id/tools/crop-video) - ubah bingkai klip Anda ke wilayah atau rasio aspek tertentu.
- [Ubah Ukuran Video](https://grepcut.com/id/tools/resize-video) - skalakan klip yang dipotong ke resolusi atau rasio aspek baru.
- [Bisukan Video](https://grepcut.com/id/tools/mute-video) - hapus trek audio dari klip Anda.
