---
layout: page
title: My Blogs & Projects
permalink: /blogs-projects/
---

### Blogs at Payatu
During my tenure at Payatu, I authored several insightful blogs. Explore them to delve into various aspects of IoT security: [Payatu-blog-asmita](https://payatu.com/author/asmita-jha/).

### HardPwn Contest

Achieved root access on the Google Pixel watch during the challenging HardPwn contest orgainized by Google at Hardwear.io. Useful links: [xda-forum](https://forum.xda-developers.com/t/how-to-root-google-pixel-watch-using-magisk.4592737/), [HardwearIo](https://media.hardwear.io/hardpwn-usa-2023/).

- I participated in a rigorous 2-day HardPwn contest by Google.
- Performed security analysis on Google Chromecast and Pixel watch.
- I performed hardware analysis on Google Chromecast, including PCB tracing, identifying debug ports (found UART), soldering wires to the identified pins, and attempting to access Chromecast's root shell via the identified UART pins.
- On the Pixel watch, I collaborated with another participant to utilize a USB-C cradle for accessing Pixel watch debug ports, unlocking the bootloader, flashing a new image, and ultimately escalating to root privileges.


### IOSC2: IoT Firmware Security

Check out my project [IOSC2](https://github.com/asmitaj08/IOSC2), where I conducted static analysis on 107 real-world firmware binaries. The project aims to identify outdated third-party software components and corresponding CVEs in IoT firmware.

- Performed in-depth static analysis on a dataset of 107 real-world firmware binaries.
- Produced a comprehensive analysis report, answering key research questions:
  - *RQ1*: What are the commonly found third-party software components in IoT devices' firmware?
  - *RQ2*: How likely is it to find outdated software components in such firmware?
  - *RQ3*: What are the corresponding existing vulnerabilities related to those software components?
- Contributed to firmware dataset collection, automation script development, and comprehensive analysis.

### OS-Based Firmware Unveil

Explore my project [OS-based Firmware Unveil](https://github.com/asmitaj08/OS-based-firmware-unveil), a single platform for extracting valuable information from Linux-based IoT firmware.

- Developed an all-in-one automated platform for extracting static information from Linux-based IoT firmware.
- Features include firmware extraction, extracted file traversal, and identification of software components and corresponding CVEs.
- Contributed to the development of this platform using tools like Binwalk, Firmwalker, and Cve-bin-tool.

### Binary Similarity Project

Dive into my project [Binary Similarity Project](https://github.com/asmitaj08/BinarySimilarityProject), where we leveraged machine learning algorithms to identify similarities between binary functions.

- Implemented machine learning algorithms to determine the similarity between binary functions.
- The project aids in extracting information about unknown target binaries, identifying third-party software components, and facilitating security analysis.
- Contributions included dataset generation, feature extraction from binary control flow graphs (CFGs), feature vectorization, and applying MLP and CNN algorithms.

Feel free to explore these blogs and projects, and don't hesitate to reach out if you have any questions or would like to collaborate!


### Exploring Firmware Security: Initial Studies

In my early exploration of firmware security, I conducted the following studies:

- [System level security tetsing on embedded hardware and firmware: A study and analysis](https://github.com/asmitaj08/embedded_security_generic_studies/blob/main/study_embedded_security_testing.pdf)
     - This study involved a comprehensive survey of security issues in embedded systems, focusing on firmware and hardware attacks. It provides valuable insights into these security challenges, followed by an analysis and a glimpse into future research possibilities.
- [Identify Memory Corruption Bugs using Fuzzing](https://github.com/asmitaj08/embedded_security_generic_studies/blob/main/Fuzzing-to-identify-mem-corruption-bugs.pdf)
    - In this project, we delved into existing firmware analysis tools and experimented with fuzzing and symbolic execution techniques (AFL++ and SymCC). The goal was to uncover and understand memory corruption bugs, contributing to the field of firmware security.