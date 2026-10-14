---
title: "Yggdrasil: a Layer-First 3D Scene Graph for Real-Time Querying"
authors:
- admin
- Ermanno Bartoli
- Afnan Algharbi
- Alireza Hoseinpur
- Iolanda Leite
- Bryan Donyanavard
date: "2026-09-29T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2609.38640"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2609.38640"
# publication_short: ""

abstract: Robotic agents use 3D scene graphs (3DSG) to perform tasks ranging from scene understanding to scene interaction. Although an extensive body of work addresses scene graph generation, little attention has been paid to optimizing the graph for consumption, which leaves state-of-the-art perception pipelines to work around their own scene graph and to pay a latency cost that does not fit the real-time budget a perception loop runs on. We present Yggdrasil, the first 3D scene graph designed to be efficient for both generation and consumption, a layer-first hierarchical graph built from generic nodes, edges, and layers, which expresses the representations existing pipelines already produce, indoor or outdoor, flat or hierarchical, while natively answering the positional and semantic queries downstream tasks issue. Against a published DSG baseline, Yggdrasil answers queries up to 121× faster, and every query we measure falls between 2 and 127 µs, three to five orders of magnitude inside the 200 ms keyframe budget a 3DSG consumer lives in, on both a workstation and embedded class device. We integrate Yggdrasil into three published pipelines spanning human trajectory prediction, object-goal navigation, and human-aware motion planning, where it removes up to 99% of the time each spends on its scene graph. The implementation, benchmark harness, and all three integrations are available online.


# Summary. An optional shortened abstract.


tags:
- robotics
- 3D Scene Graphs
- Rust
- Systems

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://arxiv.org/pdf/2609.38640"
url_code: 'https://github.com/brdsdsu/Yggdrasil'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---
