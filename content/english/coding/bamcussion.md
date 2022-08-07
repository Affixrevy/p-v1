+++
author = "Arthur Gao"
title = "National Stiltwalkers of Canada: Bamcussion"
date = "2021-06-23"
description = "Bamcussion"
tags = [
    "video",
]
+++

Bamcussion presented a unique challenge to me. I had the opportunity to meld my video expertise with my coding experience developing a live rendered background for a greenscreen production. One key issue facing greenscreen productions is that they requre static cameras as if cameras move, the background must also move appropriately. 

Therefore, the need and desire for a roaming camera posed a problem: "how does one move the background as *during* a live show appropriately with the camera?". The solution that I ultiamtely settled with took inspiration from both the StarWars Mandalorian and BBC Tokyo 2020 Olympics broadcast of making the background in Unreal Engine rendering it live on a separate computer and have a separate switcher chroma key the live actors into the environment we had created.

The project involved developing a background in Unreal Engine, Optimizing the background given our limited hardware capabilites, and connecting the Blackmagic Switcher API to the C# unreal engine project.

{{< youtube lY5ggr7QOR0 >}}