---
name: Wrong rendering report
about: Report subtitles that look wrong (different from VSFilter)
title: ''
labels: compatibility
assignees: ''

---

Please replace the following text with the appropiate information.

**Compare to VSFilter**
Before reporting an issue, If possible, check what your file looks like in a video player that uses VSFilter to render subtitles (for example, MPC-HC). If it looks the same, even if it still feels wrong, this is probably intentional and not an issue with libass.

**Show screenshots**
If possible, add a screenshot of the file in libass (mpv, VLC, Kodi, MPlayer) that shows the wrong rendering, and a screenshot of the same file in a different renderer/video player (for example, MPC-HC) that shows the correct rendering.
**libass version in use?**
If you are using an old version of libass please retest with current git-master or the newest release if possible.

**System used?**
If VSFilter and libass screenshots were taken on different systems, give info for both
OS:  *(\*Linux, MacOS, Windows, …)*
CPU: *(32 or 64Bit AMD/Intel x86, ARM, POWER, …)*

**Did previous libass samples render the sample better?**
Or is this a recent change?

**Show the ASS code**
If possible, show an excerpt of the ASS script that looks wrong. Include the relevant Dialogue and Style lines. The excerpt should basically be a fully functional ASS file in itself. If you can’t make an excerpt, we can work with a full ASS file if you tell us the time at which the problem occurs.

If you see the problem with a particular video file that contains subtitles, try to upload a short cut from the video file that we can play to see the problem. You can use tools such as MKVToolNix to make a smaller cut from a large file.

**Include the font**
If a particular font is needed to see the wrong rendering, upload it as a file if you have permission to do so. If it is a free font available on the Web, you can instead give a link to it.

**Describe what’s wrong**
Tell us clearly and concisely what you think looks wrong. Even if you show a screenshot, it is not always obvious to another person what you think is the problem.

**Describe what it should look like**
If you don’t have screenshots to show this but you know what the correct picture should be, tell us about it.

**Log**
If you have logs regarding the issue please include them. Eg for [mpv](https://github.com/mpv-player/mpv), you can obtain a log by adding `--log-file=output.txt` when playing the affected file.

**Anything else**
Feel free to add anything else that may be useful.
