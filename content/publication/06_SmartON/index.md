---
title: "SmartON: Just-in-time active event detection on energy harvesting systems"
authors:
- admin
- Shahriar Nirjon

author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-07-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*17th International Conference on Distributed Computing in Sensor Systems*"
publication_short: ""

abstract: We propose SmartON, a batteryless system that learns to wake up proactively at the right moment in order to detect events of interest. It does so by adapting the duty cycle to match the distribution of event arrival times under the constraints of harvested energy. While existing energy harvesting systems either wake up periodically at a fixed rate to sense and process the data, or wake up only in accordance with the availability of the energy source, SmartON employs a three-phase learning framework to learn the energy harvesting pattern as well as the pattern of events at run-time, and uses that knowledge to wake itself up when events are most likely to occur. The three-phase learning framework enables rapid adaptation to environmental changes in both short and long terms. Being able to remain asleep more often than a CTID (charging-then-immediate-discharging) wake-up system and adapt to the event pattern, SmartON is able to reduce energy waste, increase energy efficiency, and capture more events. To realize Smar- tON we have developed a dedicated hardware platform whose power management module activates capacitors on-the-fly to dynamically increase its storage capacitance. We conduct both simulation-driven and real-system experiments to demonstrate that SmartON captures 1X–7X more events and is 8X–17X more energy-efficient than a CTID system. 

# Summary. An optional shortened abstract.
summary: (DCOSS 2021) 17th International Conference on Distributed Computing in Sensor Systems
 

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
