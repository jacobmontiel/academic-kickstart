---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning Fast and Slow: A Unified Batch/Stream Framework."
authors: [Montiel Jacob, Bifet Albert, Losing Viktor, Read Jesse, Abdessalem Talel]
date: 2018-12-10
doi: "https://doi.org/10.1109/BigData.2018.8622222"

# Schedule page publish date (NOT publication's date).
publishDate:

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2018 IEEE International Conference on Big Data"
publication_short: "Big Data 2018"

abstract: "Data ubiquity highlights the need of efficient and adaptable data-driven solutions. In this paper, we present FAST AND SLOW LEARNING (FSL), a novel unified framework that sheds light on the symbiosis between batch and stream learning. FSL works by employing Fast (stream) and Slow (batch) Learners, emulating the mechanisms used by humans to make decisions. We showcase the applicability of FSL on the task of classification by introducing the FAST AND SLOW CLASSIFIER (FSC). A Fast Learner provides predictions on the spot, continuously updating its model and adapting to changes in the data. On the other hand, the Slow Learner provides predictions considering a wider spectrum of seen data, requiring more time and data to create complex models. Once that enough data has been collected, FSC trains the Slow Learner and starts tracking the performance of both learners. A drift detection mechanism triggers the creation of new Slow models when the current Slow model becomes obsolete. FSC selects between Fast and Slow Learners according to their performance on new incoming data. Test results on real and synthetic data show that FSC effectively drives the positive interaction of stream and batch models for learning from evolving data streams."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/document/8622222
url_code:
url_dataset:
url_poster:
url_project:
url_slides: https://docs.google.com/presentation/d/e/2PACX-1vRmed55HgjouHnZqvdBBj38L6VH2iKs2Lo9n95w24Cqz2iNFvtCCVyOD087cval2SgSg0red1sa46_Z/pub?start=false&loop=true&delayms=3000
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [scikit-multiflow]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
