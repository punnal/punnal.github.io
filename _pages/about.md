---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a Ph.D. student at the University of California, Santa Barbara, working under the supervision of Prof. Arpit Gupta in the Systems and Networking Lab.

Currently, I am working on a system that generates live network traffic under different network conditions. The existing approaches include replaying pcaps or generating traffic using traffic generators that replicate some traffic features such as distribution. However they fail to capture complex application logic. To capture the application logic we use orchestrable code avaliable on online platforms like github. This type of network traffic data will help ML models solving network problems more generalizable.

I also worked on building a system called Panakos that leveraged the skewness inherent to most feature streams in the real world(i.e Network traffic). Specifically, we disentangled a feature stream into cold, warm, and hot items based on their feature values(i.e flow size) and use a combination of the bitmap, Count-Min, and SpaceSaving data structures to track them. The design is generalizable to count, sum, and average operators, and strikes a good balance between accuracy and memory overhead. This system was implemented on tofino network switch using p4 programming language. 

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

