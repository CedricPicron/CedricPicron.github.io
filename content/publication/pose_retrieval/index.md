---
title: 'Category-level pose retrieval with contrastive features learnt with occlusion augmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Georgios Kouros
  - Shubham Shrivastava
  - admin
  - Sushruth Nagesh
  - Punarjay Chakravarty
  - Tinne Tuytelaars

date: '2022-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *BMVC 2022*
publication_short: In *BMVC 2022*

abstract: Pose estimation is usually tackled as either a bin classification or a regression problem. In both cases, the idea is to directly predict the pose of an object. This is a non-trivial task due to appearance variations between similar poses and similarities between dissimilar poses. Instead, we follow the key idea that comparing two poses is easier than directly predicting one. Render-and-compare approaches have been employed to that end, however, they tend to be unstable, computationally expensive, and slow for real-time applications. We propose doing category-level pose estimation by learning an alignment metric in an embedding space using a contrastive loss with a dynamic margin and a continuous pose-label space. For efficient inference, we use a simple real-time image retrieval scheme with a pre-rendered and pre-embedded reference set of renderings. To achieve robustness to real-world conditions, we employ synthetic occlusions, bounding box perturbations, and appearance augmentations. Our approach achieves state-of-the-art performance on PASCAL3D and OccludedPASCAL3D and surpasses the competing methods on KITTI3D in a cross-dataset evaluation setting.

# Summary. An optional shortened abstract.
# summary: A new query-based two-stage object detection head combining the best of both classical and DETR-based detectors, by improving the cross-attention prior with anchors and introducing the effective top-k matching scheme.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://bmvc2022.mpi-inf.mpg.de/0026.pdf'
url_code: 'https://github.com/gkouros/contrastive-pose-retrieval'
url_poster: 'https://bmvc2022.mpi-inf.mpg.de/0026_poster.pdf'

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
