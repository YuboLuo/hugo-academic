---
title: "Text steganography with high embedding rate: Using recurrent neural networks to generate chinese classic poetry"
authors:
- admin
- Yongfeng Huang

author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2017-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 5th ACM workshop on information hiding and multimedia security*"
publication_short: ""

abstract: We propose a novel text steganography method using RNN Encoder-Decoder structure to generate quatrains, one genre of Chinese poetry. Compared to other text-generation based steganography methods which have either very low embedding rate or flaws in the naturalness of generated texts, our method has higher embedding rate and better text quality. In this paper, we use the LSTM Encoder-Decoder model to generate the first line of a quatrain with a keyword and then generate the following lines one by one. RNN has proved effective in generating poetry, but when applied to steganograpy, poetry quality decreases sharply, because of the redundancy we create to hide information. To overcome this problem, we propose a template-constrained generation method and develop a word-choosing approach using inner-word mutual information. Through a series of experiments, it is proven that our approach outperforms other poetry steganography methods in both embedding rate and poetry quality.

# Summary. An optional shortened abstract.
summary: (IHMMSEC 2017) Proceedings of the 5th ACM workshop on information hiding and multimedia security 

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
