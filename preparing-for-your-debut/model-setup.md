---
title: Setting up Your Model
layout: default
parent: Preparing For Your Debut
nav_order: 3
---

# Setting up Your Model
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

-----

## PNGTuber Model

{% include youtube.html id='aKURqgsOlPA' %}

You can refer to the video guide above by Masuoh for a brief overview of 3 PNGTuber applications: Honk, PNGTuber Plus, and veadotube.

### veadotube mini

* [Download](https://olmewe.itch.io/veadotube-mini)
* [PNGTuber Setup](https://veado.tube/help/mini/building-avatar/)
* [Streaming Setup](https://veado.tube/help/mini/obs/)

### PNGTuber Plus

* [Download](https://kaiakairos.itch.io/pngtuber-plus)
* I have not tested this one yet

### OBS Plugins

{% include youtube.html id='-U4OuFxaCQU' %}

You can set up your PNGTuber directly in OBS using plugins.
You can watch the video tutorial above by Shindigs to see how, plus some really cool things you can do directly in OBS to level up your stream.

-----

## Live2D Model

### VTube Studio

* [Download](https://denchisoft.com/)
* [Face Tracking Setup](https://github.com/DenchiSoft/VTubeStudio/wiki/Getting-Started)
* [Streaming Setup](https://github.com/DenchiSoft/VTubeStudio/wiki/Recording-Streaming-with-OBS)

-----

## 3D Model

### VSeeFace

* [Download](https://www.vseeface.icu/)
* [Export a VRM file from VRoid Studio](https://vroid.pixiv.help/hc/en-us/articles/360014383713-How-to-create-a-VRM-file)
* [Using a VRoid Studio VRM file in VSeeFace](https://streamlabs.com/content-hub/post/how-to-set-up-a-3d-avatar-for-streaming)
* [Enable Spout Support](https://streamlabs.com/content-hub/post/vtuber-support-on-streamlabs-desktop)
* [Streaming Setup](https://www.vseeface.icu/spout)

I personally found that toggling on "Mirror motion" allows for easier testing since you will be able to see your model move in the same direction as you.

Additionally, the model tracking was a bit delayed/laggy for me on my older computer so I ended up playing with some settings to make it smoother:
* Under "Settings" > "General Settings"
* Scroll down to "Graphics settings".
* Look for "Anti-aliasing". I decreased this from "16x" to "2x".
* Look for "Cap frame rate". I decreased this from "60" to "30".