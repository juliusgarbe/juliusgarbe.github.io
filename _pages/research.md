---
permalink: /research/
title: "Research"
#excerpt: "More about my research, research interests and models I'm currently working with."
header:
  overlay_image: header/header1.jpg
  overlay_filter: 0.2 # same as adding an opacity of 0.2 to a black background
  caption: "Photo: J. Garbe"
author_profile: true
redirect_from: 
  - 
---

{% include base_path %}

{% include toc title="Jump to" icon="fas fa-file-alt" %}

## Research Interests
- Numerical ice sheet modeling (<i class="fas fa-arrow-circle-right"></i> co-development of [PISM](/research/#parallel-ice-sheet-model-pism "/research/#parallel-ice-sheet-model-pism"))
- Antarctic Ice Sheet stability and future sea-level rise (<i class="fas fa-arrow-circle-right"></i> e.g., [Hill et al., 2023](/publications/articles/hill-2023 "/publications/articles/hill-2023"); [Reese et al., 2023](/publications/articles/reese-2023 "/publications/articles/reese-2023"); [Bauer et al., 2023](/publications/articles/bauer-2023 "/publications/articles/bauer-2023"))
- Tipping points and hysteresis behavior of the Antarctic Ice Sheet (<i class="fas fa-arrow-circle-right"></i> e.g., [Garbe et al., 2020](/publications/articles/garbe-2020 "/publications/articles/garbe-2020"); [Chandler et al., 2025](/publications/preprints/chandler-2025 "/publications/preprints/chandler-2025"))
- Surface melting in Antarctica (<i class="fas fa-arrow-circle-right"></i> [Garbe et al., 2023](/publications/articles/garbe-2023 "/publications/articles/garbe-2023"))
- Climate and socio-economic tipping interactions (<i class="fas fa-arrow-circle-right"></i> [DominoES](https://www.pik-potsdam.de/en/institute/departments/activities/dominoes "https://www.pik-potsdam.de/en/institute/departments/activities/dominoes"))
- Earth system resilience (<i class="fas fa-arrow-circle-right"></i> [ERSU](https://www.pik-potsdam.de/en/institute/futurelabs-science-units/ersu "https://www.pik-potsdam.de/en/institute/futurelabs-science-units/ersu"))

## Ph.D. Project
My research focuses on the long-term stability and critical thresholds, or "tipping points", of the Antarctic Ice Sheet, as well as their implications for future sea-level rise under global warming. In particular, I focus on how the stability of the Antarctic Ice Sheet is influenced by interacting tipping elements within the Earth's climate system, such as the Greenland Ice Sheet and the Atlantic Meridional Overturning Circulation (AMOC). The goal of my Ph.D. project is to determine whether interactions between the Greenland and Antarctic ice sheets increase the likelihood that a tipping of the Greenland Ice Sheet amplifies the tipping potential of the Antarctic Ice Sheet.

{% include figure image_path="/images/Fig4.png" style="display:block;text-align:center;" alt="Simulated equilibrium states of the Antarctic Ice Sheet at different levels of global warming" caption="Simulated equilibrium states of the Antarctic Ice Sheet at different levels of global warming (from [Garbe et al., 2020](/publications/articles/garbe-2020 '/publications/articles/garbe-2020'))." %}

To get a better idea of my research focus, watch this short introduction video about the [TiPACCs](https://www.tipaccs.eu "https://www.tipaccs.eu") project on tipping points in Antarctic climate components, in which I am involved:
{% include video id="brUoMpHmbiA" provider="youtube" %}

## Models
### Parallel Ice Sheet Model (PISM)
For my research, I mainly use and co-develop the [Parallel Ice Sheet Model (PISM)](https://www.pism.io/ "https://www.pism.io/"). PISM is an [open-source](/publications/data/khrulev-2023 '/publications/data/khrulev-2023'), high-resolution computer model used to simulate the flow of ice sheets and glaciers, which is adopted as a scientific tool by many research groups around the globe.
PISM is jointly developed at the University of Alaska, Fairbanks (UAF) and the Potsdam Institute for Climate Impact Research (PIK).

{% include figure image_path="/images/pism_3d_4km_2020.png" class="half" style="display:block;text-align:center;" alt="Antarctic Ice Sheet as simulated with PISM" caption="Antarctic Ice Sheet as simulated with PISM." %}

### Modeling Sandbox
Want to play around with some simple ice-sheet models yourself? Check out this <i class="fas fa-arrow-circle-right"></i> [Github repository](https://github.com/juliusgarbe/modelling_sandbox "https://github.com/juliusgarbe/modelling_sandbox")!
