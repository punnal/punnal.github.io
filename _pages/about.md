---
permalink: /
title: "Hi, I am Punnal"
excerpt: "Hi, I am Punnal"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
------
I’m a grad student at the University of California, Santa Barbara, working under the supervision of Prof. [Arpit Gupta](https://sites.cs.ucsb.edu/~arpitgupta/) in the Systems and Networking Lab.

Currently, I am working on developing and improving a system called netMosaic. It is a data-collection platform that leverages existing public code repositories and programmable network infrastructures to simplify data collection for various learning problems under a variety of different network conditions. My focus is on the development of new closed-loop workflows that can (i) learn to constrain the typically vast search space of possible network conditions to only those conditions whose alterations would have the maximal impact on the quality of the collected network data, and (ii) reason about which conditions do or don’t improve model generalizability and produce the desired deployment performance (and why). We also plan to leverage this pipeline for learning problems such as flow completion time, throughput prediction, and version fingerprinting (i.e., determining the version of identified services, such as MongoDB).


I also helped design and build a system called [Panakos](https://doi.org/10.14778/3583140.3583147) that leveraged the skewness inherent to most feature streams in the real world(i.e Network traffic). Specifically, we disentangled a feature stream into cold, warm, and hot items based on their feature values(i.e flow size) and use a combination of the bitmap, Count-Min, and SpaceSaving data structures to track them. The design is generalizable to count, sum, and average operators, and strikes a good balance between accuracy and memory overhead. This system was implemented on tofino network switch using p4 programming language. 

Previously during my undergraduate I worked on a project that involved finding and resolving inconsistencies in the Linux Audit System to improve the reliability of provenance graphs generated through its output logs. Moreover, I also worked on finding data leakages of potentially identifiable information in online job portals.

Interests
------
My Interestes are in in the intersection of Network, Systems and Machine learning.

Selected Publications
------
1. [Panakos: Chasing the Tails for Multidimensional Data Streams](https://doi.org/10.14778/3583140.3583147) <br />
    Fuheng Zhao, Punnal Ismail Khan, Divyakant Agrawal, Amr El Abbadi, Arpit Gupta, and Zaoxing Liu.  <br />
    Proceedings of the VLDB 23  <br />
    https://doi.org/10.14778/3583140.3583147  <br />

