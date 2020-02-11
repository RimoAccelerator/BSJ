---
title: Explicit Solvation and Dynamical Effect
summary: A new dimension for understanding chemical reactions.
tags:
- Explicit Solvation
- Dynamical Effect
date: "2020-02-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Implicit solvation might be misleading
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Inspired by (and under the kind help of) Prof. Singleton (Texas A&M University), Ma's interest turned to advanced chemical theories beyound transition state theory (TST). This field mainly consists of bifurcation, plateu reactions, explicit solvation, etc.

Singleton's work in 2016 has revealed that the regioselectivity of toluene nitration is determined by solvation dynamics. It is the starting point for Ma to get into the field of dynamical effects. In 2019 Ma examined the SNAr reaction between sodium methoxide and 4-nitrobenzonitrile. Although standard DFT calculation under implicit solvation predicted that the reaction would be rapid and complete, the experiments showed rather different results. By using explicit solvation model with 62 solvent (DMSO) molecules, Ma discovered that the free energy surface was greatly modified by the presence of solvents. I.e. implicit solvation model gave totally wrong free energy surface (FES), although DMSO does not directly participate in the reaction Molecular dynamics with explicit solvation gave satisfying explanation for the experimental observations. The modification of FES was attributed to the entropy effect due to solvent dynamics. To the best of Ma's knowledge, it is the first work showing that explicit solvation could significantly modify the FES for small molecular reactions.

Obviously the influence of explicit solvation is rather complex. In the current stage, the only way to account for it is to run molecular dynamics, which is time-consuming. There are two ways to overcome this problem. First, to propose a new theory (or a new semi-emperical model just like implicit solvation used currently) to account for the dynamical effect of solvents. Second, to make DFT calculations 100 times faster.

Besides explicit solvation, Ma is also interested in novelly shaped FES. Bifurcation is the well-known example for this case. However, there are still some other type of FES that could lead to interesting chemical behavior. Ma is trying to find some examples, to show how the curiosity of human can be satisfied by human's intelligence.


