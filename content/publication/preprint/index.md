---
title: "Learning to Cooperate for Continual Learning with Pre-training and Parameter-Efficient Fine-tuning"
authors:
- admin
- Junmin Liu*
- Zixuan Lu
- Xiaorong Li
date: "2025-05-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The integration of Pre-Trained Models (PTMs) with Parameter-Efficient Fine-Tuning (PEFT) techniques has emerged as a prevalent paradigm in Continual Learnin} (CL), offering a promising strategy to overcome catastrophic forgetting. To retain previously learned knowledge, recent methodologies focus on optimizing only task-specific parameters during training and implementing a parameter selection mechanism for inference. However, this task isolation learning strategy can lead to suboptimal performance in CL due to its  susceptibility to misallocated inputs after adapting to individual tasks. Addressing this issue, we first present a unified framework that formulates the PTM-based CL methods as an ensemble of multiple experts. Based on this framework, the fundamental factors crucial for CL can be derived by theoretically analyzing its generalization bounds, which reveal a trade-off between task isolation and task cooperation, yielding new insights and a better interpretation for CL dynamics. And then, we propose a novel method, referred to Learning to Cooperate (L2C), to explore the feasibility of task cooperation. Specifically, L2C involves an expert selector as a guide for dynamic expert allocation and output aggregation. In addition, several training strategies and optimization objectives are introduced to improve forward and backward knowledge transfer and facilitate cross-expert cooperation. Finally, we evaluate L2C on various CL benchmarks, demonstrating its competitive or superior performance compared to state-of-the-art methods. Our code is available at https://github.com/zdyoung0519/l2c.

# Summary. An optional shortened abstract.
summary: Continual learning, pre-trained models, parameter-efficient fine-tuning, task-specific, cooperation.

tags:
- Continual Learning
- Pre-Trained Models

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/
url_code: 'https://github.com/zdyoung0519/l2c'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs. -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
