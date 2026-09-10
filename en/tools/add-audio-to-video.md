# Add Audio to Video Online

Drop a video and an audio file - GrepCut replaces the soundtrack without re-encoding the picture. Nothing leaves your device.

HTML: https://grepcut.com/en/tools/add-audio-to-video

## How to Add Audio to a Video in Your Browser

1. **Choose your video**: Drop an MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP or MPEG file into GrepCut. Your video stays on your device.
2. **Choose your audio**: Add one MP3, WAV, AAC, M4A, FLAC, OGG or Opus file. This file becomes the replacement soundtrack.
3. **Mix and export**: Click Mix & export. GrepCut muxes the video stream and your new audio into one MP4.
4. **Download the result**: Save the MP4 with -with-audio added to the filename. The export stops at the shorter of your two inputs.

Need to layer background music with the original voice, adjust volume, fade audio, or sync a track by a few frames? Open [GrepCut Studio](/) instead.

## What This Audio Swap Actually Changes

If you already have a finished video and a separate voiceover, song, narration, or cleaned-up audio file, you do not need a full editor just to replace the soundtrack. GrepCut takes the video stream from your first file and the audio stream from your second file, then writes them into one MP4.

Your original soundtrack is not kept. The new audio file becomes the only audio track in the export. This is useful when your clip is silent, noisy, muted by a platform, or exported with the wrong audio take.

The video stream is copied when possible, so the picture is not re-compressed just because you changed the audio. If the video codec cannot be copied into MP4 cleanly, you may need a different workflow in the full editor.

The key idea is simple: you are replacing one track, not rebuilding the whole edit.

## Audio Replacement vs Full Editing

| What you need | Use this quick tool | Use GrepCut Studio |
| --- | --- | --- |
| Replace bad camera audio with a separate MP3 or WAV | Yes, this is the main workflow | Only if you also need edits |
| Add voiceover to a silent screen recording | Yes, if one audio file is enough | Use it for timing adjustments |
| Keep the original audio and add music on top | No, the original audio is replaced | Yes, use multiple tracks |
| Fade music in or out | No, quick replacement only | Yes, use volume controls |
| Fix audio that starts late or early | No precise sync controls here | Yes, line it up on the timeline |

Use the quick tool when your video and replacement audio already match well. Use the Studio when your audio needs editing, mixing, or timing work.

## Supported Video and Audio Inputs

Start with one video file. GrepCut is built around MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP and MPEG inputs, plus other readable video files when the browser and FFmpeg can parse them.

Then add one audio file. MP3, WAV, AAC, M4A, FLAC, OGG and Opus are the tested audio inputs. The output is always an MP4, which makes the result easier to share, play, and import into common apps.

### A few practical format notes:

- **MP4 and MOV**: good for phone clips, screen recordings, camera exports, and social media drafts.
- **WebM and MKV**: useful when your source came from a browser recorder, download, or open-source workflow.
- **WAV and FLAC**: good for clean voiceover or music masters before the final MP4 is created.
- **OGG and Opus**: useful for audio recorded by web apps, games, or open media tools.

If a file opens but the export fails, the usual culprit is not the file extension. It is the codec inside the container.

## Why Your Export Stops at the Shorter File

GrepCut trims the export to the shorter input so you do not get a long black tail, silent ending, or hidden extra audio after the picture ends. If your song is longer than the clip, the song is cut at the end of the video. If your voiceover is shorter than the clip, the exported video ends when the voiceover ends.

That behavior is intentional for a quick replacement tool. It keeps the result predictable without adding looping, padding, fades, or silence generation. For those timing choices, use the full timeline in GrepCut Studio.

## What You Get with a Browser-Based Audio Swap

### Advantages

- Your video and audio stay on your device with no upload.
- The picture is not re-encoded when stream copy is possible.
- You get an MP4 that is easier to play and share.
- You can replace noisy, muted, or wrong audio without opening a full timeline.
- You can use common video inputs and common audio formats.

### Disadvantages

- Only one replacement audio file is used.
- The original audio is removed instead of mixed underneath.
- Volume changes, fades, ducking, and exact sync need GrepCut Studio.
- Very large files depend on your device memory and browser limits.
- Some unusual codecs may need conversion before they fit inside MP4.

> rendering either makes the video 3 times as large or there's a significant loss of quality for the same file size
>
> Reddit r/davinciresolve

## Add Audio to Video FAQ

### Can you replace audio in an MP4 without rendering the video again?

Yes, when the video stream can be copied into the output MP4. GrepCut tries to copy the picture stream instead of re-encoding it, so changing the soundtrack does not automatically mean losing image quality.

### Will your video or audio be uploaded?

No. GrepCut runs the audio swap locally in your browser using FFmpeg compiled to WebAssembly. Your files stay on your device.

### Can you keep the original sound and add music on top?

Not in this quick tool. The replacement audio becomes the only soundtrack. Use [GrepCut Studio](/) if you need music, dialogue, and sound effects playing together.

### What happens if your audio is longer than your video?

The export stops at the end of the shorter file. If your audio runs longer than the video, it is trimmed. If your audio is shorter, the video ends with it.

### Can you sync audio that starts too early or too late?

This tool does not include offset controls. If your voiceover needs frame-level alignment, open the video in [GrepCut Studio](/) and move the audio on the timeline.

### What formats can you add audio to?

You can start with MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP or MPEG video. Your replacement audio can be MP3, WAV, AAC, M4A, FLAC, OGG or Opus. The downloaded file is MP4.

### Why does GrepCut export MP4 instead of keeping the original container?

MP4 is widely supported by browsers, phones, editors, and social apps. Keeping one output container also makes the quick tool simpler and more predictable.

### Will your file lose quality?

The picture should stay the same when stream copy works. The audio is taken from your replacement file and muxed into the output, so the result depends on the quality of the audio file you provide.

## Sources & further reading

- [Reddit discussion about replacing MP4 audio without rendering](https://www.reddit.com/r/davinciresolve/comments/1fnsfjb/how_do_i_replace_the_audio_of_an_mp4_without/)
- [Super User thread on replacing audio in video with FFmpeg](https://superuser.com/questions/1137612/ffmpeg-replace-audio-in-video)
- [Super User thread on audio and video length behavior](https://superuser.com/questions/801547/ffmpeg-add-audio-but-keep-video-length-the-same-not-shortest)
- [Reddit discussion about editing audio without re-encoding video](https://www.reddit.com/r/VideoEditing/comments/v1n6tu/edit_audio_without_reencoding_video/)
- [FFmpeg documentation on stream specifiers and codec copy](https://ffmpeg.org/ffmpeg.html)
- [MDN guide to media container formats](https://developer.mozilla.org/en-US/docs/Web/Media/Guides/Formats/Containers)

## Replace Your Video Soundtrack Privately

Open GrepCut, add your video, add your replacement audio, and export an MP4 without uploading your files.

## Related Tools

- [Mute Video](https://grepcut.com/en/tools/mute-video) - remove the soundtrack before adding a new one.
- [Video Trimmer](https://grepcut.com/en/tools/video-trimmer) - cut your clip before you replace the audio.
- [Burn SRT Subtitles](https://grepcut.com/en/tools/burn-srt-subtitles-to-video) - hardcode captions after the soundtrack is replaced.
