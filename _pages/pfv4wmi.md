---
title: ""
permalink: /pfv4wmi/
author_profile: true
redirect_from:
  - /pfv4wmi
---

{% include base_path %}

## Probabilistic formal verification of AI/ML systems


### Why?

The pervasiveness of AI systems in our daily lives calls for effective
tools for ensuring their safety, fairness and correctness. While
regulatory bodies are moving the first steps in providing legal
frameworks, the development of the required computational techniques
to enforce them is in its infancy.

### What?

I am focusing the problem of verifying a ML/AI system with respect to
a probabilistic specification:

- a property that should hold with high probability;
- a probabilistic notion of the environment where the system will be deployed.

*For instance, given a population model, we want to make sure that
the ML model used by a bank is not discriminating any category
when deciding who should receive a loan.*

My perspective is property/model-agnostic, trying to unify the
problem under a single formalism. By identifying the factors that
hinder the verification I hope to develop more scalable analysis
techniques, as well as novel ML models that are more easily
verifiable.

### How?

I am investigating the problem under the lenses of Weighted Model Integration (WMI), a relatively recent formalism for probabilistic inference with algebraic and logical constraints.

This formalism enables the verification of many properties of interest, including:

- fairness properties (demographic parity, equality of opportunity, ...);
- distance-based properties (probabilistic robustness, individual fairness, ...);
- other algebraic properties (compliance to physical or safety rules, ...)

over a wide range of ML models, such as: NNs, PGMs, tree-based models, ...


## Resources

I am one of the developers of [SAE4WMI](https://github.com/unitn-sml/wmi-pa "wmi-pa") (formerly WMI-PA), a state-of-the-art solver for WMI.

You can find a preprint of the position paper describing our approach
on [arXiv](https://arxiv.org/abs/2402.04892 "position paper").

<br/><br/>


*[Funded by the European Union](https://cordis.europa.eu/project/id/101110960 "Cordis"). Views and opinions expressed
are however those of the author only and do not necessarily
reflect those of the European Union or The European Research
Executive Agency. Neither the European Union nor the granting
authority can be held responsible for them.
GA n°101110960 “Probabilistic Formal Verification for Provably
Trustworthy AI - PFV-4-PTAI”*