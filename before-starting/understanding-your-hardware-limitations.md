---
title: Understanding Your Hardware Limitations
layout: default
parent: Before Starting
nav_order: 2
---

# Understanding Your Hardware Limitations
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

-----

## Summary

I think before we get started on anything, we need to address the elephant in the room. Being able to run VTube Studio and being able to run VTube Studio, a game, and stream at the same time are two very different things.

While you can technically stream on your phone, laptop, or potato PC, your computer specs will determine your ability to VTube in general and what you can stream. As games continue to require beefier hardware to run year after year, your computer's minimum requirements become more and more of a bottleneck for what your can feasibly stream.

This section will go over what I would consider the minimum requirements for streaming, how to find out if you meet these requirements, and what you can do if you don't meet these requirements.

{: .note}
While the remaining sections will be a bit technical, I will try my best to explain things as easily as possible so that people who aren't familiar with computers can understand.

-----

## What is the Minimum Computer Specs for VTubing/Streaming?

**The short answer** is that I would recommend **at least**:

| Component | Recommendation
| --------- | -------------- |
| CPU | A modernish-gen (10th gen or above) i5 or equivalent
| RAM | At least 16 GB of RAM
| GPU | A GTX 1060-equivalent

These specs are what I consider passable **if you already have them**, meaning if your computer meet or exceed these specs, you should be able to hit "Go Live" on a modern-ish game running at 1080p with medium graphics settings. **If your computer specs do not meet these, I would highly recommend investing in a better graphics card than this one.**

**The long answer** is that it depends based on what type of VTuber model you plan on using and what games you intend on streaming. It's important to note that your computer will need to **exceed** the minimum requirements of the games you intend on playing in order to account for VTubing and streaming software running as well.

-----

## How Do I Know if I Meet These Requirements?

![Speccy Interface](../assets/images/speccy-specs.jpg)

To find out what CPU, RAM, and GPU specs you have, I've found that something like [Speccy](https://www.ccleaner.com/speccy) (pictured above) is one of the easiest ways to find out. If you don't feel comfortable downloading something, you can always Google how to do it for your operating system, as how to do so differs between Windows, Mac, and Linux.

| Component | Recommendation
| --------- | -------------- |
| CPU | **For Intel CPUs**, a 10th gen i5 will show as `i5-10XXX`, an 11th gen as `i5-11XXX`, etc. Generally, an i7 is better than an i5 an an i9 is better than an i7. <br/> **For AMD CPUs**, you can compare benchmark scores by [searching for your CPU](https://www.cpubenchmark.net/cpu_list.php) and seeing if their benchmark scores meet or exceed the recommended CPU ([Intel Core i5-10400](https://www.cpubenchmark.net/cpu.php?cpu=Intel+Core+i5-10400+%40+2.90GHz&id=3737)).
| RAM | At least 16 GB of RAM
| GPU | You can compare benchmark scores by [searching for your GPU](https://www.videocardbenchmark.net/gpu_list.php) and seeing if their benchmark scores meet or exceed the recommended GPU ([GTX 1060](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+GTX+1060&id=3548)).

<div class="code-example bg-grey-lt-000" markdown="1">

### Example Comparison

{: .note }
It's important to take everything with a grain of salt. You won't really know if you can run something until you try it out yourself but you can at least rule something in or out if your benchmarking scores are vastly inferior or superior to the minimum requirements of a game.

Let's use my current computer's specs and compare them to the [minimum requirements to run Dragon's Dogma 2](https://store.steampowered.com/app/2054970/Dragons_Dogma_2/), a very resource-intensive game that came out recently. Since both Intel and AMD CPUs are listed, as well as NVIDIA and AMD GPUs, we will compare our components with the respective brand listed (bolded).

| Components  | Dragon Dogma 2's Minimum Requirements | My Computer Specs | Status |
| ----------- | ------------------------------------- | ----------------- | ------ |
| CPU         | [Intel Core i5 10600](https://www.cpubenchmark.net/cpu.php?cpu=Intel+Core+i5-10600+%40+3.30GHz&id=3750) / [AMD Ryzen 5 3600](https://www.cpubenchmark.net/cpu.php?cpu=AMD+Ryzen+5+3600&id=3481) <br/> Avg. CPU Mark: 13675 / **17767** | [AMD Ryzen 5 3600X](https://www.cpubenchmark.net/cpu.php?cpu=AMD+Ryzen+5+3600X&id=3494) <br/> Avg. CPU Mark: **18216** | <span class="text-green-000">**PASS**</span> |
| RAM         | **16** GB | **64** GB | <span class="text-green-000">**PASS**</span> |
| GPU         | [NVIDIA GeForce GTX 1070](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+GTX+1070&id=3521) / [AMD Radeon RX 5500 XT with 8GB VRAM](https://www.videocardbenchmark.net/gpu.php?gpu=Radeon+RX+5500+XT&id=4174) <br/> Avg. G3D Mark: **13510** / 9164 | [NVIDIA GeForce GTX 1660 SUPER](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+GTX+1660+SUPER&id=4159) <br/> Avg. G3D Mark: **12776** | <span class="text-red-000">**FAIL**</span> | 

Based on the above, **in theory**, I should expect frame drops or stuttering gameplay when running the game alone **before** accounting for VTubing and streaming software. I **might** be able to get it to run more smoothly and stream it if I reduced the resolution to 720p and turned down additional graphics settings like texture quality, shadow quality, and anti-aliasing.

</div>

-----

## Hololive Comparison
Thanks to some Redditors, we can take a look at how our minimum requirements compare to some of the computers used by the talents in Hololive (data from [2021](https://www.reddit.com/r/Hololive/comments/ko50fu/hololive_member_pc_specs_cpu_and_gpu/), [2023](https://www.reddit.com/r/Hololive/comments/113mf3n/nene_casual_pc_specs_flex/), and [2024 onwards](https://www.reddit.com/r/Hololive/comments/1gldusz/comment/lvtnu9j/), RAM is speculative):

| Component | Minimum | Median | Maximum |
| --------- | ------- | ------ | ------- |
| CPU | [Intel Core i5-10400](https://www.cpubenchmark.net/cpu.php?cpu=Intel+Core+i5-10400+%40+2.90GHz&id=3737) <br/> Avg. CPU Mark: 12130 <br/> Price: $75-150 | [Intel Core i9-9900K](https://www.cpubenchmark.net/cpu.php?cpu=Intel+Core+i9-9900K+%40+3.60GHz&id=3334) <br/> Avg. CPU Mark: 18311 <br/> Price: $250-400 | [Intel Core i9-13900KF](https://www.cpubenchmark.net/cpu.php?cpu=Intel+Core+i9-13900KF) <br/> Avg. CPU Mark: 58656 <br/> Price: $400-600
| RAM | 16 GB <br/> Price: $50-100 | 32 GB <br/> Price: $80-120 | 64 GB <br/> Price: $150-250
| GPU | [GTX 1060](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+GTX+1060&id=3548) <br/> Avg. G3D Mark: 10073 <br/> Price: $50-150 | [GTX 2080 Ti](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+RTX+2080+Ti&id=3991) <br/> Avg. G3D Mark: 21785 <br/> Price: $200-400 | [GTX 4080](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+RTX+4090&id=4606) <br/> Avg. G3D Mark: 38579 <br/> Price: $600-1600

-----

## I Have a Potato PC. What Can I Stream?

If you're on older hardware and/or have "integrated graphics" (meaning you don't have a dedicated graphics card), chances are your computer will struggle to be able to run a modern video game let alone stream it. If this is the case and you don't have the resources for an upgrade at the moment, there is nothing wrong with starting as a PNGTuber playing retro or indie games that require less resources.

You can check out the community below for games that might run on your hardware:
* [r/LowEndGaming](https://www.reddit.com/r/lowendgaming/) - "A community for anyone struggling to find something to play for that older system, or sharing or seeking tips for how to run that shiny new game on yesterday's hardware."

-----

## Additional Resources

If you can't make heads or tails out of any of this, you can check out the community below to help you decipher whether or not you can run a game:

* [r/CanIRunIt](https://www.reddit.com/r/CanIRunIt/) - "A community with the goal to help computer enthusiasts figure out if they can run certain video games or applications."

If you are looking for more information about upgrading or buying a new computer, this is covered in [a later section](https://vtubing.info/post-debut/hardware-upgrades.html).