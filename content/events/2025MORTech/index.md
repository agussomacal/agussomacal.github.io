---
title: "Talk at MORTech 2025"

event: MORTech 2025
event_url: https://mortech2025.i3a.es/

location: Universidad de Zaragoza
address:
  #street: 450 Serra Mall
  city: Zaragoza
  #region: CA
  #postcode: '94305'
  country: Spain

summary: 'Natural gradient descent with momentum for physics informed learning'
abstract: 'Natural gradient descent (NGD) recently received a lot of attention for approximating functions in nonlinear manifolds [1]. NGD can be seen as a preconditioned update where parameter changes are driven by a functional perspective [2]. In a spirit similar to a second order (or Newton’s) method, the NGD update uses, instead of the Hessian, the Gram matrix of the generating system of the tangent space to the approximation manifold at the current iterate, with respect to a suitable metric [3]. 
Although the assemblage and inversion of the Gram matrix is prohibitively expensive in the context of big machine learning models, it becomes not only feasible but necessary when we look at scientific machine learning problems [4] not requiring as many parameters. For example when searching for the solution of a parametric partial differential equation (pPDE) by solving the forward (given parameters) or inverse (given measurements) problems using Physics Informed Neural Networks (PINNs) traditional ubiquitous solvers like Adam or L-BFGS do not yield reliable solutions or they take too long to converge [5]. However, taking the natural gradient perspective allows us to reinterpret gradient descent as a projection of the functional gradient into the tangent space of the approximation manifold obtaining great improvements. That being said, both gradient and natural gradient descent will still get stuck at any local minima. Furthermore, when the loss function is other than the L2 distance (for example when minimising the residual of a pPDE as in PINNs) even the natural gradient might yield non-optimal directions at each step. We will first focus on how we can tackle these situations by introducing a Natural version of classical inertial dynamic methods like Nestorov [6] or heavy-ball [7] and second we will show how this strategy can be used to improve the optimization of PINNs.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2025-11-27T12:00:00-12:30" 
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