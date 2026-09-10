# Convert VOB to MP4 Free Online

Convert legacy DVD VOB video files to modern, universally playable MP4. Processes entirely in your browser without uploading to any server.

HTML: https://grepcut.com/en/converters/vob-to-mp4

## How to Convert VOB to MP4 in Your Browser

1. **Choose your VOB file**: Drop your .vob file into the converter area, or select it from your device with the file picker.
2. **Let FFmpeg.wasm transcode it locally**: GrepCut runs FFmpeg through WebAssembly in your browser, converting DVD-style MPEG-2 video and AC-3 audio into an MP4 with H.264 video and AAC audio.
3. **Download your MP4**: Save the finished MP4 and use it on your phone, browser, editor, cloud drive, or media library without uploading your original video to a server.

Your conversion runs with **FFmpeg.wasm** inside your browser. That keeps your file local, but long DVD chapters and multi-gigabyte VOB files can take time because your own device is doing the transcoding.

## Why Your VOB File May Need MP4

A VOB file usually comes from the `VIDEO_TS` folder on a DVD. It can hold MPEG-2 video, audio tracks, subtitles, menus, and navigation data, which made sense for DVD players but can be awkward when you just want a normal video file.

If your VOB came from a home DVD, a VHS transfer, or an old camcorder disc backup, MP4 is usually easier to open and share. Your phone, browser, editing app, and cloud preview tool are far more likely to handle H.264 video with AAC audio than a raw DVD VOB.

This converter is built for that practical job: turn your single VOB file into a web-friendly MP4 while keeping the process on your device.

If your DVD title is split across several VOB files, convert the main clip you actually need. DVD projects often divide one title into multiple numbered VOB files, so keep your originals until you have checked that the exported MP4 contains the full segment you expected.

## What Happens During VOB to MP4 Conversion

VOB to MP4 is usually a transcode, not just a rename. GrepCut reads the DVD-style streams inside the VOB, decodes them with FFmpeg.wasm, and writes a new MP4 using H.264 video and AAC audio.

That matters for compatibility. MP4 is a container, and the H.264 plus AAC combination is one of the safest choices when you want your video to play in modern browsers and on everyday devices.

It also means the output is not lossless. Your MP4 is designed to preserve visible quality for normal playback, but you should keep the original VOB if it is your only archive copy.

## VOB vs MP4: What Changes for Your File

| Aspect | VOB | MP4 |
| --- | --- | --- |
| Original use | DVD-Video playback and navigation | Modern playback, sharing, uploading, and editing |
| Typical video and audio | MPEG-2 video with AC-3 or other DVD audio | H.264 video with AAC audio in this converter |
| Browser support | Poor for direct playback in web pages | Broad support across modern browsers and devices |
| Menus and navigation | Can include DVD menus, chapters, and navigation data | Exports the video as a normal MP4, without DVD menus |
| File size expectation | Often large because DVD-era compression is less efficient | Often smaller after H.264 compression, depending on the source |

MP4 is the better everyday format when you want your video to open without DVD software.

## Private Browser Transcoding: What You Gain and What to Expect

### Advantages

- Your VOB file stays on your device with no server upload
- You can convert DVD footage without installing desktop software
- FFmpeg.wasm handles legacy DVD streams more reliably than browser playback alone
- Your MP4 is easier to preview, share, upload, and edit

### Disadvantages

- Large VOB files can take longer because your CPU performs the conversion
- The MP4 is not lossless, so your original VOB is still the archive copy
- DVD menus and navigation are discarded in the MP4 output
- Subtitle tracks from the DVD are not preserved by this simple converter flow
- Damaged or unusual VOB files may fail if the browser runs out of memory

## When a Browser Converter Is the Right Fit

Use GrepCut when you have a personal VOB file and want a private, no-upload MP4 quickly. It is especially useful for family video transfers, old DVD clips, school projects, business recordings, or anything you do not want to send to an online conversion server.

For a full DVD with multiple titles, multiple VOB parts, forced subtitles, or language tracks, keep the full DVD folder and check your output carefully. A simple VOB to MP4 converter is best for one selected video file, not for preserving every DVD feature.

Because the work runs in your browser, performance depends on your device, browser memory, and source duration. A short chapter can finish smoothly, while a long 1 GB VOB may need patience.

## VOB to MP4 Converter FAQ

### Can you convert a VOB file to MP4 without uploading it?

Yes. GrepCut runs the conversion in your browser with FFmpeg.wasm, so your VOB file stays on your device instead of being uploaded to a remote server.

### Will your VOB lose quality when converted to MP4?

The conversion is not lossless because the DVD video is transcoded to H.264 and the audio is converted to AAC. The goal is a practical MP4 that looks good for normal playback, but you should keep your original VOB if it is your master copy.

### Why is your VOB file split into VTS_01_1.VOB, VTS_01_2.VOB, and similar parts?

DVD-Video folders often split a title into multiple numbered VOB files. If your movie or home recording spans several files, keep the originals and check which part contains the section you need before converting.

### Can you keep DVD menus when converting VOB to MP4?

No. MP4 is a normal video container, not a DVD navigation format. Your exported MP4 contains the playable video and audio, while DVD menus and navigation data are discarded.

### Can you preserve subtitles from a VOB file?

This simple browser converter is focused on producing an MP4 with H.264 video and AAC audio. DVD subtitle tracks are not preserved in the output, so keep the original DVD files if subtitles are important.

### Why does browser VOB conversion take longer than a desktop app?

FFmpeg.wasm runs inside your browser and uses your device resources. That keeps the workflow private and installation-free, but it is usually slower than a native desktop encoder, especially for long DVD files.

### Can you play the MP4 on your phone after conversion?

Yes. The converter outputs MP4 with H.264 video and AAC audio, a broadly supported combination for phones, browsers, media libraries, and editing apps.

### What should you do if your VOB conversion fails?

Try a smaller VOB file first, close other heavy browser tabs, and make sure you have enough free memory. Very old, damaged, encrypted, or unusual DVD files may still fail in a browser-based converter.

## Sources & further reading

- [Reddit discussion about preserving home video VOB files](https://www.reddit.com/r/VideoEditing/comments/1beot72/vob_to_mp4_need_advice_on_converting_home_videos/)
- [Reddit discussion about self-hosting VOB home videos](https://www.reddit.com/r/selfhosted/comments/13i9l2o/a_media_player_that_reads_vob_files/)
- [VideoHelp forum discussion on lossless vs transcoded VOB to MP4](https://forum.videohelp.com/threads/401761-Conversion%28lossless%29-from-VOB-%28and-other-video-types%29-to-MP4)
- [Super User question about lossless VOB conversion with FFmpeg](https://superuser.com/questions/227772/lossless-vob-conversion-with-ffmpeg)
- [ffmpeg.wasm project page](https://ffmpegwasm.netlify.app/)
- [MDN guide to web media containers and MP4 compatibility](https://developer.mozilla.org/en-US/docs/Web/Media/Guides/Formats/Containers)

## Edit Your MP4 After Conversion

Need to trim the converted clip, remove dead time, combine scenes, or add subtitles after export? Open GrepCut and continue editing your video in the browser.

## Explore Other Converters

- [WebM to MP4](https://grepcut.com/en/converters/webm-to-mp4) - Convert WebM HTML5 videos to MP4
- [DAT to MP4](https://grepcut.com/en/converters/dat-to-mp4) - Convert legacy Video CD DAT files to MP4
