---
title: "TOAD v1.0: A Python Framework for Detecting Abrupt Shifts and Coherent Spatial Domains in Earth-System Data"
collection: publications_preprints
permalink: /publications/preprints/harteg-2026
citation: "Harteg, J., Röhrich, L., De Maeyer, K., <b>Garbe, J.</b>, Sakschewski, B., Klose, A. K., Donges, J. F., Winkelmann, R., Loriani, S.: <i>TOAD v1.0: A Python Framework for Detecting Abrupt Shifts and Coherent Spatial Domains in Earth-System Data</i>, Geoscientific Model Development, in review, DOI: <a href='https://doi.org/10.5194/egusphere-2026-356'>10.5194/egusphere-2026-356</a> [preprint], 2026."
doi: 10.5194/egusphere-2026-356
date: 2026-01-29
venue: "Geoscientific Model Development"
---

## Abstract
Large-scale, nonlinear, abrupt, and potentially irreversible transitions in major Earth-system components are becoming increasingly likely under human pressures, with far-reaching consequences for ecosystems, climate stability, and human societies. Yet detecting and comparing such transitions across Earth System Model ensembles remains fragmented and inconsistent, hindering systematic assessment of tipping-point risks.

Here we present the first release of the Tipping and Other Abrupt events Detector (TOAD v1.0), an open-source, user-oriented Python framework for detecting abrupt changes in gridded Earth-system data. TOAD implements a modular three-stage pipeline consisting of 1) grid-level abrupt shift detection, 2) spatio-temporal clustering of co-occurring changes, and 3) consensus synthesis to identify statistically robust regions across ensemble members, variables, models, or methodological configurations and quantifies agreement in transition timing. The framework addresses key practical challenges of large-scale spatio-temporal clustering on geographic grids and provides diagnostic statistics and visualisation tools. Detection, clustering, and synthesis algorithms can be flexibly exchanged, supporting systematic method comparison and extensibility. TOAD functions as a data-introspection tool that reveals potentially tipping-relevant dynamics across spatial and temporal scales for subsequent, process-based analysis.

We apply TOAD to a synthetic benchmark, domain models of the Antarctic Ice Sheet and the global terrestrial biosphere, and a global Earth System Model ensemble of the North Atlantic Subpolar Gyre. Together, these demonstrations illustrate TOAD's applicability across diverse systems and establish a structured foundation for investigating where and when potentially tipping-relevant changes occur and for quantifying associated uncertainties, supporting coordinated assessment efforts such as the Tipping Points Modelling Intercomparison Project (TIPMIP).