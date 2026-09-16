# Convex Hulls of Great Subspheres and Gaussian Minima

**cyclemath — Public Version 0.1 (September 2026)**

This repository contains the public source and PDF of the preliminary research manuscript

> **Convex Hulls of Great Subspheres and Gaussian Minima**

**Edited and released by cyclemath.**

## Overview

Let \(\nu_1,\ldots,\nu_n\in \mathbb S^{d-1}\) be unit normals and let

\[
K=\operatorname{conv}\!\left(\bigcup_{i=1}^n
(\mathbb S^{d-1}\cap \nu_i^\perp)\right).
\]

Thus \(K\) is the convex hull of finitely many great \((d-2)\)-spheres of the unit sphere. In dimension three, these generators are great circles.

For \(G\sim N(0,I_d)\), define the associated Gaussian minimum

\[
M=\min_i |\langle G,\nu_i\rangle|.
\]

The manuscript studies the ordinary Euclidean volume of \(K\) and its relation to this Gaussian minimum, intrinsic volumes, active strata, spherical zones, and Kunisky's Gaussian-minimum conjecture.

## Main results

The principal identity proved in the manuscript is

\[
\operatorname{Vol}_d(K)
=
\kappa_d\bigl(1-\mathbb E M^2\bigr)-R_{n,d},
\qquad
R_{n,d}\ge 0,
\]

where \(\kappa_d=\operatorname{Vol}_d(B^d)\).

The manuscript also establishes:

- the exact second-intrinsic-volume identity
  \[
  V_2(K)=\pi\bigl(d-1-\mathbb E M^2\bigr);
  \]
- an explicit nonnegative active-stratum representation of \(R_{n,d}\) under signed affine general position;
- continuous extension of the total correction to arbitrary configurations;
- exact reduction to the span of the normals, including \(R_{n,d}=0\) whenever the normals span a subspace of dimension at most two;
- in dimension three, an explicit formula valid without general position, including multiple ties: each antipodal pair of positive active polygons of area \(A\) contributes
  \[
  \frac{2A(1-r)^2}{3r},
  \]
  where \(r\) is the circumcircle radius of the active polygon;
- a conditional sharp volume bound from the \(p=2\) part of Kunisky's Gaussian-minimum conjecture.

The equally spaced planar normal configuration attains the corresponding candidate sharp value unconditionally.

## What is not proved

The manuscript does **not** prove:

- Kunisky's Gaussian-minimum conjecture;
- Kunisky's volumetric zone conjecture;
- uniqueness of the volume-maximizing configuration;
- an exhaustive priority or novelty classification of all equivalent formulations in the literature.

The cylindrical / sine-polar description of the polar body is prior work and is not claimed as a new contribution.

## Status and AI assistance

This is an **AI-assisted research manuscript**. Generative AI, principally OpenAI's ChatGPT, was used to carry out a substantial majority of the mathematical exploration, conjecture formation, proof development, proof revision, and reproducible diagnostic checking underlying the manuscript.

**cyclemath formulated and directed the investigation, selected and challenged intermediate claims, requested repeated audits and corrections, and prepared the manuscript for public release.** The designation **“Edited and released by cyclemath”** is intended to record that role without representing the mathematical content as solely or primarily the unaided work of cyclemath.

The mathematical arguments and novelty assessment have **not received independent verification by a subject-matter expert**, and the manuscript has **not undergone peer review**. The results should therefore be read as a public preliminary research record pending independent scrutiny.

## Related formulations and search terms

The same geometry can appear under several related descriptions. Relevant entry points include:

- convex hulls of great circles in \(\mathbb R^3\);
- convex hulls of great subspheres in \(\mathbb R^d\);
- convex hulls of central hyperplane sections of the Euclidean unit ball;
- Gaussian minima and Gaussian minimum optimization;
- intrinsic volumes of convex hulls of central sections;
- active-stratum and Monge--Ampère descriptions of convex hull volume;
- spherical zones and zone-union measure;
- sine polarity and intersections of circular cylinders;
- cosine covariance and Kunisky's conjecture.

These phrases are included to make the mathematical content discoverable under different natural formulations of the same problem.

## Repository contents

- `convex_hulls_great_subspheres_gaussian_minima_v0.1.pdf` — public PDF of the manuscript.
- `convex_hulls_great_subspheres_gaussian_minima_v0.1.tex` — LaTeX source.
- `README.md` — overview, status, and discovery-oriented index.
- `LICENSE` — license information.

Additional computational diagnostics or historical versions may be added separately in later releases.

## Versioning

This repository uses a **public release version** independent of internal drafting numbers.

The first public release is:

> **Version 0.1 — September 2026**

Later substantive corrections can be released as Version 0.2, 0.3, and so on. Earlier public versions should remain archived rather than being silently replaced.

## Archived version and DOI

A Zenodo DOI will be added here after the first archived release is published.

> **Zenodo DOI:** to be added

The GitHub repository is intended to remain the updateable research record; Zenodo will provide fixed, citable snapshots.

## Citation

Until the Zenodo DOI is assigned, the manuscript may be cited as:

> *Convex Hulls of Great Subspheres and Gaussian Minima* (2026). Edited and released by cyclemath. Version 0.1, preliminary AI-assisted research manuscript.

After Zenodo publication, this section will be updated with the DOI.

## License

Unless otherwise stated, the manuscript source, text, and figures in this repository are licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

Reuse is permitted subject to the attribution requirements of that license. Any software or computational code added later may be distributed under a separate software license.
