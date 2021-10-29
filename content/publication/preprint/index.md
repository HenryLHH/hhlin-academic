---
# title: "Challenging β-VAE with β < 1 for Disentanglement Via Dynamic Learning"
# authors:
# - admin
# date: "2020-09-15T00:00:00Z"
# doi: ""

# # Schedule page publish date (NOT publication's date).
# publishDate: "2020-09-15T00:00:00Z"

# # Publication type.
# # Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# # 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# # 7 = Thesis; 8 = Patent
# publication_types: ["3"]

# # Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

# abstract: This paper challenges the common assumption that the weight of β-VAE should be larger than 1 in order to effectively disentangle latent factors. We demonstrate that β-VAE with β≤1 can not only obtain good disentanglement but significantly improve the reconstruction accuracy via dynamic control. The goal of this paper is to deal with the trade-off problem between reconstruction accuracy and disentanglement with unsupervised learning. The existing methods, such as β-VAE and FactorVAE, assign a large weight in the objective, leading to high reconstruction errors in order to obtain better disentanglement. To overcome this problem, ControlVAE is recently developed to dynamically tune the weight to achieve the trade-off between disentangling and reconstruction using control theory. However, ControlVAE cannot fully decouple disentanglement learning and reconstruction, because it suffers from overshoot problem of the designed controller and does not timely respond to the target KL-divergence at the beginning of model training. In this paper, we propose a novel DynamicVAE that leverages an incremental PI controller, a variant of proportional-integral-derivative controller (PID) controller, and moving average as well as hybrid annealing method to effectively decouple the reconstruction and disentanglement learning. We then theoretically prove the stability of the proposed approach. Evaluation results on benchmark datasets demonstrate that DynamicVAE significantly improves the reconstruction accuracy for the comparable disentanglement compared to the existing methods. More importantly, we discover that our method is able to separate disentanglement learning and reconstruction without introducing any conflict between them.

# # Summary. An optional shortened abstract.
# summary: Disentanglement Representation, Variational Auto-Encoder, Evidence Lower Bound, Dynamic Systems

# tags:
# - Source Themes
# featured: true

# # links:
# # - name: Custom Link
# #   url: https://github.com/shj1987/ControlVAE-ICML2020

# url_pdf: https://arxiv.org/pdf/2009.06795.pdf
# url_code: 'https://github.com/shj1987/ControlVAE-ICML2020'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'PID Controller for hyper parameter β: [**A diagram view**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
# - internal-project

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example

title: "CausalAF: Causal Autoregressive Flow for Goal-Directed Safety-Critical Scenes Generation"
authors:
- Wenhao Ding, Haohong Lin, Bo Li, Ding Zhao
date: "2021-10-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Goal-directed generation, aiming for solving downstream tasks by generating diverse data, has a potentially wide range of applications in the real world. Previous works tend to formulate goal-directed generation as a purely data-driven problem, which directly searches or approximates the distribution of samples satisfying the goal. However, the generation ability of preexisting work is heavily restricted by inefficient sampling, especially for sparse goals that rarely show up in off-the-shelf datasets. For instance, generating safety-critical traffic scenes with the goal of increasing the risk of collision is critical to evaluate autonomous vehicles, but the rareness of such scenes is the biggest resistance. In this paper, we integrate causality as a prior into the safety-critical scene generation process and propose a flow-based generative framework - Causal Autoregressive Flow (CausalAF). CausalAF encourages the generative model to uncover and follow the causal relationship among generated objects via novel causal masking operations instead of searching the sample only from observational data. By learning the cause-and-effect mechanism of how the generated scene achieves the goal rather than just learning correlations from data, CausalAF significantly improves the learning efficiency. Extensive experiments on three heterogeneous traffic scenes illustrate that CausalAF requires much fewer optimization resources to effectively generate goal-directed scenes for safety evaluation tasks.

# Summary. An optional shortened abstract.
summary: Causal Generative Models, Safety-critical Scene Generation, Autonomous driving

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
  caption: 'Diagram of proposed CausalAF. (pipeline_3.png)'
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
