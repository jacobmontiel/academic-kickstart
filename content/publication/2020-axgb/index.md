---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Adaptive XGBoost for Evolving Data Streams"
authors: [Montiel Jacob, Mitchell Rory, Frank Eibe, Pfahringer Bernhard, Abdessalem Talel, Bifet Albert]
date: 2020-09-28
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate:

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "2020 International Joint Conference on Neural Networks"
publication_short: "IJCNN"

abstract: "Boosting is an ensemble method that combines base models in a sequential manner to achieve high predictive accuracy. A popular learning algorithm based on this ensemble method is eXtreme Gradient Boosting (XGB). We present an adaptation of XGB for classification of evolving data streams. In this setting, new data arrives over time and the relationship between the class and the features may change in the process, thus exhibiting concept drift. The proposed method creates new members of the ensemble from mini-batches of data as new data becomes available. The maximum ensemble size is fixed, but learning does not stop when this size is reached because the ensemble is updated on new data to ensure consistency with the current concept. We also explore the use of concept drift detection to trigger a mechanism to update the ensemble. We test our method on real and synthetic data with concept drift and compare it against batch-incremental and instance-incremental classification methods for data streams."

# Summary. An optional shortened abstract.
summary: ""

tags: ["research", "data streams", "boosting"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2005.07353
url_code: https://github.com/jacobmontiel/AdaptiveXGBoostClassifier
url_dataset:
url_poster:
url_project:
url_slides:
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
