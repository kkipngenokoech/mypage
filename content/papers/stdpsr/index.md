---
title: "Rapid learning of predictive maps with STDP and theta phase precession" 
date: 2023-03-16
tags: ["stdp","reinforcement learning","hippocampus","successor representations"]
author: ["Tom M George","William de Cothi", "Kimberly Stachenfeld", "Caswell Barry"]
summary: "We study how successor representations can be learned in a biologically plausible way by hippocampal neurons using STDP and theta phase procession." 
cover:
    image: "stdpsr.gif"
    relative: false
editPost:
    URL: "https://elifesciences.org/articles/80663"
    Text: "eLife"

---

---

##### Download

+ [Paper](stdpsr.pdf)
+ [eLife](https://elifesciences.org/articles/80663)
+ Reviewer responses [1](response1.pdf) [2](response2.pdf) 
+ [Code and data](https://github.com/TomGeorge1234/STDP-SR/tree/main)

---

##### Abstract

The predictive map hypothesis is a promising candidate principle for hippocampal function. A favoured formalisation of this hypothesis, called the successor representation, proposes that each place cell encodes the expected state occupancy of its target location in the near future. This predictive framework is supported by behavioural as well as electrophysiological evidence and has desirable consequences for both the generalisability and efficiency of reinforcement learning algorithms. However, it is unclear how the successor representation might be learnt in the brain. Error-­driven temporal difference learning, commonly used to learn successor representations in artificial agents, is not known to be implemented in hippocampal networks. Instead, we demonstrate that spike-­ timing dependent plasticity (STDP), a form of Hebbian learning, acting on temporally compressed trajectories known as ‘theta sweeps’, is sufficient to rapidly learn a close approximation to the successor representation. The model is biologically plausible – it uses spiking neurons modulated by theta-­ band oscillations, diffuse and overlapping place cell-­ like state representations, and experimentally matched parameters. We show how this model maps onto known aspects of hippocampal circuitry and explains substantial variance in the temporal difference successor matrix, consequently giving rise to place cells that demonstrate experimentally observed successor representation-­related phenomena including backwards expansion on a 1D track and elongation near walls in 2D. Finally, our model provides insight into the observed topographical ordering of place field sizes along the dorsal-­ ventral axis by showing this is necessary to prevent the detrimental mixing of larger place fields, which encode longer timescale successor representations, with more fine-­grained predictions of spatial location.

---

![](stdpsr.gif)

---

##### Citation

George, T. M., de Cothi, W., Stachenfeld, K. L., & Barry, C. (2023). Rapid learning of predictive maps with STDP and theta phase precession. Elife, 12, e80663.

```BibTeX
@article{george2023stdpsr,
  title={Rapid learning of predictive maps with STDP and theta phase precession},
  author={George, Tom M and de Cothi, William and Stachenfeld, Kimberly L and Barry, Caswell},
  journal={Elife},
  volume={12},
  pages={e80663},
  year={2023},
  publisher={eLife Sciences Publications Limited}
}
```

---

##### Related material

This paper was published concurrent with two other related studies: 
+ [Bono, J., Zannone, S., Pedrosa, V., & Clopath, C. (2023). Learning predictive cognitive maps with spiking neurons during behavior and replays. Elife, 12, e80671.](https://elifesciences.org/articles/80671)
+ [Fang, C., Aronov, D., Abbott, L. F., & Mackevicius, E. L. (2023). Neural learning rules for generating flexible predictions and computing the successor representation. elife, 12, e80680.](https://elifesciences.org/articles/80680)

--- 

##### Related material 

+ [Cosyne abstract (2-page summary)](cosyne_stdpsr.pdf)
+ [Cosyne poster](cosyneposter_stdpsr.pdf)