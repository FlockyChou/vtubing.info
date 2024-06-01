---
title: Understanding Your Hardware Limitations
layout: default
parent: Before Starting
nav_order: 1
---

# Understanding Your Hardware Limitations
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

-----

I think before we get started on anything, we need to address the elephant in the room. Your computer specs will determine your ability to VTube and stream in general. It's important to note that just because you can play a game without issues normally, your computer may not be able to handle running the same game, having VTubing software running, and streaming at the same time.

While this section can be a bit technical, I will try my best to explain things as easily as possible so that people who aren't familiar with computers can understand.

## What is the Minimum Computer Specs for VTubing/Streaming?
The longer answer, as always, is it depends based on what type of model you plan on using and what games you intend on streaming. Multiple factors, namely your CPU, RAM, and GPU, will determine whether or not certain games will run smoothly on your computer. Using a 3D model will put more strain on your computer than a Live2D model, which will put more strain on your computer than a PNGTuber.

The short answer is that I would recommend **at least**:
* **CPU:** A modernish-gen i5. I would say this should be anything named "i5-9XXX" or above.
* **RAM:** 16 GB of RAM
* **GPU:** A GTX 1060-equivalent

A computer that I've seen recommended at a price point that checks all these boxes is the [NZXT "Player: One"](https://nzxt.com/product/player-one) at $799 (before taxes). While this isn't an endoresement for this product or company, you can use this as a benchmark in computer specs and price when shopping for other pre-built computers.

## How Do I Check My Computer Specs?
While there are ways to tell what specs/hardware you have in your computer without opening anything up or downloading anything, the easiest way I've found to get all the information in one place is by downloading and using [Speccy (available on Windows and Mac)](https://www.ccleaner.com/speccy). 

![Speccy Interface](assets/images/speccy-specs.jpg)

If you don't feel comfortable downloading something, you can always Google how to do it for your operating system.

## How Do I Know if I Meet These Requirements?
While not the most robust, an easy way to determine what hardware is "better" us by using PassMark ratings. These are basically benchmark scores given to computer parts based on how well they perform doing certain tasks.

In order to find the PassMark rating for each of your components, simply search for the name of the CPU or GPU on their respective search pages ([CPU search](https://www.cpubenchmark.net/cpu_list.php), [GPU search](https://www.videocardbenchmark.net/gpu_list.php)) and see if there's any existing benchmark of it.

<div class="code-example bg-grey-lt-000" markdown="1">

### Example Comparison for Video Games

{: .note }
It's important to take everything with a grain of salt. You won't really know if you can run something until you try it out yourself but you can at least rule something in or out if your benchmarking scores are vastly inferior or superior to the minimum requirements of a game.

Let's use my current computer's specs and compare them to the [minimum requirements to run Dragon's Dogma 2](https://store.steampowered.com/app/2054970/Dragons_Dogma_2/), a very resource-intensive game that came out recently. Since both Intel and AMD CPUs are listed, as well as NVIDIA and AMD GPUs, we will compare our components with the respective brand listed (bolded).

| Components  | My Computer Specs | Dragon Dogma 2's Minimum Requirements | Status |
| ----------- | ----------------- | ------------------------------------- | ------ |
| CPU         | [AMD Ryzen 5 3600X](https://www.cpubenchmark.net/cpu.php?cpu=AMD+Ryzen+5+3600X&id=3494) <br/> Avg. CPU Mark: 18216| [Intel Core i5 10600](https://www.cpubenchmark.net/cpu.php?cpu=Intel+Core+i5-10600+%40+3.30GHz&id=3750) / [AMD Ryzen 5 3600](https://www.cpubenchmark.net/cpu.php?cpu=AMD+Ryzen+5+3600&id=3481) <br/> Avg. CPU Mark: 13675 / **17767** | PASS
| RAM         | 64 GB | 16 GB | PASS |
| GPU         | [NVIDIA GeForce GTX 1660 SUPER](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+GTX+1660+SUPER&id=4159) <br/> Avg. G3D Mark: 12776 | [NVIDIA GeForce GTX 1070](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+GTX+1070&id=3521) / [AMD Radeon RX 5500 XT with 8GB VRAM](https://www.videocardbenchmark.net/gpu.php?gpu=Radeon+RX+5500+XT&id=4174) <br/> Avg. G3D Mark: **13510** / 9164 | FAIL | 

According to Dragon Dogma 2's Steam page, the minimum requirements are for "1080p/30fps". Keeping the above advice in mind, this means that in theory, I should expect frame drops or stuttering gameplay. I may be able to get it to run more smoothly if I reduced the resolution to 720p and turned down my graphics settings like texture quality, shadow quality, and anti-aliasing.

-----

### Additional Resources
If you can't make heads or tails out of any of this, there are also communities that may be able to help you decipher it:
* [r/CanIRunIt](https://www.reddit.com/r/CanIRunIt/) - "A community with the goal to help computer enthusiasts figure out if they can run certain video games or applications."
* [r/LowEndGaming](https://www.reddit.com/r/lowendgaming/) - "A community for anyone struggling to find something to play for that older system, or sharing or seeking tips for how to run that shiny new game on yesterday's hardware."

</div>

-----

## What Do I Do if I Don't Meet The Minimum Requirements?

If you don't meet the minimum requirements, you have 3 options:

1. Upgrade parts
2. Build or buy a new computer
3. PNGTUber + streaming older games

<div class="code-example bg-grey-lt-000" markdown="1">

### Upgrade Parts

If you don't feel comfortable doing this or an older laptop, you may want to look into buying a new computer. Laptops are nearly impossible to upgrade most times and the only components that are easily upgradable are often the hard drive and the RAM.

It is really hard to upgrade old desktops as well, depending on the age. For example, if your motherboard only supports DDR2 RAM, it can be both very hard and very expensive to upgrade. Additionally, newer processors will be incompatible with older motherboards as well, so there will almost always be some sort of bottleneck. This was the problem I faced with my 10 yr old desktop that is now relegated to being a small Minecraft server.

-----

### Build or Buy a Computer

If you are looking to build a PC, there are some Reddit communities of people helping others build a computer based on their needs:

* https://www.reddit.com/r/buildapc/
* https://www.reddit.com/r/buildmeapc/

If you are looking to buy a pre-built computer, there are some things to take into account:

<div class="code-example bg-white" markdown="1">

#### Desktop

| Pros  | Cons |
| ----- | ---- |
| Usually cheaper than a comparable laptop | Hidden cost of monitor, keyboard, mouse, webcam, and microphone. |
| Upgradable but only a pro if you intend on doing so. | |

#### Laptop

| Pros  | Cons |
| ----- | ---- |
| Have a monitor, keyboard, and touchpad built-in. Often times have webcam and microphone built-in, although you may want to still upgrade these. | Usually cost more than a comparable desktop |
| | Less upgradable (often only RAM and hard drive) |
| | A desktop CPU and GPU and not the same as a laptop CPU and GPU. Laptop hardware is often less beefy than their desktop counterparts, despite having the same or similar names.

</div>

-----

### PNGTuber + Streaming Older Games
If you are running on older hardware or a laptop with an integrated graphics chip, it may be best to start as a PNGTuber playing retro or indie games that require less resources.

</div>
