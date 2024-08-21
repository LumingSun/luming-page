---
title: "Is Large Language Model Good at Database Knob Tuning? A Comprehensive Experimental Evaluation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yiyan Li
- Haoyang Li
- Zhao Pu
- Jing Zhang
- Xinyi Zhang
- Tao Ji
- admin
- Cuiping L
- Hong Chen

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-08-05T00:00:00Z"
# doi: "10.1145/3514221.3520167"

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-06-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: arXiv
publication_short: arXiv

abstract: Knob tuning plays a crucial role in optimizing databases by adjusting knobs to enhance database performance. However, traditional tuning methods often follow a Try-Collect-Adjust approach, proving inefficient and database-specific. Moreover, these methods are often opaque, making it challenging for DBAs to grasp the underlying decision-making process. The emergence of large language models (LLMs) like GPT-4 and Claude-3 has excelled in complex natural language tasks, yet their potential in database knob tuning remains largely unexplored. This study harnesses LLMs as experienced DBAs for knob-tuning tasks with carefully designed prompts. We identify three key subtasks in the tuning system: knob pruning, model initialization, and knob recommendation, proposing LLM-driven solutions to replace conventional methods for each subtask. We conduct extensive experiments to compare LLM-driven approaches against traditional methods across the subtasks to evaluate LLMs' efficacy in the knob tuning domain. Furthermore, we explore the adaptability of LLM-based solutions in diverse evaluation settings, encompassing new benchmarks, database engines, and hardware environments. Our findings reveal that LLMs not only match or surpass traditional methods but also exhibit notable interpretability by generating responses in a coherent ``chain-of-thought'' manner. We further observe that LLMs exhibit remarkable generalizability through simple adjustments in prompts, eliminating the necessity for additional training or extensive code modifications. Drawing insights from our experimental findings, we identify several opportunities for future research aimed at advancing the utilization of LLMs in the realm of database management.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2408.02213

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
