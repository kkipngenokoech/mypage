---
title: "SIMPL: Scalable and hassle-free optimisation of neural representations from behaviour"
date: 2024-10-01
tags: ["latents", "place filds", "grid cells", "tuning curves", "dimensionality reduction"]
author: ["Tom M George", "Pierre Glaser", "Kimberly Stachenfeld", "Caswell Barry", "Claudia Clopath"]
summary: "An efficient technique for optimising tuning curves starting from behaviour by iteratively refitting the tuning curves and redecoding the latent variables." 
cover:
    image: "simpl.gif"
    relative: false
editPost:
    URL: ""
    Text: "unpublished (under review)"

---

![](simpl2.gif)

---

##### Download

+ [bioRxiv](https://www.biorxiv.org/content/10.1101/2024.11.11.623030v1)
+ [Paper](simpl.pdf)
+ [Code and data](https://github.com/TomGeorge1234/SIMPL)

---

##### Abstract

High-dimensional neural activity in the brain is known to encode low-dimensional, time-evolving, behaviour-related variables. A fundamental goal of neural data analysis consists of identifying such variables and their mapping to neural activity. The canonical approach is to assume the latent variables are behaviour and visualize the subsequent tuning curves. However, significant mismatches between behaviour and the encoded variables may still exist --- the agent may be thinking of another location, or be uncertain of its own --- distorting the tuning curves and decreasing their interpretability. To address this issue a variety of methods have been proposed to learn this latent variable in an unsupervised manner; these techniques are typically expensive to train, come with many hyperparameters or scale poorly to large datasets complicating their adoption in practice. To solve these issues we propose SIMPL (Scalable Iterative Maximization of Population-coded Latents), an EM-style algorithm which iteratively optimizes latent variables and tuning curves. SIMPL is fast, scalable and exploits behaviour as an initial condition to further improve convergence and identifiability. We show SIMPL accurately recovers latent variables in biologically-inspired spatial and non-spatial tasks. When applied to a large rodent hippocampal dataset SIMPL efficiently finds a modified latent space with smaller, more numerous, and more uniformly-sized place fields than those based on behaviour, suggesting the brain may encode space with greater resolution than previously thought.

---

##### Citation

George, T. M., Glaser, P., Stachenfeld, K., Barry, C., & Clopath, C. (2024). SIMPL: Scalable and hassle-free optimization of neural representations from behaviour. bioRxiv. doi:10.1101/2024.11.11.623030

```BibTeX
@article {George2024SIMPL,
	author = {George, Tom M and Glaser, Pierre and Stachenfeld, Kimberly and Barry, Caswell and Clopath, Claudia},
	title = {SIMPL: Scalable and hassle-free optimization of neural representations from behaviour},
	elocation-id = {2024.11.11.623030},
	year = {2024},
	doi = {10.1101/2024.11.11.623030},
	publisher = {Cold Spring Harbor Laboratory},
	URL = {https://www.biorxiv.org/content/early/2024/11/12/2024.11.11.623030},
	eprint = {https://www.biorxiv.org/content/early/2024/11/12/2024.11.11.623030.full.pdf},
	journal = {bioRxiv}
}
```

---

##### Related material

+ [Two page summary](cosyne.pdf)
