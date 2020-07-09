---
title: "Machine learning-based differential network analysis: a study of stress-responsive transcriptomes in Arabidopsis"
authors:
- Chuang Ma
- Mingming Xin
- Kenneth A. Feldmann
- Xiangfeng Wang
date: "2014-02-26T00:00:00Z"
doi: "10.1105/tpc.113.121913"

# Schedule page publish date (NOT publication's date).
publishDate: "2014-02-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*The Plant Cell*"
publication_short: "Plant Cell"

abstract: "Machine learning (ML) is an intelligent data mining technique that builds a prediction model based on the learning of prior knowledge to recognize patterns in large-scale data sets. We present an ML-based methodology for transcriptome analysis via comparison of gene coexpression networks, implemented as an R package called machine learning-based differential network analysis (mlDNA) and apply this method to reanalyze a set of abiotic stress expression data in Arabidopsis thaliana. The mlDNA first used a ML-based filtering process to remove nonexpressed, constitutively expressed, or non-stress-responsive \"noninformative\" genes prior to network construction, through learning the patterns of 32 expression characteristics of known stress-related genes. The retained \"informative\" genes were subsequently analyzed by ML-based network comparison to predict candidate stress-related genes showing expression and network differences between control and stress networks, based on 33 network topological characteristics. Comparative evaluation of the network-centric and gene-centric analytic methods showed that mlDNA substantially outperformed traditional statistical testing-based differential expression analysis at identifying stress-related genes, with markedly improved prediction accuracy. To experimentally validate the mlDNA predictions, we selected 89 candidates out of the 1784 predicted salt stress-related genes with available SALK T-DNA mutagenesis lines for phenotypic screening and identified two previously unreported genes, mutants of which showed salt-sensitive phenotypes."

# Summary. An optional shortened abstract.
# summary: "RNA N6-methyladenosine-modified genes exhibit biased subgenome fractionation, and their co-evolutionary relationship with transposable elements is mediated by genomic duplication in maize (Zea mays)."

tags:
- Arabidopsis Genetics
- Arabidopsis Physiology
- Artificial Intelligence
- Databases
- Genetic
- Gene Expression Profiling
- Gene Expression Regulation
- Plant
- Gene Regulatory Networks
- Genes
- Genetic Association Studies
- Phenotype
- Signal Transduction Drug Effects
- Signal Transduction Genetics
- Sodium Chloride Pharmacology
- Software
- Stress
- Physiological Genetics
- Transcriptome Genetics
featured: false

links:
- name: PubMed
  url: https://www.ncbi.nlm.nih.gov/pubmed/24520154
url_pdf: ''
url_code: 'https://github.com/cran/mlDNA'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

