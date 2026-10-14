---
title: Hash Map Based on Split-Ordered Lists
summary: |2-
    * Implemented a concurrent, lock-free hash map in **Rust** based on the [split-ordered lists](https://dl.acm.org/doi/abs/10.1145/1147954.1147958) paper.

tags:
    - Concurrency
    - System

date: "2023-08-01T00:00:00Z"

links:
  - icon: file-alt
    icon_pack: fas
    name: Paper
    url: https://dl.acm.org/doi/abs/10.1145/1147954.1147958
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
---

A concurrent hash map in Rust based on Shalev and Shavit's split-ordered lists, which grow the table without moving items between buckets.
