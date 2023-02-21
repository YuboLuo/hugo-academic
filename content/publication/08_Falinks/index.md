---
title: "Amalgamated Intermittent Computing System"
authors:
- Bashima Islam
- admin
- Shahriar Nirjon

author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-02-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*In International Conference on Internet-of-Things Design and Implementation*"
publication_short: ""

abstract: Intermittent computing systems undergo frequent power failure, hindering necessary data sample capture or timely on-device computation. These missing samples and deadlines limit the potential usage of intermittent computing systems in many time-sensitive and fault-tolerant applications. However, a group/swarm of intermittent nodes may amalgamate to sense and process all the samples by taking turns in waking up and extending their on-time. However, coordinating a swarm of intermittent computing nodes requires frequent and power-hungry communication, often infeasible with limited energy. Though previous works have shown promises when all intermittent nodes have access to the same amount of energy to harvest, work has yet to be looked into scenarios when the available energy distribution is different for each node. The proposed AICS framework provides an amalgamated intermittent computing system where each node schedules its wake-up schedules based on the duty cycle without communication overhead. We propose one offline tailored duty cycle selection method (Prime-Co-Prime), which schedules wake-up and sleep cycles for each node based on the measured energy to harvest for each node and the prior knowledge or estimation regarding the relative energy distribution. However, when the energy is variable, the problem is formulated as a Decentralized-Partially Observable Markov Decision Process (Dec-POMDP). Each node uses a group of heuristics to solve the Dec-POMDP and schedule its wake-up cycle. We conduct a real-world experiment by implementing a deep acoustic event classifier in three MSP430 microcontrollers. AICS successfully captures and processes 41.17\% more samples than a swarm of greedy intermittent computing systems while spending 69.7\% less time with multiple redundant active systems. Our simulation-based evaluations show a 35.73\%–54.40\% higher compute and process success rate with AICS than with state-of-the-art algorithms (including reinforcement learning).

# Summary. An optional shortened abstract.
summary: (IoTDI 2023) In International Conference on Internet-of-Things Design and Implementation
 

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
