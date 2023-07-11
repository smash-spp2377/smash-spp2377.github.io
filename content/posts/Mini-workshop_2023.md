---
title: "Mini-workshop 2023"
date: 2023-06-12T12:16:16+01:00
draft: false
sidebar: false
pager: false
tags:
  - "Workshops"
---

Our group is planning the next mini-workshop with the topic **A Benchmark Suite for Data Placement in Operating Systems**. We all agree that a system can only grow if it is challenged with suitable, real-world benchmarking workloads. Hence, with this initiative, our group aims at creating a configurable benchmarking suite that is a Swiss army knife for challenging modern heterogeneous memory setups to validate each project’s specific goals and create a base of comparison between projects. For example, how much does the use of NVM in Project X contribute to performance improvements when compared to Project Y which focuses on safety and based on these results which actors might benefit from the former or the latter approach?

Of course, there is a variety of benchmarks already available with varying end goals and emulated workloads. We should leverage their capabilities and specific challenges that they set already and evaluate what a common benchmark should encompass especially regarding the diverse metrics of performance, energy usage, operation costs etc. The specific goal of this mini-workshop is, thus, to analyze the state of the art and afterward create our own configurable benchmark that we can use within the SPP, but especially publish it for external competitions and benchmarking purposes.

The agenda of this mini-workshop is rather special because it starts with a preparation phase before the in-person workshop. In the preparation phase, we ask you to create together with us a knowledge base of existing benchmarks. Afterward, we structure the material and distribute the presentations about benchmarks for the mini-workshop among the participants. After some presentation slots, we aim to get our hands dirty with conceptualizing or, at best, implementing the benchmark suite.

The workshop will take place from the 6th of July, 1pm until the 7th of July, 2pm. The location is Building 29 (Fakultät für Informatik) at Otto-von-Guericke University, Magdeburg in Room 301: [maps.google.com](https://goo.gl/maps/XV6PHpXRK3cHajpz5). You will find hotels nearby the university or the central station.

Please enter your name in the following poll ([link to the poll](https://terminplaner6.dfn.de/p/dc1b3eedabefefd6aa0c00610f40eefa-282462)) such that we have a final list of participants latest by the 23rd of June. The material for the Mini-Workshop can be found under the SPP’s Git. You can find the collected benchmarks at this [link](https://spp2377-git.uos.de/meetings/2023/mini-workshop-on-a-benchmark-suite-for-data-placement-in-operating-systems/-/wikis/list-of-benchmarks).

The benchmarks have also been distributed among the groups for presentation inside the wiki. Please prepare a 5-10 minutes presentation per benchmark. To already come to a common characterization of the benchmarks, please report on the following points for each benchmark:
- application domain
-	metrics (latency, throughput, energy consumption, …)
-	read/write/update ratio
-	access granularity/unit (key-value pairs, blocks, …)
-	access patterns (random reads, sequential writes, …  if identifiable)
-	data size (at best differentiation between working memory and persistent storage)
-	flexibility of workload characteristics (predefined query templates, selectivity, ...)

Finally, a rough schedule for the meeting:

**Thursday 6th** 
- 1pm 	Welcoming Words
- 1-5pm	Benchmark Presentations (10 mins each) & Consolidation (incl. Ad-Hoc Breaks)
  - After each 3-4 talks, we consolidate the characteristics of the benchmarks in an interactive phase
- 5-6pm	Buffer+Wrap-Up of the First Day
- 7pm	Get Together at Local Restaurant
  - https://qilin-md.de (Reserved for Michael Kuhn)

**Friday 7th**
- 9-10am	Conceptualizing a Common Benchmark
  - Identifying common interfaces for a set of benchmarks, mapping benchmarks with the requirements of the projects
- 10-12am	Hackathon (BYOD!) 
  - We plan to do first implementation tasks on-site
- 12-1pm	Discussion on Paper Ideas
  - Planning how to proceed (discussing option of a survey paper or a common benchmark paper)

---

We thank all the participants for attending the workshop and for making it a productive one. The slides and snapsots of the boards are placed in the groups SPP Git's repository.
- [Slides](https://spp2377-git.uos.de/meetings/2023/mini-workshop-on-a-benchmark-suite-for-data-placement-in-operating-systems/-/tree/main/BenchmarkIntros)
- [Discussion](https://spp2377-git.uos.de/meetings/2023/mini-workshop-on-a-benchmark-suite-for-data-placement-in-operating-systems/-/tree/main/BreakOut-Discussion)
- [Boards](https://spp2377-git.uos.de/meetings/2023/mini-workshop-on-a-benchmark-suite-for-data-placement-in-operating-systems/-/tree/main/Characterizations)

![Group Photo](../../images/mini_workshop_23_group_photo.jpeg)
