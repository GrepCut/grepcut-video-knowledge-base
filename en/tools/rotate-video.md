# Rotate Video Online

Turn sideways phone footage upright or flip your clip for social posts. Processed locally in your browser - no upload, no watermark.

HTML: https://grepcut.com/en/tools/rotate-video

## How to Rotate a Video in Your Browser

1. **Add your video**: Drop your MP4, MOV, WebM, MKV, or M4V into the tool, or click to browse. Your file stays on your device while the browser prepares the preview.
2. **Choose the angle**: Pick 90° clockwise, 180°, or 90° counter-clockwise. Use the preview to check that your phone clip is upright before you export.
3. **Select the export mode**: Use Social-ready when you want the rotation baked into the pixels, or Fast remux when you only need the MP4 rotation flag changed.
4. **Download your MP4**: Click Rotate to export your corrected video as MP4. You can also open the clip in GrepCut Studio if you need crop, resize, captions, or timeline edits.

Need more than rotation? Open your clip in [GrepCut Studio](/) and continue editing in the browser.

## Why Your Phone Video Looks Sideways

A phone video can look correct in your camera roll but sideways in another app because the file may store a rotation flag instead of storing upright pixels. When a player or uploader respects that flag, your clip looks fine. When it ignores the flag, your video appears rotated even though the recording itself is not broken.

GrepCut gives you two fixes for that problem. Social-ready mode physically rotates the frames and clears the rotation flag, which is the safer choice before you post. Fast remux keeps the original video stream and updates the rotation metadata, which is faster but depends on the next app reading the flag correctly.

### Use this when:

- **Your phone clip is sideways**: Turn portrait or landscape footage upright before you upload it.
- **Your video is upside down**: Rotate 180° when the camera orientation was wrong during recording.
- **Your app ignores rotation metadata**: Bake the rotation into the pixels so the output does not rely on a hidden flag.
- **You need a quick MP4 export**: Save a corrected MP4 without opening a desktop video editor.

If you are posting to Instagram, TikTok, YouTube, or another uploader that may process the file again, choose **Social-ready** for the most predictable result.

## Social-ready vs Fast Remux

| Need | Social-ready | Fast remux |
| --- | --- | --- |
| What changes | Rotates the actual video frames and clears the rotation flag | Keeps the original frames and updates the MP4 rotation metadata |
| Speed | Slower because the video is re-encoded to H.264 | Near-instant because the compressed video packets are copied |
| Quality | High-quality H.264 export, but it is still a re-encode | Identical to the source video stream |
| Best for social uploads | Best choice when the next app may ignore rotation metadata | Works only when the next app respects the rotation flag |
| Output | Upright pixels in an MP4 file | Same pixels with a corrected rotation instruction |

Both modes run locally in your browser. Your original video is not uploaded, and the export has no watermark.

## When You Should Re-encode Instead of Remux

Fast remux is useful when you want a quick local fix and you know the next player reads MP4 rotation metadata. It can be the right choice for previewing, archiving, or sending a file to an app that already handles rotation flags correctly.

Social-ready is better when the clip will be uploaded, compressed again, or opened across different devices. By writing upright pixels into the MP4, you remove the guesswork. Your export may take longer, but the file is easier for social platforms and basic players to display correctly.

### A simple rule:

If the video is for posting, choose **Social-ready**. If the video is for your own device and you want the fastest possible correction, try **Fast remux**.

## Rotate Video at a Glance

### Advantages

- Private processing with no server upload.
- 90°, 180°, and 270° rotation options.
- Social-ready MP4 export for predictable orientation.
- Fast remux option when you only need a metadata fix.
- Free export with no watermark.

### Disadvantages

- Social-ready mode re-encodes video, so export takes longer than remux.
- Fast remux depends on the next app honoring rotation metadata.
- Only right-angle rotation is supported, not arbitrary angles.
- Requires a modern browser with WebCodecs support.

> observed by some players and not by some others
>
> Stack Overflow discussion about MP4 rotation metadata

## Rotate Video - FAQ

### Can you rotate a video without uploading it?

Yes. GrepCut runs the rotation process in your browser, so your file stays on your device instead of being uploaded to a server.

### Why does your MP4 look sideways in one app but correct in another?

Your MP4 may contain rotation metadata. Some players read that instruction and rotate the video during playback, while other apps ignore it. Use **Social-ready** mode when you want the exported MP4 to contain upright pixels instead of relying on metadata.

### Should you use Social-ready or Fast remux?

Use **Social-ready** when you plan to post the clip online or send it to an app that may ignore rotation flags. Use **Fast remux** when you want the fastest export and the next player is likely to honor MP4 rotation metadata.

### Will rotating your video reduce quality?

Fast remux keeps the original video stream unchanged, so the video stream stays identical. Social-ready mode re-encodes to H.264 so the rotation is baked into the pixels, which is more reliable for posting but takes longer.

### What video formats can you rotate?

You can add MP4, MOV, WebM, MKV, M4V, and most common video formats. GrepCut exports the rotated result as MP4.

### Will your audio stay in sync after rotation?

Yes. Rotation does not change playback speed. Audio is copied losslessly when it is already AAC, or re-encoded to AAC for broad MP4 compatibility.

### Can you rotate by a custom angle like 12°?

No. This tool is built for right-angle fixes: 90° clockwise, 180°, and 90° counter-clockwise. For sideways phone footage, those are usually the corrections you need.

### Why does GrepCut need a modern browser?

Social-ready export depends on browser video processing features such as WebCodecs. If your browser does not support the required APIs, try an up-to-date Chromium-based browser.

## Sources & further reading

- [Reddit discussion about accidentally filming in portrait mode](https://www.reddit.com/r/VideoEditing/comments/xryq3n/i_accidentally_filmed_my_videos_in_portrait_mode/)
- [Reddit workflow question about rotating without re-encoding](https://www.reddit.com/r/VideoEditing/comments/uuw62f/automatically_rotate_video_without_actually/)
- [Super User explanation of iPhone video rotation metadata](https://superuser.com/questions/564233/iphone-recorded-videos-getting-rotated-on-windows-systems)
- [Stack Overflow discussion about MP4 rotation flags](https://stackoverflow.com/questions/69386275/mp4-and-rotation-remove-flags-but-set-rotation)
- [MDN guide to the WebCodecs API](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [W3C WebCodecs specification](https://www.w3.org/TR/webcodecs/)

## Done Rotating? Build the Full Edit

Open GrepCut Studio to crop, resize, add captions, add music, and finish your browser-based video edit.

## Related Tools

- [Crop Video](https://grepcut.com/en/tools/crop-video) - trim your frame to a region or aspect ratio.
- [Resize Video](https://grepcut.com/en/tools/resize-video) - scale your clip by percentage.
- [Video Trimmer](https://grepcut.com/en/tools/video-trimmer) - cut your clip before or after rotating.
