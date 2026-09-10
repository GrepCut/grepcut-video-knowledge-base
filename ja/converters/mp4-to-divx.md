# MP4をDivXに無料でオンライン変換

ブラウザ上でMP4動画をDivX（.divx）に無料変換。ローカルのFFmpeg.wasmで処理するためアップロード不要。ファイルはデバイス上に残ります。

HTML: https://grepcut.com/ja/converters/mp4-to-divx

## ブラウザでMP4をDivXに変換する手順

1. **MP4ファイルを選択**: GrepCutに.mp4ファイルをドロップするか、デバイスから選択します。
2. **ローカルでトランスコード**: GrepCutがブラウザ内でFFmpeg.wasmを実行し、DivX互換のMPEG-4ビデオストリームとMP3オーディオを作成します。
3. **DivXファイルをダウンロード**: 完成した.divxファイルを保存し、DVDプレーヤー、ホームシアターシステム、カーオーディオ、DivX認定デバイスでテストしてください。

変換中、ファイルはデバイス上に留まります。FFmpeg.wasmがブラウザ内で処理するため、アップロード待ちはありませんが、長いHDクリップはCPUがエンコードを行うため時間がかかることがあります。

## MP4をDivX出力する必要がある理由

古いDVDプレーヤーやUSBメディアユニットでは、スマートフォンで完璧に再生できるMP4でも再生できないことがあります。これらのデバイスはDivX、MPEG-4、AVI対応と表示されていても、実際には特定の古い動画形式を指しており、現代のMP4ファイルには対応していない場合があります。

GrepCutはこの不一致を解決するため、MP4をデコードし、MPEG-4ビデオとMP3オーディオのDivX互換結果を書き出します。これはファイル名の変更ではなく、実際のビデオとオーディオストリームを変更する完全なトランスコードです。

対象が最新のブラウザ、スマートフォン、SNSアップロードの場合は、通常MP4のままが最適です。MP4→DivXは、対象デバイスがDivX形式での再生を特に要求する場合に使用してください。

## 古いデバイス再生に必要なMP4とDivXの比較

| 形式 | 最適な用途 | GrepCutでの変更点 |
| --- | --- | --- |
| MP4 | 最新のスマートフォン、ブラウザ、テレビ、編集ソフト、アップロードサイト | ソースファイルをデコードし、DivX出力用に再エンコード |
| DivX互換.divx | 古いDivX認定DVDプレーヤー、ホームシアターシステム、USB再生デバイス | GrepCutがDIVX fourccのMPEG-4ビデオとMP3オーディオを生成します |
| AVI形式のDivX期待 | DivXやMPEG-4対応と表示されるがH.264 MP4を拒否するデバイス | 出力は最新のH.264 MP4ではなく、古いMPEG-4+MP3互換形式を目指します |

デバイスが厳しい場合は、まず短いクリップでテストしてください。一部のプレーヤーは解像度、ビットレート、fourcc、オーディオコーデック、ファイルサイズなどの詳細に敏感です。

## MP4からDivXへの変換で行われる処理

ブラウザはすべてのMP4を単純にDivX互換ファイルにラップすることはできません。一般的なMP4はH.264ビデオとAACオーディオを使用しますが、古いDivXプレーヤーはMPEG-4 Part 2形式のビデオとMP3またはAC3オーディオを期待することが多いです。

GrepCutはFFmpeg.wasmを使用してこの変換をローカルで実行します。MP4をデコードし、ビデオをDIVXタグ付きのMPEG-4に再エンコード、オーディオはMP3にエンコードして、より広いレガシーサポートを実現します。

これはトランスコードであるため、元のMP4はマスターとして保持してください。DivXファイルは古いハードウェア用の互換性コピーであり、長期保存用のアーカイブではありません。

## プライベートDivX変換：利点とトレードオフ

### Advantages

- 動画はローカルに留まり、サーバーにアップロードされない
- 出力は古いDivX認定ハードウェアやDVDプレーヤーのUSBワークフローに対応しています
- FFmpeg.wasmがブラウザでは通常エクスポートできないコーデックパスを処理
- 長時間のデスクトップ作業には元のFFmpegコマンドも利用可能

### Disadvantages

- トランスコードはリマックスより遅く、ローカルCPUを使用
- DivXは最新のスマートフォン、ブラウザ、共有プラットフォームには最適でない
- ビデオとオーディオを再エンコードするため、画質劣化の可能性
- 一部の古いプレーヤーはビットレート、解像度、プロファイルの制限で拒否する場合あり

## MP4→DivX変換FAQ

### アップロードせずにMP4をDivXに変換できますか？

はい。GrepCutはブラウザ内でFFmpeg.wasmを実行するため、MP4はクラウドコンバーターにアップロードされることなく、デバイス上でローカル処理されます。

### DivXファイルはスタンドアロンDVDプレーヤーで再生できますか？

可能です。特にプレーヤーがDivX認定されているか、USBやディスクでのDivX再生に対応している場合に適しています。ハードウェアの対応状況は異なるため、長い動画を変換する前に短いクリップでテストしてください。

### MP4→DivX変換はロスレスですか？

いいえ。GrepCutはMP4をMPEG-4ビデオとMP3オーディオにトランスコードします。最高品質のマスターが必要な場合は、元のMP4を保持してください。

### ブラウザベースのDivX変換がクラウドツールへのアップロードより遅いのはなぜですか？

FFmpeg.wasmはWebAssemblyを通じてブラウザ内で動作します。これによりプライバシーが保護されファイルはローカルに留まりますが、エンコードは自身のCPUが行うためです。

### MP4をDIVXにリネームするだけではだめですか？

リネームはファイル名を変えるだけです。H.264ビデオ、AACオーディオ、ビットレート、解像度、古いプレーヤーが必要とするDivX互換性の詳細は変更されません。

### この変換を最新のWeb動画に使用できますか？

使用は可能ですが、通常は避けるべきです。対象がウェブサイト、スマートフォン、SNSプラットフォーム、最新テレビの場合、H.264 MP4の方がDivXより互換性が高いです。

### 古いプレーヤーがDivXファイルを拒否した場合、どうすればよいですか？

デバイスのマニュアルで解像度、フレームレート、ビットレート、オーディオコーデック、ファイルサイズの制限を確認してください。古いDivXハードウェアは厳しい場合があるため、短いテストファイルで時間を節約できます。

## 出典と参考資料

- [Reddit r/ffmpeg：MP4をDivX/Xvid AVIに変換する議論](https://www.reddit.com/r/ffmpeg/comments/ry6elt/how_to_covert_mp4_to_divxxvidavi_with_minimumor/)
- [VideoHelpフォーラム：DivX DVDプレーヤーの再生問題](https://forum.videohelp.com/threads/290800-My-DivX-DVD-Player-can-t-play-my-avi-DivX-xvid-video)
- [FFmpeg-userメーリングリスト：厳しいDivXプレーヤーとFourCCについて](https://ffmpeg.org/pipermail/ffmpeg-user/2012-September/009422.html)
- [DivXサポート記事：DivXコンバーターの出力形式](https://support.divx.com/hc/en-us/articles/360002218833-What-output-formats-does-the-DivX-Converter-support)
- [ffmpeg.wasmプロジェクト概要](https://github.com/ffmpegwasm/ffmpeg.wasm)
- [MDN Web Docs：動画コーデックガイド](https://developer.mozilla.org/en-US/docs/Web/Media/Guides/Formats/Video_codecs)

## MP4をプライベートにDivX変換

GrepCutを開き、MP4をドロップしてブラウザ内でDivX互換コピーを作成。FFmpeg.wasmがトランスコードを処理する間、ファイルはデバイス上に留まります。

## 関連コンバーター

- [MP4→TS](https://grepcut.com/ja/converters/mp4-to-ts) - MP4をMPEG-TSにリマックスし、放送スタイルのワークフローに対応
- [AVI→MP4](https://grepcut.com/ja/converters/avi-to-mp4) - レガシーAVI映像を最新のMP4コンテナに移行
- [MP4→MP3](https://grepcut.com/ja/converters/mp4-to-mp3) - ブラウザ内でMP4動画から音声を抽出
