---
layout: bibtex
permalink: /26-gas/
---

```
@InProceedings{pmlr-v300-mones26a,
  title = 	 { On the Number of Conditional Independence Tests in Constraint-based Causal Discovery },
  author =       {Mon{\'e}s, Marc Franquesa and Zhang, Jiaqi and Uhler, Caroline},
  booktitle = 	 {Proceedings of The 29th International Conference on Artificial Intelligence and Statistics},
  pages = 	 {1981--1989},
  year = 	 {2026},
  editor = 	 {Khan, Emtiyaz and Li, Yingzhen and Solin, Arno and Ramdas, Aaditya},
  volume = 	 {300},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {02--05 May},
  publisher =    {PMLR},
  pdf = 	 {https://raw.githubusercontent.com/mlresearch/v300/main/assets/mones26a/mones26a.pdf},
  url = 	 {https://proceedings.mlr.press/v300/mones26a.html},
  abstract = 	 { Learning causal relations from observational data is a fundamental problem with wide-ranging applications across many fields. Constraint-based methods infer the underlying causal structure by performing conditional independence tests. However, existing algorithms such as the prominent PC algorithm need to perform a large number of independence tests, which in the worst case is exponential in the maximum degree of the causal graph. Despite extensive research, it remains unclear if there exist algorithms with better complexity without additional assumptions. Here, we establish an algorithm that achieves a better complexity of $p^{\mathcal{O}(s)}$ tests, where $p$ is the number of nodes in the graph and $s$ denotes the maximum undirected clique size of the underlying essential graph. Complementing this result, we prove that any constraint-based algorithm must perform at least $2^{\Omega(s)}$ conditional independence tests, establishing that our proposed algorithm achieves exponent-optimality up to a logarithmic factor in terms of the number of conditional independence tests needed. Finally, we validate our theoretical findings through simulations, on semi-synthetic gene-expression data, and real-world data, demonstrating the efficiency of our algorithm compared to existing methods in terms of number of conditional independence tests needed. }
}
```
