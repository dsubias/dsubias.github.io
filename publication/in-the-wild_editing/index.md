---
title: 'In-the-wild Material Appearance Editing using Perceptual Attributes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Manuel Lagunas

# Author notes (optional)
author_notes:
  - 'Universidad de Zaragoza, I3A, Spain'
  - 'Amazon, Spain (not related to his current position)'

date: ''
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Eurographics 2023*
publication_short: In *EG23*

abstract: Intuitively editing the appearance of materials from a single image is a challenging task given the complexity of the interactions between light and matter, and the ambivalence of human perception. This problem has been traditionally addressed by estimating additional factors of the scene like geometry or illumination, thus solving an inverse rendering problem and subduing the final quality of the results to the quality of these estimations. We present a single-image appearance editing framework that allows us to intuitively modify the material appearance of an object by increasing or decreasing high-level perceptual attributes describing such appearance (e.g., glossy or metallic). Our framework takes as input an in-the-wild image of a single object, where geometry, material, and illumination are not controlled, and inverse rendering is not required. We rely on generative models and devise a novel architecture with Selective Transfer Unit (STU) cells that allow to preserve the high-frequency details from the input image in the edited one. To train our framework we leverage a dataset with pairs of synthetic images rendered with physically-based algorithms, and the corresponding crowd-sourced ratings of high-level perceptual attributes. We show that our material editing framework outperforms the state of the art, and showcase its applicability on synthetic images, in-the-wild real-world photographs, and video sequences.

# Summary. An optional shortened abstract.
summary: We propose a STGAN-based framework for material appearance editing from an in-the-wild image of a single object.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2302.03619.pdf'
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
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

