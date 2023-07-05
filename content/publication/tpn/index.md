---
title: 'Trident Pyramid Networks for Object Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tinne Tuytelaars

date: '2022-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *BMVC 2022*
publication_short: In *BMVC 2022*

abstract: Feature pyramids have become ubiquitous in multi-scale computer vision tasks such as object detection. Given their importance, a computer vision network can be divided into three parts; a backbone (generating a feature pyramid), a neck (refining the feature pyramid) and a head (generating the final output). Many existing networks operating on feature pyramids, named necks, are shallow and mostly focus on communication-based processing in the form of top-down and bottom-up operations. We present a new neck architecture called Trident Pyramid Network (TPN), that allows for a deeper design and for a better balance between communication-based processing and self-processing. We show consistent improvements when using our TPN neck on the COCO object detection benchmark, outperforming the popular BiFPN baseline by 0.5 AP, both when using the ResNet-50 and the ResNeXt-101-DCN backbone. Additionally, we empirically show that it is more beneficial to put additional computation into the TPN neck, rather than into the backbone, by outperforming a ResNet-101+ FPN baseline with our ResNet-50+ TPN network by 1.7 AP, while operating under similar computation budgets. This emphasizes the importance of performing computation at the feature pyramid level in modern-day object detection systems.

# Summary. An optional shortened abstract.
# summary: A new query-based two-stage object detection head combining the best of both classical and DETR-based detectors, by improving the cross-attention prior with anchors and introducing the effective top-k matching scheme.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://bmvc2022.mpi-inf.mpg.de/0241.pdf'
url_code: 'https://github.com/CedricPicron/TPN'
url_poster: 'https://bmvc2022.mpi-inf.mpg.de/0241_poster.pdf'

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
