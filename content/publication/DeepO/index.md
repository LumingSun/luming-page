---
title: "DeepO: A Learned Query Optimizer"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Tao Ji
- Cuiping Li
- Hong Chen

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-06-17T00:00:00Z"
doi: "10.1145/3514221.3520167"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2022 International Conference on Management of Data (Demo Track)*
publication_short: In *SIGMOD ’22 (Demo Track)*

abstract: Query optimization is crucial for the query performance of database systems. Despite decades of efforts from both research and industrial communities, query optimization remains one of the most challenging problems. Thanks to the advances in artificial intelligence, data-driven and learning-based techniques are seeing traction in database research recently. However, most former learning-based works perform less practical because they are evasive about the interaction between learning components and database systems.
In this demonstration,we introduce DeepO, a novel deep-learningbased query optimizer that offers high-quality and fine-grained query optimization efficiently and practically.We implement DeepO and incorporate it into PostgreSQL, and we also provide a web user interface, where users can carry out the optimization operations interactively and evaluate the optimization performance. Preliminary results show that DeepO outperforms the baseline PostgreSQL optimizer.

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
