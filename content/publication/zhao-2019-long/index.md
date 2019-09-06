---
title: "Long-Form Video Question Answering via Dynamic Hierarchical Reinforced Networks"
date: 2019-01-01
authors: ["Zhou Zhao", "Zhu Zhang", "Shuwen Xiao", "Zhenxin Xiao", "Xiaohui Yan", "Jun Yu", "Deng Cai", "Fei Wu"]
abstract: ""
featured: false

doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-05T05:52:10.075857Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Image Processing*"
publication_short: ""

abstract: Open-ended long-form video question answering is a challenging task in visual information retrieval, which automatically generates a natural language answer from the referenced long-form video contents according to a given question. However, the existing works mainly focus on short-form video question answering, due to the lack of modeling semantic representations from long-form video contents. In this paper, we introduce a dynamic hierarchical reinforced network for open-ended long-form video question answering, which employs an encoder–decoder architecture with a dynamic hierarchical encoder and a reinforced decoder. Concretely, we first propose a frame-level dynamic long-short term memory (LSTM) network with binary segmentation gate to learn frame-level semantic representations according to the given question. We then develop a segment-level highway LSTM network with a question-aware highway gate for segment-level semantic modeling. Furthermore, we devise the reinforced decoder with a hierarchical attention mechanism to generate natural language answers. We construct a large-scale long-form video question answering dataset. The extensive experiments on the long-form dataset and another public short-form dataset show the effectiveness of our method.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8737880

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'illustration'
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
slides: ""
---
