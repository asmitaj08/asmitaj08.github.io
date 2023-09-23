---
layout: page
title: Blogs & Projects
permalink: /blogs-projects/
---

* Some blogs that I wrote while working at Payatu - [Payatu-blog-asmita](https://payatu.com/author/asmita-jha/)

* Achieved root access on Google Pixel watch (HardPwn contest at Hardwear.io) - [xda-forum](https://forum.xda-developers.com/t/how-to-root-google-pixel-watch-using-magisk.4592737/), [HardwearIo](https://media.hardwear.io/hardpwn-usa-2023/)

    - 48 hour 

* IOSC2: Identification & analysis of Outdated Software Components and corresponding CVEs in IoT firmware - [Github link](https://github.com/asmitaj08/IOSC2)

    - Performed static analysis on 107 real-world firmware binaries to identify third-party software components and corresponding analysis.
    - Provided detailed analysis report answering following research questions : *RQ1*: What are the commonly found third-party software components in IoT devices' firmware? *RQ2*: How likely is it to find outdated software components in such firmware? *RQ3*: What are the corresponding existing vulnerabilities w.r.t those software components? 
    - I worked on firmware dataset collection, writing the automation scripts and performing the comprehensive analysis.

* Unveil OS-based IoT firmware - [Github link](https://github.com/asmitaj08/OS-based-firmware-unveil)

    -  Single platform to get static info about Linux based IoT firmware. It includes firmware extraction, extracted file traversal, and identifiction of software components and corresponding CVEs. 
    - I worked on creation of this single automated platform using Binwalk, Firmwalker, Cve-bin-tool in the backened. 

* Binary similarity project - [Github link](https://github.com/asmitaj08/BinarySimilarityProject)

    - Leverage machine learning algorithm to identify whether the given to binary functions are similar for not.
    - It helps to extract the information about the unknown target binary, hence identify the third-party software components present in the binary which also assists in performing security analysis of the target.
    - I worked on the back-end dataset generation, feature extraction from binaries cfgs (Control flow graphs), and feature vectorization to get embedding vector corresponding to each feature of respective functions. After this, I worked on applying these MLP, and CNN algorithms on these dataset.