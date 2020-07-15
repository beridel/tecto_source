---
title: "Fast matched-filter (FMF): an efficient seismic matched-filter search for both CPU and GPU architectures"
date: 2017-12-01
publishDate: 2020-07-14T17:59:35.754107Z
authors: ["Eric Beaucé", "wbfrank", "Alexey Romanenko"]
publication_types: ["2"]
abstract: "Matched-filter searches are an important tool in modern seismology to detect seismic events. They operate via an algorithm that computes the correlation coefficient between a template event and a sliding window of continuous seismic records. A detection is recorded when the correlation coefficient crosses an established threshold. We present an optimized program, called Fast Matched Filter (FMF), that efficiently runs a network-based matched-filter search with either central processing units (CPUs) or Nvidia graphics processing units (GPUs). Wrappers for both Python and MATLAB (CPU only) are provided to easily run FMF on a wide range of computational resources, from multicore laptops to specialized computing clusters with GPUs. Both implementations leverage a significantly similar structure when it comes to the continuous computation of correlation coefficients in the time domain to achieve rapid performance. The highly parallel architecture of GPUs lends itself perfectly to the matched-filter algorithm, and we achieve the fastest run times with our GPU implementation. FMF allows for seismic network-based matched-filtering between a large set of template waveforms and a large continuous dataset in a reasonable amount of time. Such fast run times are an important step in expanding the scope of earthquake detection and fostering the reproducibility of such studies."
featured: false
publication: "*Seismological Research Letters*"
doi: "10.1785/0220170181"
url_code: 'https://github.com/beridel/fast_matched_filter'
---

