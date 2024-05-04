---
title: Setting up OBS Studio
layout: default
parent: Pre-Debut
nav_order: 2
---

# Setting up OBS Studio
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

-----

## OBS Studio Streaming Settings

{% include youtube.html id='muwqdMQptKo' %}

If you're confused on what settings to use for OBS Studio, I would recommend taking a look at the video above for recommended settings for FHD (Full HD) 1080p 30/60 FPS streaming. You can follow along with the video for most of the settings; however, you need to pay special attention to the segment around [the 04:45 mark](https://www.youtube.com/watch?v=muwqdMQptKo&t=285s):

* **For 30 FPS streams** - min 3,000 Kbps, max 6,000 Kbps
* **For 60 FPS streams** - min 4,500 Kbps, max 9,000 Kbps

**You should have 50% MORE upload speed than your bitrate setting.** For example, if you are doing 6,000 Kbps, you should have 6,000 Kbps + 3,000 Kbps (50% of 6,000) = 9,000 Kbps upload.

### Finding a Bitrate That Works for You

To find a bitrate that works for you, we need to find your upload speed first.

To check your upload speed, go to a website like [Speedtest](https://www.speedtest.net/). I would recommend changing the results from the default Mbps to Kbps in order to match the number on OBS.

1. First, click on the ["Settings" link](https://www.speedtest.net/settings) at the top middle of the page above "GO".
2. Then, on the next page, change the "Speed" setting to "Kbps".
3. Finally, press "GO" and wait for the test to finish.
4. The final number under "Upload Kbps" should be **at least double** your target bitrate listed above.

**Please note that even if your internet can handle streaming at 9,000 Kbps, your computer might not be able to and vice versa.**

### Test Streaming

{% include youtube.html id='UTEIyQITubM' %}

I would recommend experimenting with whether or not your computer can handle 60 FPS streaming with some test streams/recordings. You can test this if streaming on Twitch by following the video above. Unfortunately, there does not seem to be an equivalent for YouTube.
