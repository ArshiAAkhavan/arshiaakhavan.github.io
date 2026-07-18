---
title: "LIA: Supervised Fine-Tuning of Large Language Models for Automatic Issue Assignment"
authors:
- Arsham Khosravani
- Alireza hossein pour
- admin
- Mehdi Keshani
- Abbas Heydarnoori
date: "2026-01-05T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2601.01780"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-01-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2601.01780"
# publication_short: ""

abstract: Issue assignment is a critical process in software maintenance, where new issue reports are validated and assigned to suitable developers. However, manual issue assignment is often inconsistent and error-prone, especially in large open-source projects where thousands of new issues are reported monthly. Existing automated approaches have shown promise, but many rely heavily on large volumes of project-specific training data or relational information that is often sparse and noisy, which limits their effectiveness. To address these challenges, we propose LIA (LLM-based Issue Assignment), which employs supervised fine-tuning to adapt an LLM, DeepSeek-R1-Distill-Llama-8B in this work, for automatic issue assignment. By leveraging the LLM's pretrained semantic understanding of natural language and software-related text, LIA learns to generate ranked developer recommendations directly from issue titles and descriptions. The ranking is based on the model's learned understanding of historical issue-to-developer assignments, using patterns from past tasks to infer which developers are most likely to handle new issues. Through comprehensive evaluation, we show that LIA delivers substantial improvements over both its base pretrained model and state-of-the-art baselines. It achieves up to +187.8% higher Hit@1 compared to the DeepSeek-R1-Distill-Llama-8B pretrained base model, and outperforms four leading issue assignment methods by as much as +211.2% in Hit@1 score. These results highlight the effectiveness of domain-adapted LLMs for software maintenance tasks and establish LIA as a practical, high-performing solution for issue assignment.


# Summary. An optional shortened abstract.


tags:
- software engineering
- AI4SE
- Issue Assignment
- Large Language Models

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://arxiv.org/pdf/2601.01780"
url_code: ''
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

