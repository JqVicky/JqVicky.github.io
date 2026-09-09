---
layout: bibtex
permalink: /26-meta-dep-ci/
---

```
@InProceedings{pmlr-v337-mazaheri26a,
  title = 	 {Meta-Dependence in Conditional Independence Testing},
  author =       {Mazaheri, Bijan and Zhang, Jiaqi and Uhler, Caroline},
  booktitle = 	 {Proceedings of the 42nd Conference on Uncertainty in Artificial Intelligence},
  pages = 	 {4427--4440},
  year = 	 {2026},
  editor = 	 {Perković, Emilija and Malinsky, Daniel},
  volume = 	 {337},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {17--21 Aug},
  publisher =    {PMLR},
  pdf = 	 {https://raw.githubusercontent.com/mlresearch/v337/main/assets/mazaheri26a/mazaheri26a.pdf},
  url = 	 {https://proceedings.mlr.press/v337/mazaheri26a.html},
  abstract = 	 {Conditional independence testing is a critical component of feature screening, invariant statistical models, and causal discovery. Many of these algorithms rely on the sequential application of conditional independence tests, and their stability hinges on how their outcomes interact. We study this "meta-dependence" between conditional independence properties using the following geometric intuition: satisfying each conditional independence property constrains the space of possible joint distributions to a manifold. The "meta-dependence" of multiple conditional independences in a probability distribution is informed by its position relative to these manifolds. We provide a simple-to-compute measure of this meta-dependence using moment projections, with a closed-form expression for multivariate {Gaussian} distributions, and consolidate our findings empirically using both synthetic and real-world data. Our measure of meta-dependence does not rely on graphical properties of the distribution and can be computed directly from summary statistics such as a covariance matrix, allowing for various applications. We demonstrate one use case of meta-dependence, using a simple redundancy metric to tune significance thresholds and improve causal discovery.}
}
```
