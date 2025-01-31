# Licence

<! --- SPDX-License-Identifier: CC-BY-4.0  -- >

## About

### EOSC Recommender System

**Introduction**

Purpose of the document and intended audience TBC

Overall architecture of the EOSC Recommender System (EOSC-RS): TBC

[Interoperability guideline](https://zenodo.org/doi/10.5281/zenodo.7849177) presents details of the RS architecture and connections between software components.  

**Packages**

- EOSC-RS-Core: RS core framework serving recommendations for research products and trainings (PSNC)
- EOSC-RS-Extensions : RS engine serving additional recommendations in the Marketplace and recommendations for providers (ATHENA)
- EOSC-RS-Metrics: evaluation framework for recommendations  (GRNET)
- EOSC-RS-MP: RS engine serving recommendations for services in the Marketplace (Cyfronet)

**Software components** (https://wiki.eoscfuture.eu/display/EOSCF/Handover+documentation)

EOSC-RS-Core

- Nearline engine	[docs](https://git.man.poznan.pl/stash/projects/EOSC-RS/repos/nearline-ml-ai-engine/browse/docs)
- Online engine	[docs](https://git.man.poznan.pl/stash/projects/EOSC-RS/repos/online-ml-ai-engine/browse/docs)
- Nearest neighbor finder	[docs](https://git.man.poznan.pl/stash/projects/EOSC-RS/repos/nearest-neighbor-finder/browse/docs)
- RS Facade	[docs](https://git.man.poznan.pl/stash/projects/EOSC-RS/repos/rs-facade/browse/docs)
- Nearest neighbor finder training module	[docs](https://git.man.poznan.pl/stash/projects/EOSC-RS/repos/nearest-neighbor-finder-training-module/browse/docs) 
- Pre-processor	[docs](https://git.man.poznan.pl/stash/projects/EOSC-RS/repos/preprocessor/browse)

EOSC-RS-Extensions

- Content Based RS	[docs](https://github.com/athenarc/EOSCF-ContentBasedRS/tree/master/docs)	
- Provider Autocompletion	[docs](https://github.com/athenarc/EOSCF-Autocompletion/tree/master/docs)
- Provider Insights	[docs](https://github.com/athenarc/EOSCF-Provider-Insights/tree/master/docs)

EOSC-RS-Metrics

- RMF   [docs](https://github.com/ARGOeu/eosc-recommender-metrics/tree/devel/docs)

**Documentation**

The documentation is stored on the source code repositories listed above, which constitute the single source of truth for EOSC-RS software and related artefacts (such as documentation). For the sake of internal peer review, the copy of the whole set of documentation is on the SharePoint.

NOTE: The EOSC-RS-Metrics documentation is stored in a separate SharePoint folder: EOSC Recommender Metrics Framework (GRNET) 

