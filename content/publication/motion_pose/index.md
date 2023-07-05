---
title: 'What My Motion tells me about Your Pose: A Self-Supervised Monocular 3D Vehicle Detector'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Punarjay Chakravarty
  - Tom Roussel
  - Tinne Tuytelaars

date: '2021-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE International Conference on Robotics and Automation (ICRA)*
publication_short: In *ICRA 2021*

abstract: The estimation of the orientation of an observed vehicle relative to an Autonomous Vehicle (AV) from monocular camera data is an important building block in estimating its 6 DoF pose. Current Deep Learning based solutions for placing a 3D bounding box around this observed vehicle are data hungry and do not generalize well. In this paper, we demonstrate the use of monocular visual odometry for the self-supervised fine-tuning of a model for orientation estimation pre-trained on a reference domain. Specifically, while transitioning from a virtual dataset (vKITTI) to nuScenes, we recover up to 70% of the performance of a fully supervised method. We subsequently demonstrate an optimization-based monocular 3D bounding box detector built on top of the self-supervised vehicle orientation estimator without the requirement of expensive labeled data. This allows 3D vehicle detection algorithms to be self-trained from large amounts of monocular camera data from existing commercial vehicle fleets.

# Summary. An optional shortened abstract.
# summary: A new query-based two-stage object detection head combining the best of both classical and DETR-based detectors, by improving the cross-attention prior with anchors and introducing the effective top-k matching scheme.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2007.14812.pdf'
url_code: 'https://github.com/CedricPicron/SelfSupervisedObject3D'

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
