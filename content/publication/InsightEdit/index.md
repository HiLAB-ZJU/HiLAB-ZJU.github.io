---
title: "InsightEdit: Towards Better Instruction Following for Image Editing "
authors:
- 徐荥璟
- Jie Kong
- Jiazhi Wang
- Xiao Pan
- 林博
- Qiang Liu
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'  
#   - 'Equal contribution'

date: "2024-11-26T00:00:00Z"
doi: "https://arxiv.org/abs/2411.17323"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-17T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "The IEEE/CVF Conference on Computer Vision and Pattern Recognition 2025"
publication_short: "CVPR 2025"

abstract: In this paper, we focus on the task of instruction-based image editing. Previous works like InstructPix2Pix, InstructDiffusion, and SmartEdit have explored end-to-end editing. However, two limitations still remain:First, existing datasets suffer from low resolution, poor backgroundconsistency, and overly simplistic instructions. Second,current approaches mainly condition on the text while the rich image information is underexplored, therefore inferior in complex instruction following and maintaining background consistency. Targeting these issues, we first curated the AdvancedEdit dataset using a novel data construction pipeline, formulating a large-scale dataset with high visual quality, complex instructions, and good background consistency. Then, to further inject the rich image information, we introduce a two-stream bridging mechanism utilizing both the textual and visual features reasoned by the powerful Multimodal Large Language Models (MLLM) to guide the image editing process more precisely. Extensive results demonstrate that our approach, InsightEdit, achieves state-of-the-art performance, excelling in complex instruction following and maintaining high backgroundconsistency with the original image. The project page is https://poppyxu.github.io/InsightEdit web/.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- CCF-A
# featured: false

links:
- name: "Paper"
  url: https://arxiv.org/abs/2411.17323
- name: "PDF"
  url: https://arxiv.org/pdf/2411.17323
- name: "Code"
  url: 'https://github.com/poppyxu/InsightEdit'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
