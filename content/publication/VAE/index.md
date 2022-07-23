---
title: "Rethinking Controllable Variational Autoencoders"
authors:
- Haohong Lin*, Huajie Shao*, Yifei Yang*, Longzhong Lin, Yizhuo Chen, Qinmin Yang, Han Zhao
date: "2022-06-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "CVPR 2022"
publication_short: ""

abstract: The Controllable Variational Autoencoder (ControlVAE) combines automatic control theory with the basic VAE model to manipulate the KL-divergence for overcoming posterior collapse and learning disentangled representations. It has shown success in a variety of applications, such as image generation, disentangled representation learning, and language modeling. However, when it comes to disentangled representation learning, ControlVAE does not delve into the rationale behind it. The goal of this paper is to develop a deeper understanding of ControlVAE in learning disentangled representations, including the choice of a desired KL-divergence (i.e, set point), and its stability during training. We first fundamentally explain its ability to disentangle latent variables from an information bottleneck perspective. We show that KL-divergence is an upper bound of the variational information bottleneck. By controlling the KL-divergence gradually from a small value to a target value, ControlVAE can disentangle the latent factors one by one. Based on this finding, we propose a new DynamicVAE that leverages a modified incremental PI (proportionalintegral) controller, a variant of the proportional-integralderivative (PID) algorithm, and employs a moving average as well as a hybrid annealing method to evolve the value of KL-divergence smoothly in a tightly controlled fashion. In addition, we analytically derive a lower bound of the set point for disentangling. We then theoretically prove the stability of the proposed approach. Evaluation results on multiple benchmark datasets demonstrate that DynamicVAE achieves a good trade-off between the disentanglement and reconstruction quality. We also discover that it can separate disentangled representation learning and reconstruction via manipulating the desired KL-divergence.

# Summary. An optional shortened abstract.
summary: Disentangled Representation, Dynamic Systems

tags:
- Source Themes
featured: true

# links:
# - name: Custom Link
#   url: https://github.com/shj1987/ControlVAE-ICML2020

url_pdf: https://openaccess.thecvf.com/content/CVPR2022/papers/Shao_Rethinking_Controllable_Variational_Autoencoders_CVPR_2022_paper.pdf
url_code: 'https://github.com/shj1987/ControlVAE-ICML2020'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'PID Controller for hyper parameter β: [**A diagram view**](https://unsplash.com/photos/s9CC2SKySJM)'
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
