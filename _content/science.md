---
layout: default
title: Science
key: science
permalink: /science/
---
# Science
Many challenging diseases such as cancer, neurodegeneration, and viral infections involve intrinsically disordered proteins (IDPs), deemed ‘undruggable’ due to their dynamic nature and lack of stable binding sites (**Figure 1**). We believe the main barrier to drugging IDPs is the lack of tools and datasets. Our mission is to make all IDPs druggable by 1) developing new tools and 2) screening millions of IDP/drug-molecule pairs to build an unprecedented public dataset. These resources will enable the prediction and rational design of therapeutic binders.

<figure>
    <img src="{{ site.baseurl }}/assets/images/static-vs-dynamic-lock-key-small-v2.svg" class="center" style="width: 100%" />
    <figcaption>
        <b>Figure 1:</b> Structured proteins and IDPs. Drug development typically focuses on interactions between small molecules and structured proteins (65% of the human proteome). However, IDPs (35%) lack stable binding sites for small molecules and are highly dynamic, rapidly shifting between states. While IDPs can bind small molecules, these interactions remain poorly understood and differ from traditional drug binding. Our goal is to make IDPs druggable by delivering tools and datasets.
    </figcaption>
</figure>

## The Lock-and-Key Paradigm for Folded Proteins
Small-molecule interactions with proteins are essential for biological processes like signalling, metabolism, and drug action. However, most understanding is limited to small-molecule binding to structured proteins (**Figure 1**, left), where the molecules (grey) fit into well-defined binding pockets, like keys into locks. Although some small-molecule binding occurs through an ‘induced fit’ mechanism, modern drug discovery largely relies on the presence of stable binding pockets in deep protein grooves. 

<figure>
    <img src="{{ site.baseurl }}/assets/images/deaths-idps-dim-25-short-v2.svg" class="center" style="width: 100%" />
    <figcaption>
        <b>Figure 2:</b> Leading causes of death on a global level. IDPs are implicated in all highlighted diseases.
    </figcaption>
</figure>

## Current Research Progress
### Unlocking new paradigms for IDPs
IDPs comprise ~35% of the human proteome, and play crucial roles in diseases including cancer, cardiovascular disease, neurodegeneration, and infection (**Figure 2**)[^dattani2023]. Despite their importance, their dynamic nature and lack of stable binding pockets (**Figure 1**, right) have led to the perception of IDPs as 'undruggable.' However, researchers have shown that IDPs can bind to small molecules, revealing novel interaction mechanisms[^heller2017]<sup>,</sup>[^heller2024]<sup>,</sup>[^robustelli2022]<sup>,</sup>[^zhu2022]<sup>,</sup>[^heller2020]<sup>,</sup>[^lohr2021] which in turn have also led to renewed drug development interest (Peptone, Nuage Therapeutics, Transition Bio, Dewpoint Therapeutics, and others).

This adds to the growing body of evidence that these mechanisms differ significantly from traditional ‘lock-and-key’ binding[^xu2022]<sup>,</sup>[^zhao2021]<sup>,</sup>[^ban2017]<sup>,</sup>[^iconaru2016]<sup>,</sup>[^iconaru2021]<sup>,</sup>[^damol2016]<sup>,</sup>[^tatenhorst2016]<sup>,</sup>[^hammoudeh2009]. In bound states, it is possible for both the small molecule and the IDP to remain highly dynamic, which may cause existing techniques to miss these interactions.

## Research Gap 
### State-of-the-art drug discovery
For folded proteins, highly optimised computational and experimental workflows exist to discover new drugs. For example, ‘docking’ is a computational method where small molecules are fit into static protein binding pockets and scored based on simulated interactions. Experimentally, X-ray crystallography provides atomistic details of small-molecule interactions with a static protein target, enabling rapid drug development. Most small molecules that have been identified to interact with IDPs to date have been discovered by chance through specific functional assays, which cannot be generalised to other IDPs. Thus, these approaches require extensive a priori knowledge of the target’s function, which is challenging for multi-functional IDPs with numerous binding partners[^holehouse2024].
Industrial drug discovery programs typically follow a design-make-test-analyse (DMTA) cycle before becoming a drug candidate (**Figure 3**, top). This process has become highly efficient due to advances in computational design, synthesis procedures, and testing techniques.

<figure>
    <img src="{{ site.baseurl }}/assets/images/dmta-struc-idp-v2.svg" class="center" style="width: 100%" />
    <figcaption>
        <b>Figure 3:</b> Current limitations of screening for IDP binders. A typical drug discovery pipeline (top) starts with target identification, followed by screening a large small-molecule library to find a ‘hit’. Hits require significant chemical modifications or even complete redesigns to become viable drugs, refined through a DMTA cycle where molecules are designed, synthesised, tested, and analysed. For IDPs (bottom) critical tools for hit identification, testing, and computational design and analysis are lacking. Bind will fill this technological gap.
    </figcaption>
</figure>

## Our Scientific Approach
Both drug design and testing stages are highly optimised for structured proteins but generally unsuitable for IDPs (**Figure 3**, bottom) due to the lack of tools for their highly dynamic nature, both experimentally (*in vitro*, in-cell) and computationally. This has created a data void, hindering the development of computational models.
At Bind, we will focus on three scientific pillars to enable drug discovery for IDPs: in-cell experiments, experimental biophysics, and computation (**Figure 4**). These approaches provide the disease context and atomistic detail needed for rational drug design, with artificial intelligence (AI) playing key roles in all three pillars. Existing tools for studying binding between drug-like molecules and IDPs are limited and often system-specific. We eventually aim to create general tools for any IDP target and increase their throughput by several orders of magnitude to support translational drug discovery.

<figure>
    <img src="{{ site.baseurl }}/assets/images/gears-horiz.svg" class="center" style="width: 100%" />
    <figcaption>
        <b>Figure 4:</b> In-cell, biophysical, and computational methods will allow us to screen many interactions and deeply characterise interactions with atomic-level resolution. This will produce a rich, publicly available dataset, helping us and others to drug IDPs. 
    </figcaption>
</figure>

## References
[^dattani2023]: [Dattani et al., “Causes of Death”, 2023](https://ourworldindata.org/causes-of-death)
[^heller2017]: [Heller et al., JMB, 2017](https://doi.org/10.1016/j.jmb.2017.07.016)
[^heller2024]: [Heller et al. JACS, 2024](https://doi.org/10.1021/jacs.3c11614)
[^robustelli2022]: [Robustelli et al., JACS, 2022](https://doi.org/10.1021/jacs.1c07591)
[^zhu2022]: [Zhu et al., Nat. Comms., 2022](https://doi.org/10.1038/s41467-022-34077-z)
[^heller2020]: [Heller et al., Sci. Advances, 2020](https://doi.org/10.1126/sciadv.abb5924)
[^lohr2021]: [Löhr, et al., ACS Chemical Neuroscience, 2021](https://doi.org/10.1021/acschemneuro.2c00116)
[^xu2022]: [Xu et al., Nat. Comms, 2022](https://doi.org/10.1038/s41467-022-28660-7)
[^zhao2021]: [Zhao et al., Nat. Comms, 2021](https://doi.org/10.1038/s41467-021-21258-5)
[^ban2017]: [Ban et al., JACS, 2017](https://doi.org/10.1021/jacs.7b01380)
[^iconaru2016]: [Iconaru et al., Sci Reports, 2016](https://doi.org/10.1038/srep39732)
[^iconaru2021]: [Iconaru et al., JMB, 2021](https://doi.org/10.1016/j.jmb.2021.167120)
[^damol2016]: [Da Mol et al., ACS Chem Bio, 2016](https://doi.org/10.1021/acschembio.6b00182)
[^tatenhorst2016]: [Tatenhorst et al., Acta Neuro. Comm., 2016](https://doi.org/10.1186/s40478-016-0310-y)
[^hammoudeh2009]: [Hammoudeh et al., JACS, 2009](https://doi.org/10.1021/ja900616b)
[^holehouse2024]: [Holehouse et al., Nat Rev Mol Cell Biol, 2024](https://doi.org/10.1038/s41580-023-00673-0)