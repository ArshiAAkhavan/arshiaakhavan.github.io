---
title: "LinkAnchor: An Autonomous LLM-Based Agent for Issue-to-Commit Link Recovery"
authors:
- admin
- Alireza hossein pour
- Abbas Heydarnoori
- Hamid Bagheri
- Mehdi Keshani
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-08-04T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2508.12232"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of the ACM International Conference on the Foundations of Software Engineering (FSE), Montreal, Canada, July 2026"
# publication_short: "FSE'26"

abstract: Issue-to-commit link recovery in software repositories is fundamental to software traceability and project management, yet it remains a challenging task. Prior studies show that only about 42.2% of issues on GitHub are correctly linked to their commits, highlighting the need for more effective solutions. Existing work has explored a range of ML/DL approaches, and more recently, large language models (LLMs) have been applied to this problem. However, these methods face two major limitations. First, LLMs are restricted by limited context windows and cannot simultaneously process all available data sources, such as long commit histories, extensive issue discussions, and large code repositories. Second, most approaches operate on individual issue–commit pairs, where a model independently scores the relevance of a single commit to an issue. This pairwise formulation fails to account for the complex associativity of software fixes, where an issue is often resolved by an aggregate chain of commits rather than a single atomic change. By ignoring these temporal and parental dependencies, existing methods often fail to incorporate the complete resolution logic and might misidentify intermediate commits as final fixes. Furthermore, this strategy is computationally inefficient in large repositories, as it requires exhaustively evaluating an enormous number of candidate pairs. To address these challenges, we present LinkAnchor, the first autonomous LLM-based agent designed specifically for issue-to-commit link recovery. LinkAnchor introduces a lazy-access architecture that allows the underlying LLM to dynamically retrieve only the most relevant contextual data, such as commits, issue comments, and code files, without exceeding token limits. Instead of isolated scoring, LinkAnchor treats link recovery as a dynamic search process, navigating the commit graph to identify the final resolving commit and effectively aggregating the entire chain of contributing changes. LinkAnchor is first to formalize ILR as dynamic heuristic search over commit chains (vs. prior pairwise scoring), enabling aggregate reasoning that recovers distributed fixes (46% of cases). Our evaluations show that LinkAnchor outperforms state-of-the-art baselines by 41–714% in Hit@1 across six large-scale open-source projects, while costing only about 0.01 US dollars per issue. Finally, LinkAnchor is designed and tested for both GitHub and Jira, and its modular architecture makes it straightforward to extend to other platforms.


# Summary. An optional shortened abstract.


tags:
- software engineering
- AI4SE
- Agentic-AI
- Issue-commit Link Recovery

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2508.12232'
url_code: 'https://github.com/ISE-Research/LinkAnchor'
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

