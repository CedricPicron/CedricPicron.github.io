---
title: 'EffSeg: Efficient Fine-Grained Instance Segmentation using Structure-Preserving Sparsity'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tinne Tuytelaars

date: '2023-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *ArXiv*
publication_short: In *ArXiv*

abstract: Many two-stage instance segmentation heads predict a coarse 28x28 mask per instance, which is insufficient to capture the fine-grained details of many objects. To address this issue, PointRend and RefineMask predict a 112x112 segmentation mask resulting in higher quality segmentations. Both methods however have limitations by either not having access to neighboring features (PointRend) or by performing computation at all spatial locations instead of sparsely (RefineMask). In this work, we propose EffSeg performing fine-grained instance segmentation in an efficient way by using our Structure-Preserving Sparsity (SPS) method based on separately storing the active features, the passive features and a dense 2D index map containing the feature indices. The goal of the index map is to preserve the 2D spatial configuration or structure between the features such that any 2D operation can still be performed. EffSeg achieves similar performance on COCO compared to RefineMask, while reducing the number of FLOPs by 71% and increasing the FPS by 29%.

# Summary. An optional shortened abstract.
summary: A new instance segmentation head performing fine-grained instance segmentation in an efficient way by using our Structure-Preserving Sparsity (SPS) method based on separately storing the active features, the passive features and a dense 2D index map containing the feature indices.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2307.01545.pdf'

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
