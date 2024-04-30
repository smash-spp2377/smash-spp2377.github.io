---
title: "Workshop GVDB24"
date: 2024-04-09T12:16:16+01:00
draft: false
sidebar: false
pager: false
tags:
  - "Publications"
---

Our paper titled "**A Design Proposal for a Unified B-epsilon-Tree: Embracing NVM in Memory Hierarchies**" has been accepted at the [35th GI-Workshop on Foundations of Databases, May 22-24, 2024, Herdecke, Germany)](https://gvdb24.fernuni-hagen.de/)

#### Abstract
Non-volatile memory (NVM) represents a new class in the traditional storage hierarchy. The technologies in this class share characteristics of both primary and secondary storage; they provide latency that approaches that of DRAM, albeit moderately higher1, yet significantly lower than that of secondary storage devices, are addressable from cache lines, and, most importantly, offer persistence. NVM is often referred to as a disruptive memory technology because it has invalidated the traditional programming paradigms used in applications such as database management systems (DBMS) and file systems (FS). Substantial research have focused on integrating NVM into diverse DBMS and FS, specifically through optimizing data structures such as B-trees and LSM-trees. Despite these advancements, considerable opportunities remain to further exploit NVM to boost application performance, particularly by exploring variations of these data structures. In this work, we present a proposal to optimize the B𝜖-tree for use with NVM. The proposed modifications aim to capitalize on the unique characteristics of NVM, enhancing the tree’s efficiency in both read and write operations. Additionally, the suggested changes are designed to reduce computational overhead, particularly by minimizing the need for tree rebalancing operations. The development of the tree is in progress, and it is assumed that completion will take some time; therefore, this paper is presented as preliminary work.

#### Keywords
Non-Volatile Memory, Persistent Memory, B-tree, B-epsilon-tree, Key-Value Store
