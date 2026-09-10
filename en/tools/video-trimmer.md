# Free Online Video Trimmer

Cut a video down to the part you need in under 2 seconds. Using lossless keyframe-aligned stream copy, everything happens locally in your browser with no upload and no quality loss.

HTML: https://grepcut.com/en/tools/video-trimmer

## How to Trim a Video in Your Browser

1. **Add your video**: Drop your file onto the trimmer or click to browse. Your video loads locally into the preview.
2. **Choose the part you want**: Drag the start and end handles, then preview the range before you export.
3. **Export your cut**: Create a trimmed MP4 using keyframe-aligned stream copy, or continue editing in GrepCut Studio.

Need several cuts, captions, music, or a middle section removed? Open the clip in [GrepCut Studio](/).

## Why Your Video Exports So Quickly

When you only need to cut the beginning or end of a clip, uploading the whole file to a server can feel wasteful. GrepCut keeps your file on your device and trims it directly in your browser.

The trimmer uses WebCodecs and MediaBunny to read the media file, copy the already-encoded video and audio packets, and remux them into a fresh MP4. Because your browser does not need to decode and re-encode every frame, the export usually finishes in seconds.

### You get a fast cut because GrepCut avoids the slowest part of editing:

- **No full transcode**: The selected range is copied from the source stream instead of being re-encoded from scratch.
- **No upload queue**: Your file stays local, so you do not wait for a server upload before trimming starts.
- **No quality generation loss**: The stream copy path preserves the original encoded media in the exported range.

## What Keyframe-Aligned Cutting Means for You

A compressed video is not just a stack of complete pictures. Most frames depend on nearby frames, and keyframes are the safe points where playback can start cleanly.

That is why a lossless stream-copy trimmer may snap your cut to the nearest usable keyframe instead of cutting on any arbitrary frame. You get a fast, standard-compliant MP4, but the exported start or end can be slightly earlier or later than the handle position.

If you need frame-exact trimming, visual effects, transitions, or a cut inside the middle of a clip, use the full editor instead of the one-range trimmer.

## Browser Trimmer vs Traditional Online Trimmer

| What you need | GrepCut Video Trimmer | Typical server trimmer |
| --- | --- | --- |
| Privacy | Your video stays on your device | Your video is uploaded before processing |
| Speed | Fast stream copy for one continuous range | Upload plus server processing time |
| Quality | Preserves source quality for the copied range | May re-encode and add generation loss |
| Cut precision | Aligned to safe video keyframes | Can be frame-exact if the server re-encodes |
| Best use | Quickly remove the start or end of a clip | Heavier edits, format changes, or frame-exact exports |

Choose GrepCut when you want a private, fast, no-upload cut. Choose a full editor when your edit needs frame-exact timing or multiple separate ranges.

## Before You Trim

### Advantages

- Your file is not uploaded to a server.
- The preview updates while you adjust the range.
- Stream copy keeps the selected range at source quality.
- No watermark, no account, and no install.

### Disadvantages

- Cut points are aligned to nearby keyframes.
- Very large files depend on your device memory.
- This tool keeps one continuous range only.
- You need a browser with WebCodecs support.

> you can only cut a video on a keyframe (without encoding)
>
> Reddit r/ffmpeg discussion

## Video Trimmer FAQ

### Is your video uploaded when you trim it?

No. Your file is processed locally in your browser, so it does not leave your device.

### Will trimming lower your video quality?

No quality loss is introduced on the stream-copy path. GrepCut copies the encoded media from your selected range and remuxes it into a new MP4.

### Why is your cut not frame-exact?

Lossless video trimming has to respect keyframes. If your chosen start or end time falls between keyframes, GrepCut aligns the cut to a nearby safe point so the exported MP4 plays correctly.

### Can you cut out the middle of a video?

This trimmer keeps one continuous range. If you need to remove a middle section or make several cuts, open the clip in [GrepCut Studio](/).

### Can you trim a large video file?

Yes, but your browser and device memory still matter. Because the file is handled locally, very large videos can be limited by your computer rather than by an upload limit.

### Which browsers work best?

Use a browser with WebCodecs support, such as Chrome, Edge, or Opera. If your browser does not support the required media APIs, the trimmer may not run.

### What file do you get after trimming?

You export an MP4 containing the selected continuous range. The goal is a broadly playable file without uploading or transcoding your whole video.

## Sources & further reading

- [Reddit discussion on cutting video without re-encoding on keyframes](https://www.reddit.com/r/ffmpeg/comments/10tj7nu/can_you_only_cut_videos_without_reencoding_on/)
- [Reddit discussion about trimming video without re-encoding](https://www.reddit.com/r/ffmpeg/comments/1qag2ug/trimming_video_without_reencoding/)
- [Super User discussion on cutting video with no or minimal re-encoding](https://superuser.com/questions/1850814/how-to-cut-a-video-with-ffmpeg-with-no-or-minimal-re-encoding)
- [Super User discussion on fast video cutting and stream copy](https://superuser.com/questions/1643484/fast-and-relatively-accurate-cutting-from-a-video)
- [MDN WebCodecs API overview](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [MediaBunny browser media toolkit](https://mediabunny.dev/)

## Trim Your Clip, Then Keep Editing

Use the trimmer for a private, fast cut. When your clip needs captions, music, layout changes, or a full timeline, open it in GrepCut Studio and keep building in the browser.

## Related Tools

- [Crop Video](https://grepcut.com/en/tools/crop-video) - reframe your clip to a region or aspect ratio.
- [Resize Video](https://grepcut.com/en/tools/resize-video) - scale trimmed clips to a new resolution or aspect ratio.
- [Mute Video](https://grepcut.com/en/tools/mute-video) - remove the audio track from your clip.
