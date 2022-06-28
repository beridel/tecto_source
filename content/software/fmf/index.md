---
date: "2016-04-27T00:00:00Z"
external_link: ""
image:
  caption: Workflow of the graphics processing unit (GPU) implementation of FMF.
links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/beridel/fast_matched_filter
- icon: newspaper
  icon_pack: far
  name: Article
  url: https://doi.org/10.1785/0220170181

#slides: example
summary: FastMatchedFilter (FMF) - An efficient seismic matched-filter search for both CPU and GPU architectures.
#tags:
#- Deep Learning
title: FastMatchedFilter (FMF)
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
authors:
- wbfrank
- ebeauce
---

Matched-filter searches are an important tool in modern seismology to detect seismic events.
They operate via an algorithm that computes the correlation coefficient between a template event and a sliding window of continuous seismic records.
A detection is recorded when the correlation coefficient crosses an established threshold.
We present an optimized program, called Fast Matched Filter (FMF), that efficiently runs a network-based matched-filter search with either central processing units (CPUs) or Nvidia graphics processing units (GPUs).
Wrappers for both Python and MATLAB (CPU only) are pro- vided to easily run FMF on a wide range of computational resources, from multicore laptops to specialized computing clusters with GPUs.
Both implementations leverage a significantly similar structure when it comes to the continuous com- putation of correlation coefficients in the time domain to achieve rapid performance.
The highly parallel architecture of GPUs lends itself perfectly to the matched-filter algorithm, and we achieve the fastest run times with our GPU implementation.
FMF allows for seismic network-based matched-filtering between a large set of template waveforms and a large continuous dataset in a reasonable amount of time.
Such fast run times are an important step in expanding the scope of earthquake detection and fostering the reproducibility of such studies.

If you use FMF in your own research, please reference the above article.
