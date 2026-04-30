---
permalink: /research/
title: "Research"
author_profile: true
---

Machine learning in stellar spectroscopy
======

A major part of my research is employing machine-learning methods to infer stellar parameters and chemical abundances from spectra, especially in crowded stellar fields where traditional fibre-fed spectrographs are limited. 
I have shown that MUSE integral-field spectroscopy, despite its moderate spectral resolution, can be used to measure reliable stellar abundances for individual stars when combined with data-driven and theoretical spectral models (e.g., Data-Driven Payne).
This work opens a new pathway for Galactic archaeology in dense environments such as the Galactic bulge, globular clusters, and nearby galaxies.

Key paper:

- **Wang et al. 2022**, *Reliable stellar abundances of individual stars with the MUSE integral-field spectrograph*, MNRAS, 514, 1034 — [NASA ADS](https://ui.adsabs.harvard.edu/abs/2022MNRAS.514.1034W/abstract)
  
![Comparison between an observed MUSE spectrum and a DD-Payne model prediction]({{ "zixianwang/images/wang2022_fig3.jpg" | relative_url }})

*This figure shows an example MUSE spectrum compared with a model prediction from a neural network model _Data-Driven Payne_ ([Xiang et al. 2019](https://ui.adsabs.harvard.edu/abs/2019ApJS..245...34X/abstract)). The small residuals demonstrate that the machine-learning model can reproduce MUSE spectra well, including the absorption features used for abundance measurements.*

Globular clusters
======

I study globular clusters as dense stellar systems that preserve information about star formation, chemical enrichment, and the early assembly history of galaxies. 
Much of my recent work focuses on Omega Centauri, one of the most complex stellar systems in the Milky Way and a possible stripped nuclear star cluster.

Using MUSE spectroscopy, I have investigated chemical abundances, multiple stellar populations, sodium absorption, interstellar and intracluster medium, and the broader enrichment history of Omega Centauri. 
These studies use large spectroscopic samples to connect stellar chemistry, kinematics, and cluster formation history.

Key papers:

- **Wang et al. 2025**, *oMEGACat. VII. Tracing Interstellar and Intracluster Medium of ω Centauri using Sodium Absorptions*, ApJ, 994, 143 — [NASA ADS](https://ui.adsabs.harvard.edu/abs/2025ApJ...994..143W/abstract)
- **Wang et al. 2026**, *oMEGACat. IX. Chemical Tagging of Omega Centauri Populations with Machine-Learning-Inferred Abundances from the MUSE Spectrograph*, arXiv:2603.01041, submitted to ApJ — [NASA ADS](https://ui.adsabs.harvard.edu/abs/2026arXiv260301041W/abstract)

![Foreground and intracluster Na absorption toward Omega Centauri]({{ "zixianwang/images/wang2025_fig.jpg" | relative_url }})

*This figure summarises the Na absorption analysis from **Wang et al. 2025, oMEGACat VII**. The left panel shows the spatial distribution of foreground Na atomic gas toward ω Centauri, measured from Voronoi-binned MUSE spectra. The clear spatial substructure is consistent with previously measured differential reddening across the cluster field. The right panel shows the stacked spectrum of hot horizontal-branch stars used to search for Na I D absorption from intracluster gas in ω Centauri. No significant intracluster Na atomic gas is detected from the D1 absorption line.*

![Chromosome diagram of Omega Centauri stars from oMEGACat DD-Payne abundances]({{ "zixianwang/images/wang2026_fig6.jpg" | relative_url }})

*This figure shows the chromosome diagram of ω Centauri stars from **Wang et al. 2026, oMEGACat IX** measured from MUSE spectra. The top-left panel shows individual oMEGACat DD-Payne stars colour-coded by metallicity, while the other panels show median chemical abundances across the diagram. The figure highlights how different stellar streams in ω Centauri separate in chemical-abundance space, providing a powerful way to chemically tag multiple stellar populations in the cluster.*

Galactic bulge
======

The Galactic bulge is one of the most important regions for understanding the formation history of the Milky Way. 
However, it is also difficult to study because of crowding, extinction, and the challenge of obtaining reliable ages for stars in the inner Galaxy.

I led a deep VLT/MUSE program targeting a low-extinction field in the inner Milky Way (Baade's window). 
This work directly detects main-sequence turn-off stars in the Galactic bulge, which are among the most reliable stellar age tracers. 
By combining ages, chemistry, and kinematics, this project provides a new observational window into the formation history and chemo-dynamical structure of the inner Galaxy.

Key paper:

- **Wang et al. 2025**, *Age, Chemistry, and Kinematics of the Inner Galaxy Revealed by MUSE*, arXiv:2512.09527, submitted to Nature Astronomy — [NASA ADS](https://ui.adsabs.harvard.edu/abs/2025arXiv251209527W/abstract)
  
![MUSE observations and age distribution of inner Milky Way stars]({{ "zixianwang/images/wang2025na_fig.jpg" | relative_url }})

*This figure summarises the MUSE study of Baade’s Window from **Wang et al. 2025**, submitted to *Nature Astronomy*. The left panel shows the MUSE field of view, with main-sequence turn-off/subgiant stars and giant stars in the inner Milky Way highlighted. The right panel shows the age distribution of the 98 main-sequence turn-off/subgiant stars, with Gaussian mixture model peaks indicating multiple stellar age populations in the inner Galaxy.*

Linking Galactic and extragalactic
======

A central goal of my research is to connect detailed studies of the Milky Way with observations of external galaxies. 
The Milky Way can be studied star by star, while external galaxies are usually observed through integrated light. This difference makes direct comparison difficult.

To address this, I developed **GalCraft**, a forward-modelling framework that generates mock integral-field spectroscopic observations of Milky Way-like galaxies. 
GalCraft allows Milky Way models to be “observed” as if they were external galaxies, enabling the same analysis tools to be applied to both mock Milky Way observations and real galaxy data. 
This provides a way to validate full-spectrum fitting methods and to place the Milky Way and external galaxies on the same observational footing.

This work supports broader efforts in surveys such as GECKOS to understand galaxy evolution by combining Galactic archaeology, stellar population modelling, and integral-field spectroscopy.

Key paper:

- **Wang et al. 2024**, *Validating full-spectrum fitting with a synthetic integral-field spectroscopic observation of the Milky Way*, MNRAS, 534, 1175 — [NASA ADS](https://ui.adsabs.harvard.edu/abs/2024MNRAS.534.1175W/abstract)
  
<!-- Plot placeholder:
Add figure showing GalCraft workflow, mock Milky Way IFS cube, or Milky Way-external galaxy comparison.

Example:
![GalCraft and Galactic-extragalactic connection](/images/research/galcraft.png)
-->
