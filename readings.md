---
title: Reading List and Schedule
---

Most of the reading links are based on DOI.
You can find the papers in ACM DL, IEEE Explore, or on the Morgan Claypool website.
You will have to log into the [Campus VPN](https://www.library.ucdavis.edu/service/connect-from-off-campus/https://www.library.ucdavis.edu/service/connect-from-off-campus/) to access the papers.

Let us know on Teams if you can't find the paper or can't log into the VPN and we can upload a version of it on Teams for you.

**NOTE:** All chapter/section numbers are *inclusive*.
I.e., if it's Sections 4-4.2 you should read Sections 4, 4.1, 4.1.1, 4.1.2, and Section 4.2.

### Hint

You're encoraged to discuss the reading outside of class with your fellow classmates.
You are welcome to use Teams to discuss the paper and ask questions.
You may also find it useful to form "reading groups" to discuss the paper together.

## How lecture will work (20% of your grade!)

Before every lecture, you *must* read the required reading listed below.
You must submit 2 "test-like" questions based on the reading.
These questions will be graded on the following scale:

* 1 points: The question is off topic or has fundamental mistakes
* 2 points: The question only requires recalling facts from the reading
* 3 points: The question demonstrates a deep understanding of the reading and asks a research-like question that requires coalescing knowledge.

For the first 45 minutes to an hour of lecture Professor Akella and/or Lowe-Power will reinforce the reading.
We will only hit the highlights, fill in blanks which the reading misses, and answer questions you may have (i.e., if you don't do the reading you will miss important information!).

Then, we will randomly assign everyone to breakout rooms for 15-30 minutes to work in groups to answer *the questions you proposed*.
We will select 2-4 questions for each lecture which you will have to write 1-2 paragraph answers.
You will work together on a google doc within your group and then turn in the document at the end of the breakout session.

#### Example questions:

Let's say the reading was on cache coherence and memory consistency.

* 1 point: Explain why cache coherence only matters for out-of-order cores.
* 2 point: Give an example thread interleaving which is a valid sequentially consistent order where a load and a store are executed in a different order than program order.
* 3 point: Compare and contrast a snooping-based protocol and a broadcast-based directory protocol (Dir0B). In both cases, every request is "broadcast" to all caches, so when would you use one vs the other?

**You will be graded based on your answers** to these questions.
The breakout sessions answers and the questions you submit before class will make up 20% of your grade.

## Reading lists

* [Week 1: Introduction to High-performance Computer Architecture](#week-1-introduction-to-high-performance-computer-architecture)
* [Week 2: Cache coherence and memory consistency](#week-2-cache-coherence-and-memory-consistency)
* [Week 3: On-chip interconnection networks](#week-3-on-chip-interconnection-networks)
* [Week 4: Memory system](#week-4-memory-system)
* [Week 5: Virtual memory and Virtualization](#week-5-virtual-memory-and-virtualization)

## Week 1: Introduction to High-performance Computer Architecture

![Relevant XKCD](https://imgs.xkcd.com/comics/efficiency.png)

### Lecture 1 (3/30): Intro and technology

**Required reading**: Watch the [2019 Turing Lecture](https://youtu.be/3LVeEjsn8Ts) by Hennessy and Patterson. <https://youtu.be/3LVeEjsn8Ts>

### Lecture 2 (4/1): Case study of modern processors

**Required reading**: IEEE MICRO papers on [AMD's Zen2](https://ieeexplore.ieee.org/document/9000513) and [Intel's Skylake](https://ieeexplore.ieee.org/document/7924286).

* <https://ieeexplore.ieee.org/document/9000513>
* <https://ieeexplore.ieee.org/document/7924286>

**Optional/Reference**: [Wikichip's](https://en.wikichip.org/wiki/WikiChip) coverage of [Zen2](https://en.wikichip.org/wiki/amd/microarchitectures/zen_2) and [Skylake](https://en.wikichip.org/wiki/intel/microarchitectures/skylake_(client)).

## Week 2: Cache coherence and memory consistency

![Caches! How do they even work?]({{"/assets/images/caches.jpg" | relative_url}})

### Lecture 3 (4/6): Cache coherence (intro) and memory consistency

**Required reading**: [Synthesis Lecture: A Primer on Memory Consistency and Cache Coherence, Second Edition](https://www.morganclaypool.com/doi/abs/10.2200/S00962ED2V01Y201910CAC049)

* Chapter 1
* Chapter 2
* Chapter 3 (Skip 3.8-3.11)
* Sections 4.1, 4.2
* Sections 5.1, 5.2-5.2.2
* *Optional:* Sections 5.4 and 5.9

### Lecture 4 (4/8): Cache coherence implementation

**Required reading**: [Synthesis Lecture: A Primer on Memory Consistency and Cache Coherence, Second Edition](https://www.morganclaypool.com/doi/abs/10.2200/S00962ED2V01Y201910CAC049)

* Chapter 6
* Sections 7-7.2.5
* Sections 8-8.2.6
* *Optional:* Chapter 11

## Week 3: On-chip interconnection networks

![Relevant XKCD](https://imgs.xkcd.com/comics/networking_problems.png)

### Lecture 5 (4/13):

**Required reading**: [Computer Architecture - A Quantitative Approach, 6th Edition,Appendix F Interconnection Networks]
({{ '/Appendix_F_online.pdf' | relative_url}})

* Section F.2 and Section F.3 (skim through these sections quickly)
* Section F.4
* Section F.5

### Lecture 6 (4/15):
**Required reading**: [Computer Architecture - A Quantitative Approach, 6th Edition,Appendix F Interconnection Networks] ( )

* Section F.6
* Section F.8

## Week 4: Memory system

![Relevant XKCD](https://imgs.xkcd.com/comics/kilobyte.png)

### Lecture 7 (4/20):

**Required reading**: [Synthesis Lecture: Innovations in the Memory System](https://www.morganclaypool.com/doi/abs/10.2200/S00933ED1V01Y201906CAC048)
* Chapter 1
* Chapter 2
* Chapter 4

### Lecture 8 (4/22):
**Required reading**: [Synthesis Lecture: Innovations in the Memory System](https://www.morganclaypool.com/doi/abs/10.2200/S00933ED1V01Y201906CAC048)
* Chapter 5
* Chapter 6
 
**Required reading**:

## Week 5: Virtual memory and Virtualization

![I hear you like virtual memory]({{"/assets/images/xzibit.jpg" | relative_url}})

### Lecture 9 (4/27): Virtual memory

**Required reading**: [Synthesis Lecture: Architectural and Operating System Support for Virtual Memory](https://www.morganclaypool.com/doi/abs/10.2200/S00795ED1V01Y201708CAC042)

* Chapter 1
* Chapter 2
* Chapter 3
* Sections 4.2-4.4
* Sections 6-6.1

### Lecture 10 (4/29): Hardware support for virtualization

**Required reading**: [Synthesis Lecture: Hardware and Software Support for Virtualization](https://www.morganclaypool.com/doi/abs/10.2200/S00754ED1V01Y201701CAC038)

* Chapter 1
* Sections 2-2.2
* Sections 3.2, 3.3
* Chapter 4
* Chapter 5
