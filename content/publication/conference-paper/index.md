---
title: "Attention Bidirectional LSTM Networks Based Mime Speech Recognition Using sEMG Data"
authors:
- admin
date: "2020-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Surface electromyography (sEMG) has been proven competent and reliable to recognize speech musculature movement patterns. In other words, we can understand what a person prepares to say by collecting sEMG signals around the mouth. Therefore, sEMG-based Mime Speech Recognition (MSR) is a potential technique for human-machine interaction within noisy surroundings as well as the application of helping dysarthric patients. In this paper, we introduce multi-layer Bidirectional Long Short-Term Memory (BLSTM) networks with attention mechanism as a classifier for MSR, and verify it in the data set  collected by ourselves. Six-channel sEMG signals are firstly acquired from elaborately selected facial muscles. Short-time Fourier Transform (STFT) and Convolutional Neural Networks (CNN) are utilized to extract time-frequency domain feature maps, replacing the handcrafted features in classic methods. The second phase of recognition process lies in the designed classifier. This classification system achieves over 97% accuracy in the fourclass MSR task, significantly surpassing simple CNN and LSTM methods. Such result also indicates that excellent MSR results can be achieved without relying on handcrafted signal features.

# Summary. An optional shortened abstract.
summary: human-machine interaction, attention BLSTM, surface electromyography, mime speech recognition

tags:
- Source Themes
featured: true

# links:
# - name: Custom Link
#   url: https://github.com/shj1987/ControlVAE-ICML2020

url_pdf: https://drive.google.com/file/d/1N4vRk-szHmW-hitEm1fughwA9aBJdSLS/view?usp=sharing
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
  caption: 'Feature Engineering Diagram: [**time domain and time-frequency domain**](https://unsplash.com/photos/s9CC2SKySJM)'
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
