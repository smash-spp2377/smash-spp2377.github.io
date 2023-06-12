---
title: "CHEOPS Workshop at EuroSys 2023"
date: 2023-03-08T12:16:16+01:00
draft: false
sidebar: false
pager: false
tags:
  - "Publications"
---

Our paper titled "**Intelligent Data Migration Policies in a Write-Optimized Copy-on-Write Tiered Storage Stack**" has been accepted at [CHEOPS '23: Proceedings of the 3rd Workshop on Challenges and Opportunities of Efficient and Performant Storage Systems](https://cheops-workshop.github.io/)

#### Abstract
Modern storage stacks increasingly aim to intellegently optimize data accesses to improve latency, throughput, and energy consumption. Additionally, new
storage setups become more heterogeneous, due to the introduction of new storage media, like NVM, and ever-increasing requirements regarding storage capacity and performance.
However, the organization of these systems is an NP-hard problem, with some elements being even strongly NP-hard. Hence, decision heuristics act on proxy values such as data temperature, access frequency, or access recency to migrate data to assumed optimal storage locations, which may lead to undesired side-effects if utilized poorly. Additionally, with copy-on-write and write-optimized data structures becoming more common, held assumptions about data distribution and latency have changed.
We introduce a heterogeneous storage stack based on write-optimized $\text{B}^{\varepsilon}$-trees called \haura and use it to argue the case for and explore policies and issues of automated data migration. We implement migration functionality and a dynamic policy interface with two proven policies from other papers as example implementations. We find that strong differences in these heuristics exist, based on data size and access type, contradicting usual assumptions made on non-write-optimized non-CoW heterogeneous storage.  When performing data-intensive workloads these policies can bring a 30\% speedup when compared to a fallback policy. In this, the storage stack offers similar advantages as dedicated burst-buffers.



The publication is available in the ACM Digital Library. Please click [here](https://dl.acm.org/doi/10.1145/3578353.3589543) to access the publication.
