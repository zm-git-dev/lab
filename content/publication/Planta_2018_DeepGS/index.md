---
title: "A deep convolutional neural network approach for predicting phenotypes from genotypes"
authors:
- Wenlong Ma
- Zhixu Qiu
- Jie Song
- Jiajia Li
- Qian Cheng
- Jingjing Zhai
- Chuang Ma
date: "2018-11-24T00:00:00Z"
doi: "10.1007/s00425-018-2976-9"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-11-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Planta*"
publication_short: "Planta"

abstract: "Deep learning is a promising technology to accurately select individuals with high phenotypic values based on genotypic data. Genomic selection (GS) is a promising breeding strategy by which the phenotypes of plant individuals are usually predicted based on genome-wide markers of genotypes. In this study, we present a deep learning method, named DeepGS, to predict phenotypes from genotypes. Using a deep convolutional neural network, DeepGS uses hidden variables that jointly represent features in genotypes when making predictions; it also employs convolution, sampling and dropout strategies to reduce the complexity of high-dimensional genotypic data. We used a large GS dataset to train DeepGS and compared its performance with other methods. The experimental results indicate that DeepGS can be used as a complement to the commonly used RR-BLUP in the prediction of phenotypes from genotypes. The complementarity between DeepGS and RR-BLUP can be utilized using an ensemble learning approach for more accurately selecting individuals with high phenotypic values, even for the absence of outlier individuals and subsets of genotypic markers. The source codes of DeepGS and the ensemble learning approach have been packaged into Docker images for facilitating their applications in different GS programs."

# Summary. An optional shortened abstract.
# summary: "RNA N6-methyladenosine-modified genes exhibit biased subgenome fractionation, and their co-evolutionary relationship with transposable elements is mediated by genomic duplication in maize (Zea mays)."

tags:
- Deep Learning
- Ensemble Learning
- Genomic Selection
- Genotypic Marker
- High Phenotypic Values
- Machine Learning
featured: true

links:
- name: PubMed
  url: https://www.ncbi.nlm.nih.gov/pubmed/30101399
url_pdf: ''
url_code: 'https://github.com/cma2015/DeepGS'
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

- **基于深度学习技术的全基因组选择的生物信息学新方法研究**

> 全基因组选择(genomic selection,GS)育种是分子辅助育种新策略，实现了育种的定量化、信息化、精确化。但是，传统的GS模型往往伴随一定的假设，在捕捉基因型间以及基因型和表型间的复杂关系上有难度。深度学习是最近发展起来的新技术，拥有自主学习大数据内部复杂信息的能力，但是，其在GS上的应用并不成熟。本年度，研究了深度学习技术应用于GS的可行性。主要通过深度卷积神经网络(DeepGS)，在底层提取特征，在顶层汇总并映射到表型。研究发现，DeepGS可以作为现在应用广泛、稳健的岭回归最优线性无偏估计(RR-BLUP)的补充，为此构建基于鸟群算法的整合模型，提升预测优良性状个体的能力。研究表明，即使去除离群值，或者减少基因型标记数目，这种互补性仍旧存在。DeepGS模型已经打包成Docker Image，以方便其应用。上述研究成果发表在Planta（Ma et al., 2018）上。
