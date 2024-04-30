---
title: Understanding Your Hardware Limitations
layout: default
parent: Pre-Model
nav_order: 3
---

# Understanding Your Hardware Limitations
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

-----

I think before we get started on anything, we need to address the elephant in the room. Your computer specs will determine your ability to VTube and what games you'll be able to stream. It's important to note that just because you can play a game without issues, your computer may not be able to handle running the same games, having VTubing software running, and streaming at the same time.

## How Do I Check What I Can Play?
While there are ways to tell what kind of hardware you have on your computer without downloading anything, the easiest way I've found to get all the information in one place is by downloading and using [Speccy (available on Windows and Mac)](https://www.ccleaner.com/speccy).

Multiple factors, namely your CPU, RAM, and GPU ("Graphics" in Speccy), will determine whether or not certain games will run smoothly on your computer. You can find out if you can play a game by looking at your hardware and comparing them to the game's minimum requirements, which are often listed on the game's buy page or on it's official site.

-----

## How Do I Compare Components?
> What is an i5? And what's the difference between an i5-2300 and i5-6400?

I typically use PassMark ratings to determine what hardware is better. Simply search for the name of the CPU or GPU on their respective search pages ([CPU search](https://www.cpubenchmark.net/cpu_list.php), [GPU search](https://www.videocardbenchmark.net/gpu_list.php)) and see if there's any existing benchmark of it.

Let's use my current computer as an example and compare them to the minimum requirements to run Dragon's Dogma 2, a very resource-intensive game that came out recently:

| Components  | My Computer Specs | Dragon Dogma 2's Minimum Requirements | Status |
| ----------- | ----------------- | ------------------------------------- | ------ |
| CPU         | [AMD Ryzen 5 3600X](https://www.cpubenchmark.net/cpu.php?cpu=AMD+Ryzen+5+3600X&id=3494) <br/> Avg. CPU Mark: 18216| [Intel Core i5 10600](https://www.cpubenchmark.net/cpu.php?cpu=Intel+Core+i5-10600+%40+3.30GHz&id=3750) / [AMD Ryzen 5 3600](https://www.cpubenchmark.net/cpu.php?cpu=AMD+Ryzen+5+3600&id=3481) <br/> Avg. CPU Mark: 13675 / **17767** | PASS
| RAM         | 64 GB | 16 GB | PASS |
| GPU         | [NVIDIA GeForce GTX 1660 SUPER](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+GTX+1660+SUPER&id=4159) <br/> Avg. G3D Mark: 12776 | [NVIDIA GeForce GTX 1070](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+GTX+1070&id=3521) / [AMD Radeon RX 5500 XT with 8GB VRAM](https://www.videocardbenchmark.net/gpu.php?gpu=Radeon+RX+5500+XT&id=4174) <br/> Avg. G3D Mark: **13510** / 9164 | FAIL | 

### What Does This Mean?
It's important to take everything with a grain of salt. You won't really know if you can run something until you try it out yourself but you can at least rule something in or out if your benchmarking scores are vastly inferior or superior to the minimum requirements of a game.

According to Dragon Dogma 2's Steam page, the minimum requirements are for "1080p/30fps". Keeping the above advice in mind, this means that in theory, I should expect frame drops or stuttering gameplay. I may be able to get it in a runnable state if I reduced the resolution to 720p and turned down my graphics settings like texture quality, shadow quality, and anti-aliasing.

### I Still Don't Get It
If you can't make heads or tails out of any of this, there are also communities that may be able to help you decipher it:
* [r/CanIRunIt](https://www.reddit.com/r/CanIRunIt/) - "A community with the goal to help computer enthusiasts figure out if they can run certain video games or applications."
* [r/LowEndGaming](https://www.reddit.com/r/lowendgaming/) - "A community for anyone struggling to find something to play for that older system, or sharing or seeking tips for how to run that shiny new game on yesterday's hardware."

#### What about "Can You RUN It"? (aka systemrequirementslab.com)
[People have found that this site is a bit unreliable.](https://www.reddit.com/r/lowendgaming/comments/4j6no4/how_reliable_is_can_you_run_it/)

-----

## A Note on Old Desktops and Laptops
If you are running on older hardware or a laptop with an integrated graphics chip, it may be best to start as a PNGTuber playing retro or indie games that require less resources.

Laptops are nearly impossible to upgrade most times. The only components that are easily upgradable are often the hard drive and the RAM.

It is really hard to upgrade old desktops as well, depending on the age. For example, if your motherboard only supports DDR3 RAM, it can be both very hard and very expensive to upgrade. Additionally, newer processors will be incompatible with older motherboards as well, so there will almost always be some sort of bottleneck. This was the problem I faced with my 10 yr old desktop that is now relegated to being a small Minecraft server.
