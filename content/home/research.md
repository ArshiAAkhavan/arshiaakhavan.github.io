---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:

  - title: Graduate Research Assistant
    company: San Diego State University
    company_url: 'https://www.sdsu.edu'
    location: San Diego, CA
    date_start: '2025-09-01'
    description: |2-
        Advisor: [Bryan Donyanavard](https://bryandony.github.io/)

        * Building [**Yggdrasil**](https://github.com/brdsdsu/Yggdrasil), a 3D scene graph for robots, written in **Rust** and designed for both construction and querying. Its layers form a DAG rather than a stack, and it answers pattern-matching, nearest-neighbor, field-of-view and traversal queries in place, using per-layer and per-node spatial indexes it keeps current as the graph changes.
        * Every measured query takes 2–127 µs, up to **121× faster** than a published C++ baseline. Yggdrasil is integrated into three published robotics pipelines and removes up to **99%** of the time they spend on their scene graph operations.
        * Currently extending Yggdrasil to multi-agent settings where each agent contributes its own view of the world, and a global server resolves the **logical and semantic conflicts** between them.
        * Fully funded by NSF award CNS-2348349.

  - title: Research Collaborator (AEBench)
    company: University of Illinois Urbana-Champaign
    company_url: 'https://github.com/AEBench/AEBench'
    location: Remote
    date_start: '2026-06-01'
    description: |2-
        With Bogdan Alexandru Stoica

        * [AEBench](https://github.com/AEBench/AEBench) measures how effective AI agents are in reproducing the results of published systems artifacts, and proposes a systematic framework for evaluation and execution of AI agents on artifact evaluation.
        * The goal is to provide Artifact Evaluation Committees with a tool to fully automate the evaluation process via use of AI agents.

  - title: Graduate Researcher (LLM Agents for Software Engineering)
    company: Bowling Green State University
    company_url: 'https://www.bgsu.edu'
    company_logo: bgsu
    location: Bowling Green, OH
    date_start: '2025-01-01'
    date_end: '2025-09-01'
    description: |2-
        Advisor: Abbas Heydarnoori

        * Built [**LinkAnchor**](https://github.com/ISE-Research/LinkAnchor), an autonomous agent that recovers links between issues and the commits that fix them (FSE '26, first author).
        * **LIA**: supervised fine-tuning of LLMs for automatic issue assignment.
        * Bug triaging with instruction-tuned LLMs.

design:
  columns: '2'
---
