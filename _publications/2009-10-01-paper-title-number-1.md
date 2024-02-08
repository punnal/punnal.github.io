---
title: "Panakos: Chasing the Tails for Multidimensional Data Streams"
collection: publications
permalink: /publication/Panakos
excerpt: 'Fuheng Zhao, Punnal Ismail Khan, Divyakant Agrawal, Amr El Abbadi, Arpit Gupta, and Zaoxing Liu'
date: 2023-02-01
venue: 'VLDB 23'
paperurl: 'https://doi.org/10.14778/3583140.3583147'
citation: 'Fuheng Zhao, Punnal Ismail Khan, Divyakant Agrawal, Amr El Abbadi, Arpit Gupta, and Zaoxing Liu. 2023. Panakos: Chasing the Tails for Multidimensional Data Streams. Proc. VLDB Endow. 16, 6 (February 2023), 1291–1304. '
---
Fuheng Zhao, Punnal Ismail Khan, Divyakant Agrawal, Amr El Abbad, Arpit Gupta, Zaoxing Liu

[Download paper here](https://zaoxing.github.io/papers/2023/VLDB23_Panakos.pdf)

System operators are often interested in extracting different feature streams from multi-dimensional data streams; and reporting their distributions at regular intervals, including the heavy hitters that contribute to the tail portion of the feature distribution. Satisfying these requirements to increase data rates with limited resources is challenging. This paper presents the design and implementation of Panakos that makes the best use of available resources to report a given feature's distribution accurately, its tail contributors, and other stream statistics (e.g., cardinality, entropy, etc.). Our key idea is to leverage the skewness inherent to most feature streams in the real world. We leverage this skewness by disentangling the feature stream into hot, warm, and cold items based on their feature values. We then use different data structures for tracking objects in each category. Panakos provides solid theoretical guarantees and achieves high performance for various tasks. We have implemented Panakos on both software and hardware and compared Panakos to other state-of-the-art sketches using synthetic and real-world datasets. The experimental results demonstrate that Panakos often achieves one order of magnitude better accuracy than the state-of-the-art solutions for a given memory budget.

