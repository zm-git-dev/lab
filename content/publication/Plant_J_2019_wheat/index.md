---
title: "Hybrid sequencing reveals insight into heat sensing and signaling of bread wheat"
authors:
- Xiaoming Wang
- Siyuan Chen
- Xue Shi
- Danni Liu
- Peng Zhao
- Yunze Lu
- Yanbing Cheng
- Zhenshan Liu
- Xiaojun Nie
- Weining Song
- Qixin Sun
- Shengbao Xu
- Chuang Ma
date: "2019-01-29T00:00:00Z"
doi: "10.1111/tpj.14299"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Plant Journal*"
publication_short: "Plant J"

abstract: "Wheat (*Triticum aestivum L.*), a globally important crop, is challenged by increasing temperatures (heat stress, HS); however, its polyploid nature, the incompleteness of its genome sequences and annotation, the lack of comprehensive HS-responsive trans    criptomes and the unexplored heat sensing and signaling of wheat hinder our full understanding of its adaptations to HS. The recently released genome sequences of wheat, as well as the emerging single-molecular sequencing technologies, provides an opportunity to tho    roughly investigate the molecular mechanisms of the wheat response to HS. We generated a high-resolution spatio-temporal transcriptome map of wheat flag leaves and filling grain under HS at 0 minute (m), 5 m, 10 m, 30 m, 1 hour (h) and 4 h by combining full-length s    ingle-molecular sequencing and Illumina short reads sequencing. This hybrid sequencing newly discovered 4,947 loci and 70,285 transcripts, generating the comprehensive and dynamic list of HS-responsive full-length transcripts and complementing the recently released     wheat reference genome. Large-scale analysis revealed a global landscape of heat adaptations, uncovering unexpected rapid heat sensing and signaling, significant changes of more than half of HS-responsive genes within 30 m, heat shock factor (HSF)-dependent and -ind    ependent heat signaling, and metabolic alterations in early HS-responses. Integrated analysis also demonstrated the differential responses and partitioned functions between organs and subgenomes, and suggested a differential pattern of transcriptional and alternativ    e splicing regulation in the HS response. This study provided comprehensive data for dissecting molecular mechanisms of early HS-responses in wheat and highlighted the genomic plasticity and evolutionary divergence of polyploidy wheat."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Alternative Splicing Regulation
- Early Heat Stress
- Heat Sensing and Signaling
- Hybrid Sequencing
- Spatio-Temporal Transcriptome
- Transcriptional Regulation
- Wheat (Triticum aestivum L.)
featured: false

links:
- name: PubMed
  url: https://www.ncbi.nlm.nih.gov/pubmed/30891832
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
image:
  caption: ""
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

### 主要研究结果：

1. 小麦转录组数据分析的生物信息学流程搭建

     针对三代测序数据错误率高、小麦基因组的多倍体等特性，搭建了一套小麦二代和三代转录组测序数据整合分析的生物信息学流程，准确地实现了三代测序数据的纠错、亚基因组定位等功能，鉴定出4,947个新的基因位点和70,285条新的转录本（图二）。这些基因和转录本为后面充分的转录组数据分析奠定了基础，也为相关基因的功能研究和小麦基因组注释信息的完善提供了参考。搭建的生物信息学分析流程，为小麦等多倍体物种的大规模转录组学数据分析提供了新技术和新思路。

  ![figure2](/img/wheat/figure2.jpeg)

    图二 新基因和新转录本的发掘与鉴定

2. 高温信号的快速感受和传递

     转录组分析表明超过50%的转录水平响应基因，和70%左右的可变剪切水平响应基因在胁迫发生后30分钟内即被检测到，同时不同数量的热激转录因子（高温信号传递链的末端）在高温胁迫后5分钟的旗叶和胁迫后10分钟的籽粒中被检测到响应，说明植物对高温胁迫的响应速度远高于其它非生物胁迫，但是这种快速性响应的生物学意义仍待进一步挖掘。早期的响应过程主要包括“碳代谢和多糖代谢”、“蛋白折叠”、“光合作用”、“电子传递”和“胁迫响应”等生理生化过程，暗示着其在高温信号感受和传递中发挥着重要作用，同时更新了代谢过程主要发生在胁迫后期的适应性过程中的观点（图三）。这里我们虽然第一次检测到了热激转录因子上游的信号，但是这些信号间的传递顺序还需进一步研究。

  ![figure3](/img/wheat/figure3.jpeg)
    
    图三 小麦生理生化过程对高温胁迫的动态响应。热图表示每个时间点转录水平（A）和可变剪切水平（B）响应基因的KEGG通路富集倍数，白色方格代表对应KEGG通路在该时间点富集不显著，“L”表示旗叶，“G”表示灌浆籽粒，“DEG”表示转录水平高温胁迫响应基因，“DSG” 表示可变剪切水平高温胁迫响应基因。

3. 旗叶和灌浆籽粒对高温胁迫的响应模式不同

     旗叶和籽粒是小麦发育后期与产量形成关系最为密切的两个组织器官。转录组分析表明旗叶对高温胁迫的响应更为剧烈，响应速度也更快，而籽粒作为储存碳水化合物的主要器官，在高温胁迫下更为稳定（图四和五）。这与我们前期的研究结果相一致（Wang等，2017），即籽粒中热激蛋白编码基因本底表达量高于其它组织，暗示着籽粒在长期的进化过程中已经形成了一定的“耐热性”。

  ![figure4](/img/wheat/figure4.jpeg)
  
    图四和五 旗叶和灌浆籽粒对高温胁迫的转录组分析

4. 转录水平调控和剪切水平调控响应高温胁迫的独立性

     转录水平调控和剪切水平调控是细胞调控mRNA丰度的两种主要方式，两者间的相互作用关系一直是该领域的研究热点。我们发现转录水平响应基因数目随着高温胁迫时间的延长而递增，但是剪切水平响应基因数目在不同胁迫时间点间相对稳定，说明两者对高温胁迫的响应模式不同，而且剪切水平调控（不需要花费时间累积mRNA数量）在早期高温信号的传递中发挥着更为重要的作用。另外，转录和剪切水平响应基因间只有10%左右的重叠率（图六），说明两者间以相互独立的角色行使作用，共同完成对高温胁迫的响应。

  ![figure5](/img/wheat/figure5.jpeg)
    
    图六 转录水平调控和剪切水平调控

5. 不同亚基因组间高温胁迫响应功能的分化

     小麦包含A、B、D三个亚基因组，数据分析表明三个亚基因组上的同源基因对高温胁迫的响应发生了明显的分化（只有一个或者两个亚基因组上的基因发生了响应），而且这种分化在不同时间点间是动态变化的（图七）。这些结果说明三个亚基因组为小麦在高温胁迫下的适应性进化提供了更多的资源和方向，这种特性也赋予了六倍体小麦相较于二倍体和四倍体亲本更强的环境适应能力，进而使其生长范围更加广泛。

  ![figure6](/img/wheat/figure6.jpeg)
    
    图七 A、B、D三个亚基因组对高温的响应

* [小麦研究联盟(公众号):二代结合三代转录组测序探究小麦对高温信号的传递](https://mp.weixin.qq.com/s?__biz=MzI1MjIyODIzMA==&mid=2247488578&idx=1&sn=ecc383e0246dc4d9725d4ae7934c5bb5&chksm=e9e7b3abde903abd5207a0b349f54214b3b549b602a23a7326a09cec52174ece971237429d31&mpshare=1&scene=23&srcid=#rd)
