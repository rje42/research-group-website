---
title: 'Model Selection and Local Geometry'
authors:
  - admin
date: '2020-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*Annals of Statistics, 48*(6)'
publication_short: 'Ann. Statist.'

abstract: We consider problems in model selection caused by the geometry of models close to their points of intersection.  In some cases---including common classes of causal or graphical models, as well as time series models---distinct models may nevertheless have identical tangent spaces.  This has two immediate consequences: first, in order to obtain constant power to reject one model in favour of another we need local alternative hypotheses that decrease to the null at a slower rate than the usual parametric $n^{-1/2}$ (typically we will require $n^{-1/4}$ or slower); in other words, to distinguish between the models we need large effect sizes or very large sample sizes.  Second, we show that under even weaker conditions on their tangent cones, models in these classes cannot be made simultaneously convex by a reparameterization.  This shows that Bayesian network models, amongst others, cannot be learned directly with a convex method similar to the graphical lasso. However, we are able to use our results to suggest methods for model selection that learn the tangent space directly, rather than the model itself.  In particular, we give a generic algorithm for learning Bayesian network models.

# Summary. An optional shortened abstract.
summary: Models do not always intersect in nice ways, and this has both statistical and computational consequences for model selection and inference.

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1801.08364

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides:
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).
