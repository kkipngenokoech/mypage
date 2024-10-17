---
title: "Unsupervised machine learning for data encoding applied to ovarian cancer transcriptomes" 
date: 2019-11-26
tags: ["machine learning","variational autoencoders","cancer","transcriptomics"]
author: ["Tom M George","Syed Haider", "Pietro Lio"]
description: "We use variational autoencoders to compressed ovarian cancer transcriptomes and extract genetic markers predictive of chemotherapy resistance."
summary: "We use variational autoencoders to compressed ovarian cancer transcriptomes and extract genetic markers predictive of chemotherapy resistance." 
cover:
    relative: false
---

---

##### Download
+ [Paper](ovaerian.pdf)
+ [bioRxiv](https://www.biorxiv.org/content/10.1101/855593v1)
+ [MSc Thesis](PartIIIProject.pdf)
+ [Code and data](https://github.com/TomGeorge1234/oVAErian-Cancer)

---

##### Abstract

Machine learning algorithms are revolutionising how information can be extracted from complex and high-dimensional data sets via intelligent compression. For example, unsupervised autoencoders train a deep neural network with a low-dimensional “bottlenecked” central layer to reconstruct input vectors. Variational Autoencoders (VAEs) have shown promise at learning meaningful latent spaces for text, image and more recently, gene-expression data. In the latter case they have been shown capable of capturing biologically relevant features such as a patients sex or tumour type. Here we train a VAE on ovarian cancer transcriptomes from The Cancer Genome Atlas and show that, in many cases, the latent spaces learns an encoding predictive of cisplatin chemotherapy resistance. We analyse the eﬀectiveness of such an architecture to a wide range of hyperparameters as well as use a state-of-the-art clustering algorithm, t-SNE, to embed the data in a two-dimensional manifold and visualise the predictive power of the trained latent spaces. By correlating genes to resistance-predictive encodings we are able to extract biological processes likely responsible for platinum resistance. Finally we demonstrate that variational autoencoders can reliably encode gene expression data contaminated with significant amounts of Gaussian and dropout noise, a necessary feature if this technique is to be applicable to other data sets, including those in non-medical fields.

---

##### Citation

George, Tom M., and Pietro Lio. "Unsupervised machine learning for data encoding applied to ovarian cancer transcriptomes." bioRxiv (2019): 855593.

```BibTeX
@article{george2019unsupervised,
  title={Unsupervised machine learning for data encoding applied to ovarian cancer transcriptomes},
  author={George, Tom M and Lio, Pietro},
  journal={bioRxiv},
  pages={855593},
  year={2019},
  publisher={Cold Spring Harbor Laboratory}
}
```

---
