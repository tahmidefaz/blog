---
layout:     post
title:      "Summer'17 Intern-Week 2"
subtitle:   "Things I did this week"
date:       2017-06-9 08:00:00
author:     "Tahmid Efaz"
header-img: "img/post-01-bg.jpg"
---

<h3>Using a computer cluster and introduction to GPU Computation and CUDA</h3>
<p>I spent most of the week trying to run codes on the copperhead computer cluster of UNCC as well as learning a little bit about GPU programming. I tried to run a program containing implementations of different algorithms of STKDE (space-time kernel density estimation) on CPU. Connecting to the SSH of copperhead proved harder than I thought it would be. I had difficulty connecting to the remote terminal of my virtual machine on the copperhead. My connection kept getting timed out. After debugging for a while, I was able to find the issue. The issue was with the wifi connection that I was using. When I used my phone as a wifi hotspot and tried to connect to the virtual machine using my phone's data, I was able to get in. Currently, I am using Codeanywhere.com to establish the connection to my virtual machine and it seems to be working fine. 
I also looked at basic programming on the GPU. I will be writing code on the Nvidia CUDA platform which is an industry standard platform for GPU computations. I learned that GPUs are built with parallelism in mind. Therefore, if I am to take advantage of the GPU computation, I need to write and execute code in parallel. Which means I may be developing parallel algorithms in the future.
Nvidia's CUDA platform uses C/C++ as it's primary language. Even though I am familiar with C++, it is not the language that I use every day. Therefore, I thought improving my C++ skills would be a great idea. Hence, I spent some time learning more about C++.
Everything seems to be going great so far. I cannot wait to see what challenges the REU throws at me in the future.
</p>
