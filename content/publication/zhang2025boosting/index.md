---
title: 'Boosting Continual Instruction Tuning of Multimodal Large Language Models via Multi-Perspective Visual Representation and Null Space Projection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Junmin Liu*

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-05-08T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Association for the Advancement of Artificial Intelligence*
publication_short: In *AAAI*

abstract: Multi-modal Large Language Models (MLLMs) have showcased impressive performance across various multi-modal domains, with notable success in vision-language tasks. However, their acquisition often requires substantial time and resources for data gathering and model training. Recently, Continual Instruction Tuning (CIT) has emerged as a promising and efficient strategy for MLLMs, enabling the incremental adaptation of a large language model (LLM) to diverse visual instruction tasks. While there have been proposals of datasets and methodologies in the CIT for MLLMs, the majority of these efforts ulitize a pre-trained vision-language connector to align multimodal embeddings and deployed complicated modules to alleviate the forgetting of reasoning capabilities and the degradation of instructions, both of which occur as the parameters of LLMs change over time. In this paper, we observe that the model’s modality alignment ability significantly degrades in the process of CIT, especially when the new task contains conflicting objectives with the old task. Addressing this challenge, we propose to learn \textit{Multi-Perspective Orthogonal} (MPO) visual representations, enabling the model to adaptively integrate representations from different perspectives based on task types, and to handle task conflicts with orthogonal gradient projection. Comprehensive experiments showcase a significant performance improvement of our method compared to existing state-of-the-art methods, in both pre-training and pre-training-free settings.

# Summary. An optional shortened abstract.
summary: Multi-modal Large Language Models, Continual Instruction Tuning


tags:
- MLLMs
- Continual Learning


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: http://arxiv.org/
url_code: 'https://github.com/zdyoung0519/l2c'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Method Overview'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to cite our work.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
