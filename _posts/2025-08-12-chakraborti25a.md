---
title: Conformal Prediction for Reliable Image Super-Resolution
abstract: Single image super-resolution (SISR) has been employed over a wide range
  of applications to enhance the visual quality and details of images. For training
  super-resolution (SR) models, low-resolution (LR) images are synthesized from the
  high-resolution (HR) images. However, these artificial intelligence (AI) methods
  for SR (like diffusion based or generative adversarial models) have stochastic elements
  that are inherent to the learning process that can be mitigated but not avoided.
  Effectively this means that for the same input LR image, different instantiations
  of the generative process is expected to produce slightly different HR output images.
  While this might not be an issue for certain applications, and in fact might provide
  interesting variations in tasks like AI art generation, in certain other high stakes
  applications like medical image super-resolution, such variations need to be tightly
  controlled and rigorously quantified. After all, when superresolving a biomedical
  image (say radiology) one would ideally expect the output to be invariant for a
  patient if it is a static time-independent image. In fact, though the point of super-resolving
  a biomedical image is to provide the human expert (or indeed an equivalent AI system)
  the visual clarity to make a better evaluation, having degradation of clinical features
  or introduction of spurious morphological features would defeat the purpose, and
  potentially increase the chances of a false inference. Thus it is important in such
  high risk applications to predict uncertainty bounds for the generated images using
  a conformal prediction inspired estimate of maximum calibrated coverage.
pdf: https://raw.githubusercontent.com/mlresearch/v266/main/assets/chakraborti25a/chakraborti25a.pdf
url: https://proceedings.mlr.press/v266/chakraborti25.html
booktitle: Proceedings of the Fourteenth Symposium on Conformal and Probabilistic
  Prediction with Applications
section: Extended Abstracts
crossref: COPA2025
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborti25a
month: 0
tex_title: Conformal Prediction for Reliable Image Super-Resolution
firstpage: 756
lastpage: 757
page: 756-757
order: 756
cycles: false
bibtex_author: Chakraborti, Tapabrata and Dey, Samiran
author:
- given: Tapabrata
  family: Chakraborti
- given: Samiran
  family: Dey
date: 2025-08-12
address:
container-title: Proceedings of the Fourteenth Symposium on Conformal and Probabilistic
  Prediction with Applications
volume: '266'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 8
  - 12
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
