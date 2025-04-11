---
title: "LIOF: Make the Learned Index Learn Faster With Higher Accuracy"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tao Ji
- Kai Zhong
- admin
- Yiyan Li
- Cuiping L
- Hong Chen

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-03-05T00:00:00Z"
# doi: "10.1145/3514221.3520167"

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-06-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Knowledge and Data Engineering ( Early Access )
publication_short: TKDE 2025

abstract: Learned indexes, emerging as a promising alternative to traditional indexes like B+Tree, utilize machine learning models to enhance query performance and reduce memory usage. However, the widespread adoption of learned indexes is limited by their expensive training cost and the need for high accuracy of internal models. Although some studies attempt to optimize the building process of these learned indexes, existing methods are restrictive in scope and applicability. They are usually tailored to specific index types and heavily rely on pre-trained model knowledge, making deployment a challenging task. In this work, we introduce the Learned Index Optimization Framework (LIOF), a general and easily integrated solution aimed at expediting the training process and improving the accuracy of index model for one-dimensional and multi-dimensional learned indexes. The optimization of LIOF for the learned indexes is intuitive, directly providing optimized parameters for index models based on the distribution of node data. By leveraging the correlation between key distribution and node model parameters, LIOF significantly reduces the training epochs required for each node model. Initially, we introduce an optimization strategy inspired by optimization-based meta-learning to train the LIOF to generate optimized initial parameters for index node models. Subsequently, we present a data-driven encoder and a parameter-centric decoder network, which adaptively translate key distribution into a latent variable representation and decode it into optimized node model initialization. Additionally, to further utilize characteristics of key distribution, we propose a monotonic regularizer and focal loss, guiding LIOF training towards efficiency and precision. Through extensive experimentation on real-world and synthetic datasets, we demonstrate that LIOF provides substantial enhancements in both training efficiency and the predictive accuracy for learned indexes.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: DOI
  url: https://doi.org/10.1109/TKDE.2025.3548298

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
