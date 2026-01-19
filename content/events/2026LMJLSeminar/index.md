---
title: Talk at LMJL seminar of applied math
summary: 'Natural gradient descent with momentum'

event: Séminaire de mathématiques appliquées
event_url: https://www.math.sciences.univ-nantes.fr/exposes/993686

location: Université de Nantes, Laboratoire de Mathématique Jean Leray
address:
  #street: 450 Serra Mall
  city: Nantes
  #region: CA
  #postcode: '94305'
  country: France

abstract: 'Natural gradient descent (NGD) can be seen as a preconditioned update where parameter changes are driven by a functional perspective. In a spirit similar to Newton’s method, the NGD update uses, instead of the Hessian, the Gram matrix of the generating system of the tangent space to the approximation manifold at the current iterate, with respect to a suitable metric. Although its assemblage and inversion is prohibitively expensive in the context of large machine learning models, it becomes not only feasible but necessary when we look at scientific machine learning problems using models not requiring as many parameters. Sill, both gradient and natural gradient descent will get stuck at any local minima. Furthermore, when the approximation class is a non-linear manifold (i.e. neural networks) or the loss function is other than L² distance (KL-divergence for a classification problem, PDE residual as in physics informed learning) even the natural gradient might yield non-optimal directions at each step. The talk will focus on how we can tackle these situations by introducing a Natural version of classical inertial dynamic methods like Nestorov or Heavy-ball.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2026-01-13T11:00:00-12:00" 
#date: "2026-13-00T11:00:00-12:00:00" 
#time_start = 2009-07-30T13:00:00 
#time_end = 2009-07-30T15:00:00
#date_start: '2025-11-27'
#date_end: '2025-11-27T12:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin
  - Anthony Nouy

tags: []

# Is this a featured talk? (true/false)
featured: true

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