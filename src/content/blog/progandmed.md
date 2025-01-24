---
layout: ../../layouts/LayoutBlogPost.astro
title: "Video Analysis & OCR Project"
description: "Video Analysis & OCR Project"
pubDate: 2023-01-21
category: "intro"
headerImage: "/src/lib/media.png"
---
<br>

[<a href="https://github.com/noumik/DVR-Project" style="color: lightblue;" target="_blank">GitHub Link</a>](https://github.com/noumik/DVR-Project)

<br>

**Problem 1:** My DVR ran out of storage space, but I wanted to save all my recorded programs. However, the content on the DVR is encrypted and not transferrable.
<br><br>
**Solution 1:** I researched ways to break the HDMI encryption and transfer videos to an external hark drive. In breaking the HDMI encryption, there was a software route and hardware route, and I chose to take the hardware route after analyzing both solutions. I now had all the videos saved as MP4s on an external drive.
<br><br>
**Problem 2:** Many of the videos, such as movies and concerts, had subtitles that were useful. These were hardcoded in the video and could not be turned off.
<br><br>
**Solution 2:**

\- First, I transferred each program from the DVR twice (once with hardcoded subtitles, once without subtitles). However, keeping two copies of each program is very inefficient.

\- I wrote a [<a href="https://github.com/noumik/DVR-Project" style="color: lightblue;" target="_blank">Python program</a>](https://github.com/noumik/DVR-Project) to analyze the video and detect when subtitles were present on the screen. It output an SRT file with timestamps and extracted a frame at every subtitle.

\- I fed the frames into an open-source OCR software, which output the completed SRT file, with my timestamps and the correct text from the subtitle.
<br><br>
To store all this content, I created a media server using a Raspberry Pi running Linux OS. The content is now accessible from anywhere.

<br><br>