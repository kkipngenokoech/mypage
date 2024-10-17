---
title: "Reservoir computing for unsupervised chunking of sequential data" 
date: 2021-01-01
tags: ["chunking", "reservoir computing", "sequential data", "unsupervised learning"]
author: ["Tom M George", "Athena Akrami", "Claudia Clopath"]
summary: "We built a reservoir network architecture, based off Asabuki et al. (2018), which can chunk sequential data into meaningful segments without supervision." 
cover:
    image: "schapiro.gif"
    relative: false


---

---

##### Download

+ [Code](https://github.com/TomGeorge1234/ReservoirComputing/)
+ [Slides](rotation.pdf)
---

##### Description

Code for computing with reservoir nets, pairs of mutually supervising reservoir nets and training with FORCE learning. Produced for PhD rotation in Akrami Lab studying temporal structure learning. This is an extension to the work originally produced by Asabuki and Fukai (2018). For the most detailed write up of my work, see finalPresentationSlides.pdf.

There are two main classes at the heart of this project: a reservoir network class which builds a classic rate-based reservoir network which can be trained to match a target function via FORCE learning. A reservoirPair class which pairs two reservoirs and trains them to predict each others output. This was shown by Asabuki and Fukai (2018) to be a good way to learn to perform 'chunking' of repeated stimuli. In this work I extend this showing the architecture and learning rule are capable of a broader class of statistical learning technique. I investigate the mechanisms for how they work include the intruging role of chaotic dynamics.

##### Why

Completed as part of a rotation project with Athena Akrami and Claudia Clopath at the Sainsbury Wellcome Centre. 

---


![](turbulence.gif)

---

##### Citation

George, Tom M., Georgy E. Manucharyan, and Andrew F. Thompson. "Deep learning to infer eddy heat fluxes from sea surface height patterns of mesoscale turbulence." Nature communications 12.1 (2021): 800.

```BibTeX
@article{george2021deep,
  title={Deep learning to infer eddy heat fluxes from sea surface height patterns of mesoscale turbulence},
  author={George, Tom M and Manucharyan, Georgy E and Thompson, Andrew F},
  journal={Nature communications},
  volume={12},
  number={1},
  pages={800},
  year={2021},
  publisher={Nature Publishing Group UK London}
}
```

