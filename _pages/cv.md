---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
*   **Ph.D. in Information Engineering**, The Chinese University of Hong Kong, 2025 - Present
    *   *Research Direction*: Wireless Network Transmission, AI for 5G
*   **M.S. in Cyber-Physical Systems**, Northeastern University, 2019 - 2021
    *   *GPA*: 3.494
*   **B.S. in Communication Engineering**, The North University of China, 2015 - 2019
    *   *GPA*: 3.39

## Technical Skills
*   **Programming Language**: Java, C, C++, Python
*   **Software**: Spring Boot, MySQL, Hadoop, Kafka, IoTDB, Redis
*   **Hardware**: STM32, Arduino, NVIDIA, Raspberry Pi, NodeMCU

## Research Experience
*   **Junior Research Assistant**
    *   *WiNS LAB, The Chinese University of Hong Kong*, Sept. 2022 - Jul. 2025
    *   Conducted in-depth research on wireless network transmission and developed a novel bottleneck detection tool called Wi-Fi Insider.
    *   Identified root causes of RTT fluctuations stemming from underlying network scanning and ARP resolution.
    *   Optimized TCP congestion control algorithms, achieving 50% reduction in average latency and 88% reduction in tail latency.

*   **Research Assistant**
    *   *Harbin Institute of Technology*, Jun. 2021 - Mar. 2022
    *   Reproduced Apache IoTDB with LSM-Tree structure in edge server and increased edge data write rate by 50%.
    *   Reduced write amplification using key-value separation technology, resulting in LSMs structure 9.5 times smaller than traditional LSM-Tree.
    *   Implemented full backup recovery strategy using shell scripts through system-scheduled tasks.

*   **Research Assistant**
    *   *Harbin Institute of Technology*, Sept. 2020 - May 2021 (Remote)
    *   Designed portable retinal detector using smartphones with self-designed auxiliary lens barrel.
    *   Implemented indirect ophthalmoscope principles to reduce mydriatic fluid influence.
    *   Developed GNN networks for glaucoma detection from captured retinal images.

*   *... 以此类推，添加其他研究经历 ...*

## Publications
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

*   **TeleAgent: Agent-Based Network Status Dialogue and Autonomous Recovery for Telepresence Human-Robot Interaction**
    *   Han Hu, **Qijia Wang**, He Chen.
    *   Accepted to the Workshop on Human-aware Embodied AI (HEAI), in conjunction with IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2025.

## Course Projects
*   **Data Analyst, Three Kingdoms Text Analysis Project** (Nov. 2019 - Dec. 2019)
    *   Implemented Word2vec to analyze character relationship networks in Romance of the Three Kingdoms.
    *   ...
*   **Data Analyst, NFL Data Analysis Project** (Oct. 2019 - Nov. 2019)
    *   Constructed Bayesian Model using Poisson distributions to analyze player performance metrics.
    *   ...

## Scholarship Honors & Rewards
*   **Scholarships**
    *   First-class Scholarship for Comprehensive Quality (2018-2019)
    *   ...
*   **Competitions**
    *   Third Prize, National College Students Intelligent Interconnection Competition, North China (Oct. 2018)
    *   ...

## Leadership
*   **Leader, Robots Association** (Spr. 2016 - Spr. 2017)
    *   Coordinated competition areas and managed competition logistics.
    *   ...
*   **Leader, Badminton Association** (Spr. 2016 - Spr. 2017)
    *   Served as competition judge and official.
    *   ...
