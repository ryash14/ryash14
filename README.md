<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./header.svg">
  <source media="(prefers-color-scheme: light)" srcset="./header-light.svg">
  <img src="./header.svg" width="100%" alt="Yashwanth Reddy Reddygari">
</picture>

<br>

```yaml
role      :  Applied AI Intern  ·  DRDO (DLRL), Hyderabad
prev      :  Research Intern    ·  ISRO-NRSC
domain    :  retrieval systems · geospatial ML · offline AI infrastructure
condition :  most interesting problems involve something missing
```

<br>

The thread across most of my work is absence — missing satellite passes, missing connectivity,
missing ground truth. At DRDO, that meant an end-to-end RAG pipeline running on local models
inside an air-gapped facility. At ISRO-NRSC, it meant reconstructing ocean surface observations
from incomplete satellite data using DINEOF — a matrix factorization technique borrowed from
climate science.

The constraint always came before the architecture.

<br>

---

<br>

## Selected Work

<br>

<table>
<tr>
<td width="48%" valign="top">

**Offline RAG System** &nbsp;&nbsp;<sup>`DRDO · DLRL`</sup>

End-to-end retrieval-augmented generation in a restricted, air-gapped facility. No external APIs. No cloud inference. Custom retrieval stack on locally hosted models. Every design decision had to survive an environment where network assumptions don't hold.

</td>
<td width="4%"></td>
<td width="48%" valign="top">

**Satellite Gap Reconstruction** &nbsp;&nbsp;<sup>`ISRO · NRSC`</sup>

Missing observations in oceanographic satellite data, reconstructed using DINEOF. The requirement wasn't statistical plausibility — it was physical coherence with the underlying ocean dynamics. Worked across atmospheric and sea-surface temperature datasets.

</td>
</tr>

<tr><td colspan="3"><br></td></tr>

<tr>
<td width="48%" valign="top">

**SyncRoute**

Route optimization with real-time constraint handling. The non-trivial part is the scheduling layer — how constraints propagate dynamically, not naive graph traversal on a fixed graph.

</td>
<td width="4%"></td>
<td width="48%" valign="top">

**LearnityX**

Adaptive learning system. The inference architecture is the part worth examining — how personalization signals are weighted over time, not how content is presented on screen.

</td>
</tr>
</table>

<br>

---

<br>

## What I keep returning to

<br>

> Most of what gets called "ML engineering" is data pipeline work that nobody writes papers about.

<br>

> The gap between what geospatial ML benchmarks report and what real satellite data supports is larger than most research acknowledges.

<br>

> Offline-first AI infrastructure isn't a niche constraint. It's a design philosophy worth imposing from day one, not retrofitting later.

<br>

> Retrieval systems should degrade predictably when context quality drops. Most don't.

<br>

---

<br>

<div align="center">

[LinkedIn](https://linkedin.com/in/yashwanthreddyreddygari) &nbsp;&nbsp;·&nbsp;&nbsp; [Email](mailto:your@email.com)

<br>

<sub>If something here overlaps with what you're working on — reach out.</sub>

</div>
