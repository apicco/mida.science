---
layout: post
title:  "Tracking of endocytic dynamics"
image: /assets/images/Sla1-invagination.png
caption: 
    The inward movement along the plasma membrane invagination axis of 67 Sla1-GFP trajectories. The trajectories are aligned in space and time and averaged using hte trajalign python library. One pixel (pxl) equals 100 nm.
---

Endocytosis is a very dynamic process where a choreography of hundreds of proteins shapes the cell plasma membrane into an invagination from which a vesicle is released. 

Wide-field microscopy images show endocytic events as diffraction-limited spots. The movement of these spots can be easily tracked, but it is too noisy to reliably measure the dynamics of the components of the endocytic machinery. I developed an imaging and data analysis pipeline to use these trajectories to resolve their position and dynamic properties with nm precision.

This method was later used in several publications to characterise the details of the endocytic process, mutations in its machinery, and differences between species.

References:

- [Download and documentation][web]
- [Github repository][github-repo]
- [Picco and Kaksonen, Meth. in Cell Bio., 2017][methods]

- [Picco, Toret, Rivier, and Kaksonen, Biorxiv, 2024][biorxiv-evoendo]
- [Manenschijn, *et al.*, elife, 2019][elife-2019]
- [Picco, Kukulski, *et al.*, MBoC, 2018][mboc]
- [Kukulski, Picco, *et al.*, elife, 2016][elife-2016]
- [Picco, *et al.*, elife, 2015][elife-2015]

[methods]: https://www.sciencedirect.com/science/article/abs/pii/S0091679X16301546
[mboc]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5994895/pdf/mbc-29-1346.pdf
[elife-2015]: https://elifesciences.org/articles/04535
[elife-2016]: https://elifesciences.org/articles/16036
[elife-2019]: https://elifesciences.org/articles/44215
[biorxiv-evoendo]: https://www.biorxiv.org/content/10.1101/2024.03.28.587219v1
[web]: https://apicco.github.io/trajectory_alignment/
[github-repo]: https://github.com/apicco/trajectory_alignment/tree/master?tab=readme-ov-file#trajectory-alignment
