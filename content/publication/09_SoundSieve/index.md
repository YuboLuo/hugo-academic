---
title: "SoundSieve: Seconds-Long Audio Event Recognition on Intermittently-Powered Systems"
authors:
- Mahathir Monjur
- admin
- Zhenyu Wang
- Shahriar Nirjon

author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-02-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The 21st ACM International Conference on Mobile Systems, Applications, and Services*"
publication_short: ""

abstract: A fundamental problem of every intermittently-powered sensing system is that signals acquired by these systems over a longer period in time are also intermittent. As a consequence, these systems fail to capture parts of a longer-duration event that spans over multiple charge-discharge cycles of the capacitor that stores the harvested energy. From an application's perspective, this is viewed as sporadic bursts of missing values in the input data -- which may not be recoverable using statistical interpolation or imputation methods. In this paper, we study this problem in the light of an intermittent audio classification system and design an end-to-end system -- SoundSieve -- that is capable of accurately classifying audio events that span multiple on-off cycles of the intermittent system. SoundSieve employs an offline audio analyzer that learns to identify and predict important segments of an audio clip that must be sampled to ensure accurate classification of the audio. At runtime, SoundSieve employs a lightweight, energy- and content-aware audio sampler that decides when the system should wake up to capture the next chunk of audio; and a lightweight, intermittence-aware audio classifier that performs imputation and on-device inference. Through extensive evaluations using popular audio datasets as well as real systems, we demonstrate that SoundSieve yields 5\%--30\% more accurate inference results than the state-of-the-art. 
 

# Summary. An optional shortened abstract.
summary: (MobiSys 2023) The 21st ACM International Conference on Mobile Systems, Applications, and Services

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
