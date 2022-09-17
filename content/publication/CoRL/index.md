---
title: "CausalAF: Causal Autoregressive Flow for Goal-Directed Safety-Critical Scenes Generation"
authors:
- [Wenhao Ding](https://wenhao.pub/), Haohong Lin, Bo Li, Ding Zhao
date: "2021-10-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "CoRL 2022"
publication_short: "CoRL 2022"

abstract: Goal-directed generation, aiming for solving downstream tasks by generating diverse data, has a potentially wide range of applications in the real world. Previous works tend to formulate goal-directed generation as a purely data-driven problem, which directly searches or approximates the distribution of samples satisfying the goal. However, the generation ability of preexisting work is heavily restricted by inefficient sampling, especially for sparse goals that rarely show up in off-the-shelf datasets. For instance, generating safety-critical traffic scenes with the goal of increasing the risk of collision is critical to evaluate autonomous vehicles, but the rareness of such scenes is the biggest resistance. In this paper, we integrate causality as a prior into the safety-critical scene generation process and propose a flow-based generative framework - Causal Autoregressive Flow (CausalAF). CausalAF encourages the generative model to uncover and follow the causal relationship among generated objects via novel causal masking operations instead of searching the sample only from observational data. By learning the cause-and-effect mechanism of how the generated scene achieves the goal rather than just learning correlations from data, CausalAF significantly improves the learning efficiency. Extensive experiments on three heterogeneous traffic scenes illustrate that CausalAF requires much fewer optimization resources to effectively generate goal-directed scenes for safety evaluation tasks.

# Summary. An optional shortened abstract.
summary: CoRL 2022
# Causal Generative Models, Safety-critical Scene Generation, Autonomous driving

tags:
- Source Themes
featured: true

# links:
# - name: Custom Link
#   url: https://github.com/shj1987/ControlVAE-ICML2020

url_pdf: https://arxiv.org/pdf/2110.13939.pdf
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
  caption: 'Diagram of proposed CausalAF. '
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

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
