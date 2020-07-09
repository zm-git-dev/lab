---
title: PEA
summary: Plant epitranscriptome analysis
tags:
- Epigenesis
- Genetic
- High-Throughput Nucleotide Sequencing
- Plants Genetics
- RNA
- RNA Processing
- Post-Transcriptional
- Software
- Transcriptome
date: "2018-11-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
- name: PubMed
  url: https://www.ncbi.nlm.nih.gov/pubmed/29850798
url_code: "https://github.com/cma2015/PEA"
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

**PEA** is a docker-based integrated R toolkit that aims to facilitate the plant epitranscriptome analysis. This toolkit contains a comprehensive collection of functions required for read mapping, CMR calling, motif scanning and discovery, and gene functional enrichment analysis. PEA also takes advantage of machine learning technologies for transcriptome-scale CMR prediction, with high prediction accuracy, using the Positive Samples Only Learning algorithm, which addresses the two-class classification problem by using only positive samples (CMRs), in the absence of negative samples (non-CMRs). Hence PEA is a versatile epitranscriptome analysis pipeline covering CMR calling, prediction, and annotation.

* [**View Details**](http://bioinfo.nwafu.edu.cn/publication/bioinformatics_2018_pea/)
* **Please cite the following article**:<br>

> Zhai, J., Song, J., Cheng, Q., Tang, Y., Ma, C. (2018). PEA: an integrated R toolkit for plant epitranscriptome analysis Bioinformatics  34(21), 3747-3749. https://dx.doi.org/10.1093/bioinformatics/bty421
