---
title: "SCVP:Multi-stage Method for Online Vertical Data Partitioning Based on Spectral Clustering (In Chinese)"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Pengju Liu
- Haoyang Li
- Tianyi Wang
- admin
- Cuiping Li
- Hong Chen

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-09-27T00:00:00Z"
# doi: "10.13328/j.cnki.jos.006384"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Software*
publication_short: In *JOS*

abstract: Vertical data partitioning technology logically stores database table attributes satisfying certain semantic conditions in the same physical block, so as to reduce the cost of data accessing and improve the efficiency of querie processing. Every query is usually only related to the table’s some attributes in the database, so only a subset of the table’s attributes can be used to get the accurate query results. Reasonable vertical data partitioning can make most queries answered without scanning the whole table, so as to reduce the amount of data accessing and improve the efficiency of query processing. Traditional database vertical partitioning methods are mainly based on heuristic rules set by experts. The granularity of partitioning is coarse, and it can not provide different partition optimizations according to the characteristics of workload. Besides, when the scale of workload or the number of attributes becomes large, the execution time of the existing methods are too long and especially can not meet the performance requirements of online real-time tuning of database. Therefore, we propose a method called Spectral Clustering based Vertical Partitioning (SCVP) for the online environment. We adapt the idea of phased solution to reduce the time complexity of the algorithm and speed up partitioning. Firstly, SCVP reduces the solution space by increasing the constraint conditions, that is, generating initial partitions by spectral clustering. Secondly, SCVP designs the algoithum to search solution space, that is, the initial partitions are optimized by combining frequent itemset mining and greedy search. In order to further improve the performance of SCVP under high-dimensional attributes, we propose a new method called Special Clustering based Vertical Partitioning Redesign (SCVP-R) which is an improved version of SCVP. SCVP-R optimizes the partitions combiner component of SCVP by introducing sympatric-competition mechanism, double-elimination mechanism, and loop mechanism. The experimental results on different datasets show that SCVP and SCVP-R have faster execution time and better performance than the current state-of-the-art vertical partitioning method.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Online
  url: http://www.jos.org.cn/jos/article/abstract/Lf049

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
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
