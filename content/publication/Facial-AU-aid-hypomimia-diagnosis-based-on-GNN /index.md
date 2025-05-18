---
title: "Facial AU-aid hypomimia diagnosis based on GNN "
authors:
- 徐荥璟
- 林博
- Wei Luo
- Shuiguang Deng,
- Jianwei Yin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'  
#   - 'Equal contribution'

date: "2023-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference-paper"]

# Publication name and optional abbreviated publication name.
publication: "Medical Imaging with Deep Learning"
publication_short: "MIDL 2023"

abstract: Hypomimia is a prevalent symptom of Parkinson's Disease(PD). It is characterized by reduced facial expression and delayed facial movement. The work proposes a framework to use Graph Neural Network(GNN) to extract related action unit(AU) features on the facial smiling videos to help to improve the recognition of hypomimia with PD. AU is an effective representation of the facial state and movement, while GNN has great capability to present relationship information between facial areas. A related AU representation can pay more attention to the relationships between the facial areas in order to increase the accuracy of the diagnosis. Experiments were conducted using an in-house dataset of 105 facial smiling videos, which contains 55 healthy control(HC) participants and 50 PD patients. Our method's performance was compared to that of random forest (RF) and support vector machine (SVM) classifiers.  Our method achieved an Accuracy, PPV, TPR, and F1 score of {91.7%, 92.8%, 90.6%, 91.7%}, while the RF and SVM achieved {84.5%,84.8%, 82.7%, 83.7%} and {88.7%, 88.0%, 88,7%, 88.3%} respectively on the dataset. 

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

links:
- name: "Paper"
  url: "https://2023.midl.io/papers/s101"
- name: "PDF"
  url: "https://openreview.net/pdf?id=BLWmZy6kSL7"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
