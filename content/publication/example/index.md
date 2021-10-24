---
title: "MOSE: A Monotonic Selectivity Estimator Using Learned CDFr"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Cuiping Li
- Tao Ji
- Hong Chen

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-09-16T00:00:00Z"
doi: "10.1109/TKDE.2021.3112753"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Knowledge and Data Engineering*
publication_short: In *TKDE*

abstract: The accuracy of selectivity estimation is of vital importance to create good query plans. Traditional estimators such as histograms make several assumptions during estimation that can lead to huge errors. Recently the database community started exploring the usage of machine learning in selectivity estimation and won great achievements. However, due to the black box models they used, existing learning-based methods still face several new challenges, including high estimation latency, large training data demanding, and occurrence of illogical results. In this work, we propose a learning-based MOnotonic Selectivity Estimator (MOSE) to address these challenges. We first learn a multi-dimensional cumulative distribution function of the data in a supervised method and then compute selectivity for ad hoc query predicates at rum-time. We propose a novel regularizer and an effective attribute-aware calibration method to improve the estimation accuracy. To further improve the model efficiency, we design a mutual information based model ensemble method. With regard to the heavy cost of training data collection, we design a model-based active learning strategy to generate high-quality training data cost-effectively. We conduct extensive experiments on both real-world and synthetic datasets and the results show that MOSE outperforms the state-of-the-art methods in terms of accuracy and efficiency.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Early Access
  url: https://ieeexplore.ieee.org/abstract/document/9540288

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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
