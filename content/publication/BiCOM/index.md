---
title: "BECAUSE: Bilinear Causal Representation for Generalizable Offline Model-based Reinfocement Learning"
authors:
- Haohong Lin, Wenhao Ding, Jian Chen, Laixi Shi, Jiacheng Zhu, Bo Li, Ding Zhao
date: "2024-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Under Review"
publication_short: "Under Review"

abstract: Offline Reinforcement Learning offers the promise of leveraging off-the-shelf datasets to learn policies, especially when exploration is costly or impractical. However, the generalization of policies is sometimes hampered by spurious correlations in the offline data. To address this, we integrate causal discovery into a low-rank Markov Decision Process (MDP) framework to reduce such spurious correlation. We propose Bilinear Causal wOrld Modeling~(BiCOM), an algorithm that uses low-rank MDP to capture causal transition dynamics for generalizing offline RL algorithms. Recognizing the scarcity of benchmarks in offline causal RL, we design a decision-making benchmark with spurious correlation. Empirical evaluations over 18 tasks with different data quality demonstrate the superior performance of BiCOM over existing offline RL algorithms in online deployments. Complementing the empirical findings, we also provide a theoretical analysis of BiCOM's finite-sample guarantees under structure awareness and pessimism, reassuring the effectiveness and efficiency of incorporating low-rank MDP in the offline setting.



# Summary. An optional shortened abstract.
summary: Under Review
# Controllable Deep Generative Models

tags:
- Source Themes
featured: true

# links:
# - name: Custom Link
#   url: https://github.com/shj1987/ControlVAE-ICML2020

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
  caption: 'BECAUSE diagram: [**causal world modeling and uncertainty-aware conservative planning**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
