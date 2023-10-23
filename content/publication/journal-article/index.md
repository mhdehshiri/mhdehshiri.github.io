---
title: "Brain effective connectome based on fMRI and DTI data: Bayesian causal learning and assessment"
authors:
- Abdolmahdi Bagheri
- Mahdi Dehshiri
- Yamin Bagheri
-  Alireza Akhondi-Asl
-  Babak Nadjar Araabi
date: "2023-08-18"
doi: "https://doi.org/10.1371/journal.pone.0289406"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-18"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Public Library of Science San Francisco, CA USA"
publication_short: "PLOS ONE"

abstract: Neuroscientific studies aim to find an accurate and reliable brain Effective Connectome (EC). Although current EC discovery methods have contributed to our understanding of brain organization, their performances are severely constrained by the short sample size and poor temporal resolution of fMRI data, and high dimensionality of the brain connectome. By leveraging the DTI data as prior knowledge, we introduce two Bayesian causal discovery frameworks -the Bayesian GOLEM (BGOLEM) and Bayesian FGES (BFGES) methods- that offer significantly more accurate and reliable ECs and address the shortcomings of the existing causal discovery methods in discovering ECs based on only fMRI data. Moreover, to numerically assess the improvement in the accuracy of ECs with our method on empirical data, we introduce the Pseudo False Discovery Rate (PFDR) as a new computational accuracy metric for causal discovery in the brain. Through a series of simulation studies on synthetic and hybrid data (combining DTI from the Human Connectome Project (HCP) subjects and synthetic fMRI), we demonstrate the effectiveness of our proposed methods and the reliability of the introduced metric in discovering ECs. By employing the PFDR metric, we show that our Bayesian methods lead to significantly more accurate results compared to the traditional methods when applied to the Human Connectome Project (HCP) data. Additionally, we measure the reproducibility of discovered ECs using the Rogers-Tanimoto index for test-retest data and show that our Bayesian methods provide significantly more reliable ECs than traditional methods. Overall, our study’s numerical and visual results highlight the potential for these frameworks to significantly advance our understanding of brain functionality.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0289406
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
