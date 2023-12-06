---
title: "BPMF: A backprojection and matched-filtering workflow for automated earthquake detection and location"
date: 2023-12-04
publishDate: 2023-12-04T17:59:35.749409Z
authors: ["ebeauce", "wbfrank", "lseydoux", "ppoli", "Robert D van der Hilst", "Michel Campillo"]
publication_types: ["2"]
abstract: "We introduce BPMF (backprojection and matched filtering)—a complete and fully automated workflow designed for earthquake detection and location, and distributed in a Python package. This workflow enables the creation of comprehensive earthquake catalogs with low magnitudes of completeness using no or little prior knowledge of the study region. BPMF uses the seismic wavefield backprojection method to construct an initial earthquake catalog that is then densified with matched filtering. BPMF integrates recent machine learning tools to complement physics‐based techniques, and improve the detection and location of earthquakes. In particular, BPMF offers a flexible framework in which machine learning detectors and backprojection can be harmoniously combined, effectively transforming single‐station detectors into multistation detectors. The modularity of BPMF grants users the ability to control the contribution of machine learning tools within the workflow. The computation‐intensive tasks (backprojection and matched filtering) are executed with C and CUDA‐C routines wrapped in Python code. This leveraging of low‐level, fast programming languages and graphic processing unit acceleration enables BPMF to efficiently handle large datasets. Here, we first summarize the methodology and describe the application programming interface. We then illustrate BPMF’s capabilities to characterize microseismicity with a 10 yr long application in the Ridgecrest, California area. Finally, we discuss the workflow’s runtime scaling with numerical resources and its versatility across various tectonic environments and different problems."
featured: false
publication: "*Seismological Research Letters*"
doi: "10.1785/0220230230"
group: tecto
tags:
- detection
- high-performance computing
---

