# Normalisasi Keras Audio Online

Ukur kenyaringan terintegrasi dan normalisasi trek Anda ke -14, -16, atau -23 LUFS. Berjalan sepenuhnya di browser Anda tanpa unggahan, tanpa akun.

HTML: https://grepcut.com/id/tools/audio-normalizer

## Cara Normalisasi Kenyaringan Audio Online

1. **Unggah audio Anda**: Letakkan file MP3, WAV, M4A, atau OGG ke dalam kartu unggah.
2. **Pilih target LUFS Anda**: Pilih Streaming pada -14 LUFS, Podcast pada -16 LUFS, atau Siaran pada -23 LUFS.
3. **Normalisasi dan ekspor WAV**: Klik Normalisasi untuk mengukur kenyaringan, menerapkan penguatan aman dengan pembatas puncak, dan unduh salinan WAV.

File Anda diproses secara lokal di peramban Anda. Tidak ada yang diunggah ke GrepCut.

## Mengapa Audio Anda Membutuhkan LUFS, Bukan Sekadar Normalisasi Puncak

Jika klip Anda memuncak mendekati 0 dB tetapi masih terdengar pelan dibandingkan audio lain, normalisasi puncak tidak akan menyelesaikan masalah sebenarnya. Puncak hanya menunjukkan sampel paling keras, sementara LUFS memperkirakan seberapa keras trek Anda terasa dari waktu ke waktu.

GrepCut mengukur kenyaringan terintegrasi dengan pembobotan-K, kemudian menerapkan penguatan menuju target yang dipilih sambil menghormati batas puncak -1 dBTP. Ini membantu audio Anda mendekati target kenyaringan streaming, podcast, atau siaran tanpa mendorong puncak ke kliping.

### Gunakan ini ketika Anda menginginkan kenyaringan yang konsisten sebelum berbagi, menerbitkan, atau mengedit lebih lanjut.

Jika file Anda sudah sangat keras dan tidak memiliki ruang kepala tersisa, batas puncak dapat mencegah alat mencapai target LUFS yang tepat. Dalam kasus itu, hasil yang lebih aman biasanya lebih baik daripada hasil yang terkliping.

## Target LUFS Mana yang Harus Anda Pilih?

| Target | Terbaik untuk | Fungsinya |
| --- | --- | --- |
| -14 LUFS | Pratinjau video streaming atau musik | Target kenyaringan umum ketika Anda ingin audio berada lebih dekat dengan tingkat pemutaran streaming utama. |
| -16 LUFS | Podcast dan klip bicara | Target praktis untuk konten berbasis suara di mana kejelasan dan konsistensi lebih penting daripada kenyaringan maksimal. |
| -23 LUFS | Pengiriman gaya siaran | Target lebih pelan yang selaras dengan alur kerja kenyaringan siaran EBU R128. |

Prasetel ini adalah titik awal. Platform pengiriman akhir Anda mungkin menerapkan normalisasi pemutaran sendiri setelah Anda menerbitkan.

## Apa yang Terjadi di Dalam Peramban Anda

Saat Anda menambahkan file, peramban Anda mendekode audio sehingga GrepCut dapat menganalisis bentuk gelombang. Alat ini mengukur kenyaringan di seluruh trek, menghitung penguatan yang diperlukan untuk target LUFS yang dipilih, dan membatasi hasilnya sehingga puncak tetap di bawah batas.

Karena pemrosesan bersifat lokal, audio Anda tetap di perangkat Anda. File yang sangat panjang dapat memakan waktu lebih lama karena peramban Anda harus mendekode dan memproses audio di memori.

- **Privasi bawaan**: Audio sumber Anda tidak diunggah ke server.
- **Sadar LUFS**: Alat ini menargetkan kenyaringan yang dirasakan, bukan hanya puncak sampel tertinggi.
- **Ekspor WAV**: Hasil normalisasi diunduh sebagai file WAV untuk diedit, diarsipkan, atau dikonversi.

## Kapan Normalisasi Kenyaringan Paling Membantu

Gunakan normalisasi LUFS ketika memo suara, segmen podcast, rekaman layar, atau klip musik Anda terdengar jauh lebih pelan atau lebih keras daripada bagian lain proyek Anda. Ini sangat berguna sebelum Anda menggabungkan beberapa klip ke dalam satu linimasa.

Untuk suara, Anda mungkin masih ingin membersihkan noise, menyetel EQ, mengompresi, atau mengedit jeda sebelum normalisasi. Normalisasi kenyaringan biasanya merupakan langkah penyesuaian level akhir, bukan pengganti untuk memperbaiki rekaman bising atau performa yang tidak merata.

## Kelebihan dan Keterbatasan Normalisasi Audio

### Advantages

- Anda dapat menormalisasi MP3, WAV, M4A, atau OGG tanpa mengunggah file Anda.
- Anda dapat memilih prasetel LUFS yang jelas untuk alur kerja streaming, podcast, atau siaran.
- Pembatas puncak mengurangi risiko kliping saat penguatan ditambahkan.

### Disadvantages

- Format ekspor adalah WAV, bukan MP3 atau M4A.
- File tanpa ruang kepala yang tersisa mungkin tidak mencapai target LUFS yang tepat tanpa kliping.
- Dukungan dekode peramban dapat bervariasi tergantung codec file dan perangkat.

> Normalisasi menyesuaikan setiap lagu ke level puncak yang sama, tetapi itu tidak sama dengan menyesuaikannya ke level kenyaringan yang sama.
>
> Reddit r/audioengineering

## FAQ Normalisasi Audio

### Bisakah Anda menormalisasi audio ke -14 LUFS secara online?

Ya. Pilih prasetel Streaming untuk menargetkan -14 LUFS, lalu ekspor hasil normalisasi sebagai WAV. Peramban Anda melakukan pemrosesan secara lokal, sehingga file Anda tidak diunggah.

### Haruskah Anda menggunakan -14 LUFS atau -16 LUFS?

Gunakan -14 LUFS ketika Anda menginginkan target gaya streaming yang umum. Gunakan -16 LUFS ketika Anda menyiapkan audio bicara seperti segmen podcast. Jika Anda tidak yakin, pilih prasetel yang sesuai dengan tempat audio Anda akan digunakan.

### Bisakah Anda menormalisasi audio untuk kenyaringan siaran?

Ya. Pilih prasetel Siaran untuk menargetkan -23 LUFS. Ini berguna ketika Anda menginginkan target kenyaringan gaya siaran yang lebih pelan daripada target streaming atau podcast.

### Apakah file audio Anda akan diunggah?

Tidak. GrepCut memproses audio Anda di peramban Anda. File sumber tetap di perangkat Anda, dan WAV yang dinormalisasi dihasilkan secara lokal.

### Apakah normalisasi kenyaringan akan mendistorsi audio Anda?

Alat ini menerapkan penguatan dengan batas puncak -1 dBTP untuk mengurangi risiko kliping. Jika sumber Anda sudah sangat keras, pembatas dapat mencegah target LUFS yang tepat sehingga ekspor tetap lebih aman.

### Mengapa file Anda masih terdengar berbeda setelah mencocokkan LUFS?

LUFS adalah panduan kenyaringan yang kuat, tetapi nada, bass, kompresi, noise latar, dan rentang dinamis masih mempengaruhi seberapa keras audio Anda terasa. Dua file dapat berbagi nilai LUFS dan masih terasa berbeda.

### Bisakah Anda mengekspor MP3 setelah normalisasi?

Alat ini mengekspor WAV. Jika Anda memerlukan format pengiriman lain, normalisasi terlebih dahulu, lalu konversi WAV dengan konverter terpisah.

## Sumber & bacaan lebih lanjut

- [Diskusi Reddit tentang normalisasi kenyaringan podcast](https://www.reddit.com/r/podcasts/comments/f1fbew/editing_question_do_you_normalize_and_if_so_how/)
- [Diskusi Reddit tentang normalisasi puncak versus kenyaringan yang dirasakan](https://www.reddit.com/r/audioengineering/comments/kctip9/normalising_the_volume_of_100_tracks_at_once/)
- [Panduan Spotify tentang normalisasi kenyaringan](https://support.spotify.com/us/artists/article/loudness-normalization/)
- [Rekomendasi kenyaringan dan puncak sebenarnya ITU-R BS.1770-5](https://www.itu.int/dms_pubrec/itu-r/rec/bs/R-REC-BS.1770-5-202311-I!!PDF-E.pdf)
- [Ikhtisar Web Audio API MDN](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
- [Referensi dekode audio peramban MDN decodeAudioData](https://developer.mozilla.org/en-US/docs/Web/API/BaseAudioContext/decodeAudioData)

## Normalisasi Audio Anda Secara Pribadi

Buka Normalisasi Audio, pilih target LUFS Anda, dan ekspor WAV bersih tanpa mengirim file Anda ke server.

## Alat Terkait

- [Penghapus Derau Audio](https://grepcut.com/id/tools/audio-noise-remover) - Bersihkan derau latar sebelum menormalkan kenyaringan.
- [Pembuat Nada Dering](https://grepcut.com/id/tools/ringtone-maker) - Potong klip pendek dan ekspor nada dering M4R atau MP3.
