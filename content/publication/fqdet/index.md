---
title: 'FQDet: Fast-converging Query-based Detector'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Punarjay Chakravarty
  - Tinne Tuytelaars

date: '2022-12-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS VTTA workshop 2022*
publication_short: In *NeurIPS VTTA workshop 2022*

abstract: Recently, two-stage Deformable DETR introduced the query-based two-stage head, a new type of two-stage head different from the region-based two-stage heads of classical detectors as Faster R-CNN. In query-based two-stage heads, the second stage selects one feature per detection processed by a transformer, called the query, as opposed to pooling a rectangular grid of features processed by CNNs as in region-based detectors. In this work, we improve the query-based head by improving the prior of the cross-attention operation with anchors, significantly speeding up the convergence while increasing its performance. Additionally, we empirically show that by improving the cross-attention prior, auxiliary losses and iterative bounding box mechanisms typically used by DETR-based detectors are no longer needed. By combining the best of both the classical and the DETR-based detectors, our FQDet head peaks at 45.4 AP on the 2017 COCO validation set when using a ResNet-50+TPN backbone, only after training for 12 epochs using the 1x schedule. We outperform other high-performing two-stage heads such as e.g. Cascade R-CNN, while using the same backbone and while being computationally cheaper. Additionally, when using the large ResNeXt-101-DCN+TPN backbone and multi-scale testing, our FQDet head achieves 52.9 AP on the 2017 COCO test-dev set after only 12 epochs of training.

# Summary. An optional shortened abstract.
summary: A new query-based two-stage object detection head combining the best of both classical and DETR-based detectors, by improving the cross-attention prior with anchors and introducing the effective top-k matching scheme.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2210.02318.pdf'
url_code: 'https://github.com/CedricPicron/FQDet'
url_poster: 'https://nips.cc/media/PosterPDFs/NeurIPS%202022/61318.png'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  focal_point: ''
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
slides: ''
---
