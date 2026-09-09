---
layout: bibtex
permalink: /26-faithful-int-only/
---

```
@InProceedings{pmlr-v337-mazaheri26b,
  title = 	 {Relaxing Faithfulness with Intervention-Only Causal Discovery},
  author =       {Mazaheri, Bijan and Zhang, Jiaqi and Uhler, Caroline},
  booktitle = 	 {Proceedings of the 42nd Conference on Uncertainty in Artificial Intelligence},
  pages = 	 {4441--4456},
  year = 	 {2026},
  editor = 	 {Perković, Emilija and Malinsky, Daniel},
  volume = 	 {337},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {17--21 Aug},
  publisher =    {PMLR},
  pdf = 	 {https://raw.githubusercontent.com/mlresearch/v337/main/assets/mazaheri26b/mazaheri26b.pdf},
  url = 	 {https://proceedings.mlr.press/v337/mazaheri26b.html},
  abstract = 	 {Causal discovery algorithms learn a network that describes the causal dependencies among random variables. A common workflow involves first utilizing conditional independence properties on observational data to determine partially directed causal relationships, then applying interventions to orient the unknown causal directions. A critical assumption for the first step is faithfulness: a requirement that causally linked variables exhibit statistical dependence. Many natural systems include buffering and stabilizing pathways that cancel out to achieve systemic robustness. This cancellation of pathways violates faithfulness, leading causal discovery algorithms to incorrectly remove causal dependencies. In this paper, we argue that hard interventions contain information about the presence/absence of causal linkage that is overlooked in the first stage of structure discovery. We show that a mild assumption — called intervention-immediacy faithfulness — that allows cancellations, is sufficient to nonparametrically identify causal structures with hard interventions. These results position interventions as the primary carriers of information about causal structure, which should take precedence over conditional independence testing. To flip the paradigm, we also specify equivalence classes when the identification criteria are not met due to limitations in the scope of interventions.}
}
```
