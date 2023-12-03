---
layout: post
title: Faceted Retrieval of CS Research Papers
description: Information Retrieval Course Project
---

# About

In this project, I developed a retrieval system to rank research papers similar to user query using a specific facet like background or method. First, we filtered out the CS papers from the Highly Influential Citations (HIC) Dataset from SciRepEval Benchmark. To achieve this, we trained a classifier using SciBERT that determines the field of study of a research paper. Finally, we utilized contrastive-loss to fine- SPECTER and SciNCL models using the CS papers filtered from HIC. In this work, we imposed a stricter notion of inter-document similarity: two research papers were considered to be similar only if one paper cites the other atleast 4 times.

# Code and Report

Source code and project report: [Github Repository](https://github.com/adityasoni9998/Information_Retrieval_SciDocFind){:target="_blank"}