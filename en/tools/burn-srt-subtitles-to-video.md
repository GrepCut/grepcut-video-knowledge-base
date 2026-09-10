# Burn SRT Subtitles to Video Online

Drop your video and an SRT file - GrepCut burns SRT subtitles into every frame. Great for accessibility, social sharing, and silent-play platforms.

HTML: https://grepcut.com/en/tools/burn-srt-subtitles-to-video

## How to Burn SRT Subtitles into Your Video

1. **Add your video**: Drop an MP4, MOV, WebM, or MKV file. Your video stays on your device.
2. **Add your SRT file**: Drop or browse for your .srt subtitle file. GrepCut parses the timestamps and caption text locally in your browser.
3. **Preview the captions**: Adjust position, size, font, and line wrap before you export, so you can catch blocked faces, cropped text, or awkward line breaks.
4. **Burn and export MP4**: Click Burn SRT subtitles to hardcode the captions into the video frames and save a new MP4.

Don't have an SRT file yet? Open [GrepCut Studio](/) to generate subtitles from speech, edit the transcript, and export SRT.

## When Burning SRT Subtitles Makes Sense

Burned-in SRT subtitles become part of the picture. If your video is shared to a feed, played in an app with captions turned off, or downloaded by someone who may not keep the sidecar SRT file, the text still appears.

This is useful when you need predictable viewing on social clips, short demos, internal training videos, or translated exports. You are not relying on the player to detect a separate subtitle track or on the platform to keep your caption file attached.

The tradeoff is simple: once you burn the SRT subtitles into the video, you cannot turn them off or edit a typo inside the exported MP4. Fix the SRT first, preview it, then burn the final version.

### Use this tool when you need captions that always show:

- **Social media clips**: make your dialogue readable when the video starts muted in a feed.
- **Client review files**: send one MP4 without asking the viewer to load a separate .srt file.
- **Translated versions**: lock one language into the export when you are delivering a fixed version.
- **Player compatibility**: avoid cases where a video app ignores an external subtitle file or shows it in the wrong style.

If you also need switchable captions for accessibility or multiple languages, keep your original SRT file too. Burned subtitles are reliable visually, but they are not a replacement for a proper closed-caption track where the platform supports one.

## Burned SRT vs Soft Subtitle Track

| Need | Burned SRT subtitles | Soft subtitles |
| --- | --- | --- |
| Always visible | Yes. The text is part of every exported frame. | No. The player or viewer can turn captions off. |
| Edit after export | No. You need to fix the SRT and export again. | Yes. You can replace or edit the subtitle file. |
| Multiple languages | Best for one fixed language per export. | Better when the viewer should choose a language. |
| Platform support | Works anywhere the exported MP4 plays. | Depends on whether the app supports your caption file. |
| Accessibility controls | Limited. The viewer cannot resize, move, or restyle the captions. | Better. Supported players can expose caption settings. |

If your goal is a social-ready MP4 with captions that cannot disappear, burn the SRT. If your goal is selectable captions, upload the SRT or VTT track separately where the platform supports it.

## What GrepCut Does to Your SRT File

An SRT file is plain text with numbered cues, start and end timestamps, and the subtitle lines that should appear during each time range. GrepCut reads those cues locally and draws the matching text over your video during export.

The tool supports standard SubRip .srt captions with plain text. HTML tags inside the SRT, such as `<i>`, are stripped automatically so the burn stays predictable.

ASS and SSA subtitle styling is not supported here. If your source subtitles depend on per-cue colors, karaoke effects, outlines, or complex positioning, convert or simplify them to plain SRT before you use this tool.

### Before you export, check these details:

- **Timing**: play a few moments where dialogue starts and stops to confirm the SRT is synced.
- **Line length**: use the wrap preview so long captions do not run off the video.
- **Position**: move captions away from faces, product UI, lower thirds, or platform buttons.
- **Final wording**: fix typos before burning because the exported MP4 cannot be edited like a text file.

## Pros and Limits of Burning SRT in Your Browser

### Advantages

- Your video and SRT file stay on your device.
- You get a live preview before export.
- The exported MP4 has captions built into the video frames.
- You can choose position, size, font, and line wrap.
- There is no upload and no watermark.

### Disadvantages

- Burned subtitles cannot be switched off after export.
- A typo requires fixing the SRT and exporting again.
- Per-cue colors, ASS styling, and SSA effects are not supported.
- Rendering takes longer than trimming or muting because every frame must be decoded, composited, and re-encoded.
- You need a WebCodecs-capable browser such as Chrome, Edge, or Opera.

> If you do have a file that has hardsubs they can't be hidden.
>
> Super User discussion about hardcoded subtitles

## Burn SRT Subtitles to Video - FAQ

### Can you burn an SRT file into an MP4 online?

Yes. Drop your video and your .srt file into GrepCut, preview the subtitles, then export a new MP4 with the SRT captions hardcoded into the frames.

### Will your video or SRT file be uploaded?

No. Your video and subtitle file are read in your browser. Nothing is sent to a server, which is useful when your clip contains private meetings, drafts, client work, or unreleased content.

### Can you customize how the SRT subtitles look?

Yes. You can preview and adjust position, size, font, and line wrap before export. Per-line colors, ASS/SSA effects, and advanced subtitle styling are not supported.

### Why does burning subtitles take longer than adding a subtitle file?

Burning SRT subtitles changes the video itself. Your browser has to decode the video, draw the subtitle text on the right frames, and encode a new MP4.

### Can you remove burned subtitles later?

Not cleanly. Burned subtitles are part of the exported image, so you should keep your original video and SRT file in case you need to edit or export again.

### What if your captions are out of sync?

The timing comes from your SRT file. If captions appear too early or too late in the preview, fix the timestamps in the SRT or regenerate the subtitles in [GrepCut Studio](/) before burning.

### Do you need an SRT file first?

Yes. This tool burns an existing .srt file into your video. If you only have a video, open it in [GrepCut Studio](/) to transcribe speech, edit the transcript, and export SRT.

### Which browsers work best for burning SRT subtitles?

Use a WebCodecs-capable browser such as Chrome, Edge, or Opera. If your current browser cannot export, open the same files in a supported Chromium-based browser.

## Sources & further reading

- [Reddit discussion about hardcoded captions, social video, and accessibility tradeoffs](https://www.reddit.com/r/deaf/comments/1n6unqv/question_about_accessibility_for_video_platforms/)
- [Reddit discussion about subtitles for social videos](https://www.reddit.com/r/socialmedia/comments/1afv64z/does_it_matter_how_i_do_subtitles_for_social/)
- [Super User thread explaining hardcoded subtitles as unhideable video text](https://superuser.com/questions/1229037/hardcoded-subtitles-in-m4v-file-dont-show-up-in-youtube)
- [Super User thread about hardcoding SRT subtitles with video processing](https://superuser.com/questions/869248/hardcoding-subs-with-ffmpeg)
- [MDN WebCodecs API overview](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [YouTube Help on supported subtitle and closed caption files](https://support.google.com/youtube/answer/2734698)

## Need to Generate the SRT File First?

Open GrepCut Studio to transcribe your video with AI, edit the transcript, export SRT, or burn captions directly into your final clip.

## Related Tools

- [Add Audio to Video](https://grepcut.com/en/tools/add-audio-to-video) - replace the soundtrack before burning captions.
- [Mute Video](https://grepcut.com/en/tools/mute-video) - remove audio when captions carry the dialogue.
- [Video Trimmer](https://grepcut.com/en/tools/video-trimmer) - cut your clip before you hardcode the subtitles.
