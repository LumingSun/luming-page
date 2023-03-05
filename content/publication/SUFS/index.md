---
title: "SUFS: A Generic Storage Usage Forecasting Service Through Adaptive Ensemble Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Shijin Gong
- Tieying Zhang
- Fuxin Jiang
- Zhibing Zhao
- Jianjun Chen
- Xinyu Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

# date: "2022-06-17T00:00:00Z"
# doi: "10.1145/3514221.3520167"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-7T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 39th IEEE International Conference on Data Engineering*
publication_short: In *ICDE ’22 (Industry and Applications Track)*

abstract: Storage space usage forecasting is critical for the scalability and stability of storage systems. Cloud providers estimate storage usages based on the forecast and allocate resources accordingly. Overestimated space usages require a redundant storage buffer that brings unnecessary cost, and underestimated space usages will cause capacity shortages that may lead to data loss and Service-Level Agreement (SLA) failures. While accurate storage forecasting is important, it is highly challenging due to various storage usage patterns on different workloads and storage systems. Moreover, some operations from users or administrators may cause transient workload burst in historical data, which makes forecasting even harder.

In this paper, we propose the Storage Usage Forecasting Service (SUFS) that combines deep neural networks and statistical models adaptively to make predictions for multiple major storage systems in ByteDance. SUFS carries comprehensive analyses of storage usage time series from various storage systems in real business scenarios. To handle workload bursts in historical data, we enhance regular LSTMs using a control signal that is installed on the input gate. When the burst is detected, the control signal reduces the input influences to the cell state. To further improve the prediction accuracy, SUFS integrates the Enhanced-LSTM (ELSTM) with a novel adaptive ensemble method. Different from previous works, our approach learns dynamic ensemble weights for each prediction step on-the-fly, making our model more accurate for multiple-step predictions. SUFS has been deployed to serve more than 150,000 storage instances. We conducted extensive experiments on the storage systems that are widely-used in ByteDance, and the results show that SUFS outperforms the state-of-the-art methods and significantly reduces storage cost.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: yes

# Custom links (uncomment lines below)
# links:
# - name: Early Access
#   url: https://ieeexplore.ieee.org/abstract/document/9540288

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
