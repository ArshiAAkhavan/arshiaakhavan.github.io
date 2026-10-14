---
title: Hazard Pointers
summary: |2-
    * Implemented hazard pointers in **Rust** for safe memory reclamation in lock-free data structures.

tags:
    - Concurrency
    - System

date: "2023-08-01T00:00:00Z"

links: []
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
---

Hazard pointers let a thread announce which shared nodes it is about to read, so that other threads defer freeing them. This implementation provides safe memory reclamation for lock-free data structures in Rust.
