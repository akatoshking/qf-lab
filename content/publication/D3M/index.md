---
title: "D3M: A Deep Domain Decomposition Method for Partial Differential Equations"
authors:
#Ke Li  ; Kejun Tang ; Tianfan Wu ; Qifeng Liao
- KeLi
- KejunTang
- Tianfan Wu
- admin
date: "2019-12-01T00:00:00Z"
# https://doi.org/10.1016/j.jcp.2019.06.059
doi: "https://doi.org/10.1109/ACCESS.2019.2957200"

# Schedule page publish date (NOT publication's date).02 December 2019
publishDate: "2019-11-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access, Volume 8, 2020, Pages 5283-5294"
publication_short: ""

abstract: A state-of-the-art deep domain decomposition method (D3M) based on the variational principle is proposed for partial differential equations (PDEs). The solution of PDEs can be formulated as the solution of a constrained optimization problem, and we design a hierarchical neural network framework to solve this optimization problem. Through decomposing a PDE system into components parts, our D3M builds local neural networks on physical subdomains independently (which can be implemented in parallel), so as to obtain efficient neural network approximations for complex problems. Our analysis shows that the D3M approximation solution converges to the exact solution of the underlying PDEs. The accuracy and the efficiency of D3M are validated and demonstrated with numerical experiments.

# Summary. An optional shortened abstract.
summary: We design a hierarchical neural network framework to solve this optimization problem.

tags:
- Domain decomposition
- Neural network
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8918421    
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
slides: ""
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
