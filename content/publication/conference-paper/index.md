---
title: 'Algorithmic Identification of Essential Exogenous Nodes for Causal Sufficiency in Brain Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Abdolmahdi Bagheri
- Mahdi Dehshiri
- Yamin Bagheri
- Alireza Akhondi-Asl
- Babak Nadjar Araabi

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-08'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Submitted to the Medical Image Computing and Computer‑Assisted Intervention"
publication_short: "MICCAI

abstract: In the investigation of any causal mechanisms, such as the brain's causal networks, the assumption of causal sufficiency plays a critical role. Notably, neglecting this assumption can result in significant errors, a fact that is often disregarded in the causal analysis of brain networks. In this study, we propose an algorithmic identification approach for determining essential exogenous nodes that satisfy the critical need for causal sufficiency to adhere to it in such inquiries. Our approach consists of three main steps: First, by capturing the essence of the Peter-Clark (PC) algorithm, we conduct independence tests for pairs of regions within a network, as well as for the same pairs conditioned on nodes from other networks. Next, we distinguish candidate confounders by analyzing the differences between the conditional and unconditional results, using the Kolmogorov-Smirnov test. Subsequently, we utilize Non-Factorized identifiable Variational Autoencoders (NF-iVAE) along with the Correlation Coefficient index (CCI) metric to identify the confounding variables within these candidate nodes. Applying our method to the Human Connectome Projects (HCP) movie-watching task data, we demonstrate that while interactions exist between dorsal and ventral regions, only dorsal regions serve as confounders for the visual networks, and vice versa. These findings align consistently with those resulting from the neuroscientific perspective. Finally, we show the reliability of our results by testing 30 independent runs for NF-iVAE initialization.



# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: ""
#   url: ""

url_pdf: 'https://arxiv.org/pdf/2403.05407.pdf'
url_code: 'https://github.com/mhdehshiri/Algorithmic-Identification-of-Essential-Exogenous-Nodes-for-Causal-Sufficiency-in-Brain-Network'
url_dataset: ''

---
