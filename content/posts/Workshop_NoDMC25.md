---
title: "Workshop NoDMC (BTW) 2025"
date: 2025-02-14T12:16:16+01:00
draft: false
sidebar: false
pager: false
tags:
  - "Publications"
---

Our paper titled "**Embracing NVM: Optimizing B-epsilon-Tree Structures and Data Compression in Storage Engines**" has been accepted at the [3rd Workshop on Novel Data Management Ideas on Heterogeneous Hardware Architectures (NoDMC), co-located to BTW 2025 (Bamberg, Germany, March 3 - 7, 2025))](https://sites.google.com/view/nodmcbtw2025)

#### Abstract
Non-volatile memory (NVM) introduces a new class within the traditional storage hierarchy, combining attributes of both primary and secondary storage. NVM technologies offer latency approaching that of DRAM, though slightly higher, and significantly lower than traditional block storage devices. NVM is byte-addressable and provides persistence. Integrating NVM into various database and file systems has been the focus of extensive research. Efforts have centered on optimizing data structures like B-trees and LSM-trees and enhancing components such as buffer manager, logging, and recovery. However, a unified storage engine specifically designed to study the characteristics of the modern storage landscape, effectively utilizing and managing the potential of diverse memory and storage devices, does not currently exist. In this project, SMASH, we extend a storage engine to explore the benefits of the modern storage landscape. By integrating NVM into its storage stack, we aim to optimize data structures and employ compression techniques to minimize memory footprint. Initial experiments show strengths under sequential workloads and sensitivity to block sizes. Further modifications enable zero-copy deserialization and granular key-value access, fully leveraging NVM’s byte-addressable characteristics.

#### Keywords
Non-Volatile Memory, NVM-optimized Bepsilon-tree, Object and Key/Value Storage Engine
