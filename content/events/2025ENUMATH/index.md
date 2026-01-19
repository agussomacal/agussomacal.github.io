---
title: "Talk at minisimposium in ENUMATH 2025"

event: MORTech 2025
event_url: https://enumath2025.eu/

location: Heidelberg University
address:
  #street: 450 Serra Mall
  city: Heidelberg
  #region: CA
  #postcode: '94305'
  country: Germany

summary: 'Natural gradient descent with momentum'
abstract: 'Natural gradient descent (NGD) can be seen as a preconditioned update where parameter changes are driven by a functional perspective. In a spirit similar to Newton’s method, the NGD update uses, instead of the Hessian, the Gram matrix of the generating system of the tangent space to the approximation manifold at the current iterate, with respect to a suitable metric. Although its assemblage and inversion is prohibitively expensive in the context of large machine learning models, it becomes not only feasible but necessary when we look at scientific machine learning problems using models not requiring as many parameters. Sill, both gradient and natural gradient descent will get stuck at any local minima. Furthermore, when the loss function is other than $L^2$ distance even the natural gradient might yield non-optimal directions at each step. The talk will focus on how we can tackle these situations by introducing a Natural version of classical inertial dynamic methods like Nestorov.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2025-09-04T10:00:00-10:30" 
#date_start: '2025-11-27'
#date_end: '2025-11-27T12:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-02-01T00:00:00Z'

authors:
  - admin
  - Anthony Nouy

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Photo by <a href="https://unsplash.com/@danieljschwarz?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Daniel J. Schwarz</a> on <a href="https://unsplash.com/photos/gray-rocky-mountain-under-white-clouds-during-daytime-REjuIrs2YaM?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
      '
  focal_point: Right

links:
  - type: slides
    url: https://slideshare.net

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - MomentumNGD
---