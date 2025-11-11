---
title: "An example journal article"
authors:
- Albert Cohen
- Olga Mula
- admin
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-03-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*ESAIM: Mathematical Modelling and Numerical Analysis*"
publication_short: "ESAIM-M2AN"

abstract: We consider the problem of recovering characteristic functions u := χΩ from cell-average data on a coarse grid, and where Ω is a compact set of Rd. This task arises in very different contexts such as image processing, inverse problems, and the accurate treatment of interfaces in finite volume schemes. While linear recovery methods are known to perform poorly, nonlinear strategies based on local reconstructions of the jump interface Γ := ∂Ω by geometrically simpler interfaces may offer significant improvements. We study two main families of local reconstruction schemes, the first one based on nonlinear least-squares fitting, the second one based on the explicit computation of a polynomial- shaped curve fitting the data, which yields simpler numerical computations and high order geometric fitting. For each of them, we derive a general theoretical framework which allows us to control the recovery error by the error of best approximation up to a fixed multiplicative constant. Numerical tests in 2d illustrate the expected approximation order of these strategies. Several extensions are discussed, in particular the treatment of piecewise smooth interfaces with corners.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Cell averages / inverse problems / geometric interfaces / subcell resolution
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.esaim-m2an.org/articles/m2an/pdf/2025/02/m2an240052.pdf
url_code: 'https://github.com/agussomacal/SubCellResolution'
url_dataset: ''
url_poster: 'https://github.com/agussomacal/SubCellResolution/blob/master/Posters/SubCell_Poster_Khipu.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
