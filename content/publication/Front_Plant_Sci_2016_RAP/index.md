---
title: "A Meta-Analysis Based Method for Prioritizing Candidate Genes Involved in a Pre-specific Function"
authors:
- Jingjing Zhai
- Yunjia Tang
- Hao Yuan
- Longteng Wang
- Haoli Shang
- Chuang Ma
date: "2016-12-15T00:00:00Z"
doi: "10.3389/fpls.2016.01914"

# Schedule page publish date (NOT publication's date).
publishDate: "2016-12-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Frontiers in Plant Science*"
publication_short: "Front Plant Sci"

abstract: "The identification of genes associated with a given biological function in plants remains a challenge, although network-based gene prioritization algorithms have been developed for Arabidopsis thaliana and many non-model plant species. Nevertheless, these network-based gene prioritization algorithms have encountered several problems; one in particular is that of unsatisfactory prediction accuracy due to limited network coverage, varying link quality, and/or uncertain network connectivity. Thus, a model that integrates complementary biological data may be expected to increase the prediction accuracy of gene prioritization. Toward this goal, we developed a novel gene prioritization method named RafSee, to rank candidate genes using a random forest algorithm that integrates sequence, evolutionary, and epigenetic features of plants. Subsequently, we proposed an integrative approach named RAP (Rank Aggregation-based data fusion for gene Prioritization), in which an order statistics-based meta-analysis was used to aggregate the rank of the network-based gene prioritization method and RafSee, for accurately prioritizing candidate genes involved in a pre-specific biological function. Finally, we showcased the utility of RAP by prioritizing 380 flowering-time genes in Arabidopsis. The \"leave-one-out\" cross-validation experiment showed that RafSee could work as a complement to a current state-of-art network-based gene prioritization system (AraNet v2). Moreover, RAP ranked 53.68% (204/380) flowering-time genes higher than AraNet v2, resulting in an 39.46% improvement in term of the first quartile rank. Further evaluations also showed that RAP was effective in prioritizing genes-related to different abiotic stresses. To enhance the usability of RAP for Arabidopsis and non-model plant species, an R package implementing the method is freely available at http://bioinfo.nwafu.edu.cn/software."

# Summary. An optional shortened abstract.
#summary: 

tags:
- Biological Network
- Data Fusion
- Flowering Time
- Gene Prioritization
- Machine Learning
- Meta-Analysis
- Rank Aggregation
- Systems Biology
featured: true

links:
- name: PubMed
  url: https://www.ncbi.nlm.nih.gov/pubmed/28018423
url_pdf: ''
url_code: 'https://github.com/cma2015/RAP'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

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
# slides: example
---

