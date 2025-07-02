---
title: "PhD Thesis: Computational Models of Learning and Representations in the Hippocampal Formation" 
date: 2025-06-25
tags: ["hippocampus","navigation","place cells","grid cells","boundary vector cells","head direction cells","reinforcement learning","neural data","locomotion","synthetic data","Python","open-source","toolkit"]
author: ["Tom M George"]
summary: "My PhD thesis." 
cover:
    image: "thesis_front.png"
    relative: false
# editPost:
#     URL: "https://github.com/RatInABox-Lab/RatInABox"
#     Text: "eLife"

---

+ [Thesis](thesis.pdf)

---

##### Abstract

This thesis explores how neural systems learn and use internal representations to support flexible behaviour, focusing on the mammalian spatial memory system and cognitive map. It introduces new computational tools and biologically plausible models that link neural structure and dynamics to spatial cognition. 
Foundational to this work is RatInABox, an open-source toolkit now widely used for simulating realistic navigation and hippocampal activity. This platform enables the rapid prototyping of models that jointly capture behavioural trajectories and neural representations, including place and grid cells.
The first model leverages this toolkit to demonstrate a biologically plausible mechanism for learning predictive representations via spike-timing dependent plasticity and theta phase precession. This mechanism bridges the timescale gap between behaviour and synaptic plasticity to enable fast and flexible learning.
A second study introduces a generative model of the hippocampal- entorhinal loop that unifies path integration and mental simulation. It shows how local Hebbian learning, scheduled by theta oscillations, can give rise to ring attractor dynamics within a normative Helmholtz machine framework.
The final contribution is SIMPL, an efficient algorithm for latent variable discovery from high-dimensional neural data. By recursively fitting latent trajectories and tuning curves, SIMPL achieves state-of-the-art performance while enhancing the interpretability and precision of neural representations.
Collectively, these contributions advance our understanding of how biological systems learn and represent the world, and provide new models and tools for research at the intersection of neuroscience and artificial intelligence.



<!-- ##### Citation

George, T. M., Rastogi, M., de Cothi, W., Clopath, C., Stachenfeld, K., & Barry, C. (2024). RatInABox, a toolkit for modelling locomotion and neuronal activity in continuous environments. Elife, 13, e85274.

```BibTeX
@article{george2024ratinabox,
  title={RatInABox, a toolkit for modelling locomotion and neuronal activity in continuous environments},
  author={George, Tom M and Rastogi, Mehul and de Cothi, William and Clopath, Claudia and Stachenfeld, Kimberly and Barry, Caswell},
  journal={Elife},
  volume={13},
  pages={e85274},
  year={2024},
  publisher={eLife Sciences Publications Limited}
}
``` -->

