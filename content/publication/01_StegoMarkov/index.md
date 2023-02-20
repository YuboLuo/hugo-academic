---
title: "Text steganography based on ci-poetry generation using Markov chain model"
authors:
- admin
- Yongfeng Huang
- Fufang Li
- Chinchen Chang

author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2016-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*KSII Transactions on Internet and Information Systems*"
publication_short: "TIIS"

abstract: Steganography based on text generation has become a hot research topic in recent years. However, current text-generation methods which generate texts of normal style have either semantic or syntactic flaws. Note that texts of special genre, such as poem, have much simpler language model, less grammar rules, and lower demand for naturalness. Motivated by this observation, in this paper, we propose a text steganography that utilizes Markov chain model to generate Ci-poetry, a classic Chinese poem style. Since all Ci poems have fixed tone patterns, the generation process is to select proper words based on a chosen tone pattern. Markov chain model can obtain a state transfer matrix which simulates the language model of Ci-poetry by learning from a given corpus. To begin with an initial word, we can hide secret message when we use the state transfer matrix to choose a next word, and iterating until the end of the whole Ci poem. Extensive experiments are conducted and both machine and human evaluation results show that our method can generate Ci-poetry with higher naturalness than former researches and achieve competitive embedding rate..

# Summary. An optional shortened abstract.
summary: (TIIS 2016) KSII Transactions on Internet and Information Systems

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
