# Putar Video Online

Putar video ponsel miring menjadi tegak atau balikkan klip untuk unggahan media sosial. Diproses secara lokal di browser Anda - tanpa unggah, tanpa watermark.

HTML: https://grepcut.com/id/tools/rotate-video

## Cara Memutar Video di Browser Anda

1. **Tambahkan video Anda**: Seret MP4, MOV, WebM, MKV, atau M4V Anda ke alat, atau klik untuk menjelajah. File Anda tetap di perangkat Anda saat browser menyiapkan pratinjau.
2. **Pilih sudut**: Pilih 90° searah jarum jam, 180°, atau 90° berlawanan arah jarum jam. Gunakan pratinjau untuk memeriksa apakah klip ponsel Anda sudah tegak sebelum mengekspor.
3. **Pilih mode ekspor**: Gunakan Siap-sosial jika Anda ingin rotasi tertanam dalam piksel, atau Remux cepat jika Anda hanya perlu mengubah bendera rotasi MP4.
4. **Unduh MP4 Anda**: Klik Putar untuk mengekspor video yang sudah diperbaiki sebagai MP4. Anda juga dapat membuka klip di GrepCut Studio jika perlu memotong, mengubah ukuran, menambahkan teks, atau mengedit timeline.

Butuh lebih dari sekadar rotasi? Buka klip Anda di [GrepCut Studio](/) dan lanjutkan mengedit di browser.

## Mengapa Video Ponsel Anda Terlihat Miring

Video ponsel bisa terlihat benar di galeri tetapi miring di aplikasi lain karena file mungkin menyimpan bendera rotasi alih-alih piksel yang tegak. Saat pemutar atau pengunggah menghormati bendera itu, klip Anda terlihat baik. Saat mengabaikannya, video Anda tampak berputar meskipun rekamannya tidak rusak.

GrepCut memberi Anda dua perbaikan untuk masalah itu. Mode Siap-sosial memutar bingkai secara fisik dan menghapus bendera rotasi, yang merupakan pilihan lebih aman sebelum Anda memposting. Remux cepat mempertahankan aliran video asli dan memperbarui metadata rotasi, yang lebih cepat tetapi tergantung pada aplikasi berikutnya yang membaca bendera dengan benar.

### Gunakan ini saat:

- **Klip ponsel Anda miring**: Putar rekaman potret atau lanskap menjadi tegak sebelum mengunggah.
- **Video Anda terbalik**: Putar 180° saat orientasi kamera salah selama perekaman.
- **Aplikasi Anda mengabaikan metadata rotasi**: Tanam rotasi ke dalam piksel sehingga output tidak bergantung pada bendera tersembunyi.
- **Anda perlu ekspor MP4 cepat**: Simpan MP4 yang sudah diperbaiki tanpa membuka editor video desktop.

Jika Anda memposting ke Instagram, TikTok, YouTube, atau pengunggah lain yang mungkin memproses ulang file, pilih **Siap-sosial** untuk hasil yang paling dapat diprediksi.

## Siap-sosial vs Remux Cepat

| Kebutuhan | Siap-sosial | Remux cepat |
| --- | --- | --- |
| Yang berubah | Memutar bingkai video sebenarnya dan menghapus bendera rotasi | Mempertahankan bingkai asli dan memperbarui metadata rotasi MP4 |
| Kecepatan | Lebih lambat karena video dienkode ulang ke H.264 | Hampir seketika karena paket video terkompresi disalin |
| Kualitas | Ekspor H.264 berkualitas tinggi, tetapi tetap merupakan enkode ulang | Identik dengan aliran video sumber |
| Terbaik untuk unggahan sosial | Pilihan terbaik saat aplikasi berikutnya mungkin mengabaikan metadata rotasi | Hanya berfungsi saat aplikasi berikutnya menghormati bendera rotasi |
| Output | Piksel tegak dalam file MP4 | Piksel sama dengan instruksi rotasi yang diperbaiki |

Kedua mode berjalan secara lokal di browser Anda. Video asli Anda tidak diunggah, dan ekspor tanpa watermark.

## Kapan Anda Harus Enkode Ulang daripada Remux

Remux cepat berguna saat Anda ingin perbaikan lokal cepat dan tahu pemutar berikutnya membaca metadata rotasi MP4. Ini bisa menjadi pilihan tepat untuk pratinjau, pengarsipan, atau mengirim file ke aplikasi yang sudah menangani bendera rotasi dengan benar.

Siap-sosial lebih baik saat klip akan diunggah, dikompresi lagi, atau dibuka di berbagai perangkat. Dengan menulis piksel tegak ke dalam MP4, Anda menghilangkan ketidakpastian. Ekspor Anda mungkin lebih lama, tetapi file lebih mudah ditampilkan dengan benar oleh platform sosial dan pemutar dasar.

### Aturan sederhana:

Jika video untuk diposting, pilih **Siap-sosial**. Jika video untuk perangkat Anda sendiri dan Anda menginginkan koreksi secepat mungkin, coba **Remux cepat**.

## Putar Video Sekilas

### Advantages

- Pemrosesan pribadi tanpa unggahan server.
- Opsi rotasi 90°, 180°, dan 270°.
- Ekspor MP4 Siap-sosial untuk orientasi yang dapat diprediksi.
- Opsi Remux cepat saat Anda hanya perlu perbaikan metadata.
- Ekspor gratis tanpa watermark.

### Disadvantages

- Mode Siap-sosial mengenkode ulang video, sehingga ekspor lebih lama dari remux.
- Remux cepat tergantung pada aplikasi berikutnya yang menghormati metadata rotasi.
- Hanya rotasi sudut siku-siku yang didukung, bukan sudut sembarang.
- Membutuhkan browser modern dengan dukungan WebCodecs.

> diamati oleh beberapa pemutar dan tidak oleh beberapa lainnya
>
> Diskusi Stack Overflow tentang metadata rotasi MP4

## Putar Video - FAQ

### Bisakah Anda memutar video tanpa mengunggahnya?

Ya. GrepCut menjalankan proses rotasi di browser Anda, sehingga file Anda tetap di perangkat Anda alih-alih diunggah ke server.

### Mengapa MP4 Anda terlihat miring di satu aplikasi tetapi benar di aplikasi lain?

MP4 Anda mungkin berisi metadata rotasi. Beberapa pemutar membaca instruksi itu dan memutar video saat diputar, sementara aplikasi lain mengabaikannya. Gunakan mode **Siap-sosial** jika Anda ingin MP4 yang diekspor berisi piksel tegak alih-alih bergantung pada metadata.

### Haruskah Anda menggunakan Siap-sosial atau Remux cepat?

Gunakan **Siap-sosial** saat Anda berencana memposting klip secara online atau mengirimnya ke aplikasi yang mungkin mengabaikan bendera rotasi. Gunakan **Remux cepat** saat Anda menginginkan ekspor tercepat dan pemutar berikutnya kemungkinan besar menghormati metadata rotasi MP4.

### Apakah memutar video akan mengurangi kualitas?

Remux cepat mempertahankan aliran video asli tidak berubah, sehingga aliran video tetap identik. Mode Siap-sosial mengenkode ulang ke H.264 sehingga rotasi tertanam dalam piksel, yang lebih andal untuk diposting tetapi memakan waktu lebih lama.

### Format video apa yang bisa diputar?

Anda dapat menambahkan MP4, MOV, WebM, MKV, M4V, dan sebagian besar format video umum. GrepCut mengekspor hasil yang diputar sebagai MP4.

### Apakah audio Anda akan tetap sinkron setelah rotasi?

Ya. Rotasi tidak mengubah kecepatan pemutaran. Audio disalin tanpa kehilangan jika sudah AAC, atau dienkode ulang ke AAC untuk kompatibilitas MP4 yang luas.

### Bisakah Anda memutar dengan sudut kustom seperti 12°?

Tidak. Alat ini dibuat untuk perbaikan sudut siku-siku: 90° searah jarum jam, 180°, dan 90° berlawanan arah jarum jam. Untuk rekaman ponsel yang miring, itu biasanya koreksi yang Anda butuhkan.

### Mengapa GrepCut membutuhkan browser modern?

Ekspor Siap-sosial bergantung pada fitur pemrosesan video browser seperti WebCodecs. Jika browser Anda tidak mendukung API yang diperlukan, coba browser berbasis Chromium yang terbaru.

## Sumber & bacaan lebih lanjut

- [Diskusi Reddit tentang tidak sengaja merekam dalam mode potret](https://www.reddit.com/r/VideoEditing/comments/xryq3n/i_accidentally_filmed_my_videos_in_portrait_mode/)
- [Pertanyaan alur kerja Reddit tentang memutar tanpa enkode ulang](https://www.reddit.com/r/VideoEditing/comments/uuw62f/automatically_rotate_video_without_actually/)
- [Penjelasan Super User tentang metadata rotasi video iPhone](https://superuser.com/questions/564233/iphone-recorded-videos-getting-rotated-on-windows-systems)
- [Diskusi Stack Overflow tentang bendera rotasi MP4](https://stackoverflow.com/questions/69386275/mp4-and-rotation-remove-flags-but-set-rotation)
- [Panduan MDN tentang API WebCodecs](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [Spesifikasi WebCodecs W3C](https://www.w3.org/TR/webcodecs/)

## Selesai Memutar? Bangun Edit Lengkap

Buka GrepCut Studio untuk memotong, mengubah ukuran, menambahkan teks, menambahkan musik, dan menyelesaikan edit video berbasis browser Anda.

## Alat Terkait

- [Potong Video](https://grepcut.com/id/tools/crop-video) - potong bingkai ke wilayah atau rasio aspek.
- [Ubah Ukuran Video](https://grepcut.com/id/tools/resize-video) - skalakan klip Anda berdasarkan persentase.
- [Pemangkas Video](https://grepcut.com/id/tools/video-trimmer) - potong klip Anda sebelum atau sesudah memutar.
