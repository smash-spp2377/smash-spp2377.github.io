---
title: "Workshop GVDB23"
date: 2023-03-09T12:16:16+01:00
draft: false
sidebar: false
pager: false
tags:
  - "Publications"
---

Our paper titled "**Assessing Non-volatile Memory in Modern Heterogeneous Storage Landscape using aWrite-optimized Storage Stack**" has been accepted at the [34th workshop on basics of database systems (Grundlage von Datenbanken)](https://gvdb23.informatik.uni-stuttgart.de/)

#### Abstract
Non-Volatile memory (NVM), or persistent memory, is a promising and emerging storage technology that has not only disrupted the typical long-established memory hierarchy but also invalidated the proclaimed programming paradigm used in traditional database management systems and file systems. It bridges the gap between primary and secondary storage and, hence, shares the characteristics of both categories. However, currently, there exists no common storage engine built particularly to study the characteristics of the modern storage landscape, which has become more heterogeneous after NVM. Therefore, a general-purpose storage engine, Haura, is utilized to study the benefits of the modern storage landscape. In this work, NVM is integrated into the storage stack of Haura and studied the patterns for modern storage devices involved and their impact on the performance of Haura. Our work shows, NVM performs best under sequential workloads, but random access is better with larger block sizes. Furthermore, the block size has a significant impact on the performance of storage devices, with smaller block sizes favoring NVM and larger block sizes favoring NVMe-supported devices.

#### Keywords
Non-Volatile Memory, Persistent Memory, Storage Class Memory, Non-Volatile Random Access Memory, Persistent Memory Programming, Modern Heterogeneous Storage Landscape, Write-Optimized Storage Engine (Haura)
