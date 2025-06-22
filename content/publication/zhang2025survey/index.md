---
title: '深度模型的持续学习综述：理论、方法和应用'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Zixuan Lu
- Junmin Liu*
- Lanyu Li

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-02-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-28T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*电子与信息学报*"
publication_short: ""

abstract: 自然界中的生物需要在其一生中不断地学习并适应环境，这种持续学习的能力是生物学习系统的基础。尽管深度学习方法在计算机视觉和自然语言处理领域取得了重要进展，但它们在连续学习任务时面临严重的灾难性遗忘问题，即模型在学习新知识时会遗忘旧知识，这在很大程度上限制了深度学习方法的应用。持续学习研究对人工智能系统的改进和应用具有重要意义。该文对深度模型的持续学习进行了全面回顾。首先介绍了持续学习的定义和典型设定，阐述了问题的关键。其次，将现有持续学习方法划分为基于正则化、基于回放、基于梯度和基于网络结构4类，分析了各类方法的优点和局限性。同时，该文强调并总结了持续学习领域的理论分析进展，建立了理论与方法之间的联系。此外，提供了常用的数据集和评价指标，以公正评判不同方法。最后，从多个领域的应用价值出发，讨论了深度持续方法面临的问题、挑战和未来研究方向。

# Summary. An optional shortened abstract.
summary: 深度学习，持续学习，灾难性遗忘


tags:
- Survey
- Continual Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/zhang2025survey/paper.pdf'
url_code: ''
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
Click the _Cite_ button above to cite this paper.
{{% /callout %}}

{{% callout note %}}
Click the _PDF_ button above to view the full text of the paper.
{{% /callout %}}