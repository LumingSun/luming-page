---
title: "COOOL: A Learning-To-Rank Approach for SQL Hint Recommendations "

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xianghong Xu
- Zhibing Zhao
- Tieying Zhang
- Rong Kang
- admin
- Jianjun Chen

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-07-16T00:00:00Z"
# doi: "10.1145/3514221.3520167"

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-06-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 5th International Workshop on Applied AI for Database Systems and Applications @ VLDB
publication_short: In *AIDB 2023@VLDB*

abstract: Query optimization is a pivotal part of every database management system (DBMS) since it determines the efficiency of query execution. Numerous works have introduced Machine Learning (ML) techniques to this field, but few of them are proven practical due to long training time, lack of interpretability, and integration cost. A recent study provides a practical method to optimize queries by recommending per-query hints but it suffers from two inherited problems. First, it follows the regression framework to predict the absolute latency of each query plan, which is very challenging because the latencies of query plans for a certain query may span multiple orders of magnitude. Second, it requires training a model for each dataset, which restricts the application of the trained models in practice. In this paper, we propose COOOL to predict Cost Orders of query plans to cOOperate with DBMS by Learning-To-Rank. Instead of estimating absolute costs, COOOL uses ranking-based approaches to compute relative ranking scores of the costs of query plans. We show that COOOL is theoretically valid to distinguish between better and worse query plans. We implement COOOL on PostgreSQL, and extensive experiments on join-order-benchmark and TPC-H data demonstrate that COOOL outperforms PostgreSQL and state-of-the-art methods on single-dataset tasks as well as a unified model for multiple-dataset tasks. Our experiments also shed some light on why COOOL outperforms regression approaches from the representation learning perspective, which may guide future research.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

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
