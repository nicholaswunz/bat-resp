# Bat respirometry
[![license](https://img.shields.io/badge/license-MIT%20+%20file%20LICENSE-lightgrey.svg)](https://choosealicense.com/)
![Open Source
Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)

This repository contains code and data needed to reproduce the article:

**Wu N. C., Villada-Cadavid T., & Turbill, C.** (Accepted) Local climate and genetic influence on intraspecific variation in torpor physiology of a cave-roosting bat. *Functional Ecology*,

When using the data or code from this project, please cite it as:

Wu N. C., Villada-Cadavid T., & Turbill, C. (2026) Accepted version of paper data and code of manuscript: Local climate and genetic influence on intraspecific variation in torpor physiology of a cave-roosting bat. Zenodo. DOI: [![DOI](https://zenodo.org/badge/794788712.svg)](https://doi.org/10.5281/zenodo.15447773)


**Data**
- `resp_raw_dat.csv` - Raw respirometry data used for the analysis.
- `cave_survey.csv` - Raw cave temperature and humidity data during winter bat surveys inside the caves.
- `bat_gl7_mth3.treefile` - Genetic relatedness of all measured individuals used in the study.
- `JEN_EXT_HOBO.csv` - External temperature readings for Jenolan to produce Figure 1.
- `JEN_END_HOBO.csv` - Internal cave temperature readings for Jenolan to produce Figure 1.
- `YES_EXT_HOBO.csv` - External temperature readings for Yessabah to produce Figure 1.
- `YES_END_HOBO.csv` - Internal cave temperature readings for Yessabah to produce Figure 1.

**Files**
- Miniopterus_orianae_oceanensis - Contains shape files of *Miniopterus orianae oceanensis* extent distribution from [BatMap](https://www.ausbats.org.au/batmap.html) to produce Figure 1.

**Analysis workflow**
- [`supplementary_information.html`](https://nicholaswunz.github.io/bat-resp/supplementary_information.html) - Supplementary information which contains the *R* workflow for processing and analysing the raw data, and creating figures.

## Abstract
1. Many small endotherms employ torpor as a survival strategy to reduce energy expenditure during periods with low food availability and cold temperatures. The expression and physiology of torpor can vary substantially within species because of phenotypic plasticity and local adaptation. Understanding how plasticity and genetics influence intraspecific variation is fundamental to identifying the drivers of phenotypic variance in nature.
2. Using a widely distributed bat species, the eastern bent-wing bat (*Miniopterus orianae oceanensis*), we exposed individuals from two thermally distinct sites to cold temperature regimes (ranging from 15 to 5 °C). We measured skin surface temperature (*T*<sub>sk</sub>), oxygen consumption and carbon dioxide production (proxies for torpor metabolic rate, TMR), and water loss during torpor (TEWL) using open-flow respirometry.
3. Analysis of the data using phylogenetically controlled, multilevel models indicated that bats from both sites exhibited a similar TMR at low *T*<sub>sk</sub>, whereas bats from the colder site had a higher TMR at higher *T*<sub>sk</sub>. We found no evidence of genetic differentiation of bats between the sites and estimates of heritability for TMR and TEWL showed broad credible intervals, yielding high uncertainty in interpreting genetic effects.
4. Differences in torpor physiology responses between warm and cold sites were likely driven by phenotypic plasticity, with among-individual variation in responses partially explained by genetic effects. Such flexibility in the expression of thermoregulatory strategies is important for a highly mobile and widely distributed endotherm to be successful across a large range of thermal climates.

**Keywords:** energy metabolism, evaporative water loss, genetic relatedness, hibernation, respirometry, temperature


## License
This repository is provided by the authors under the MIT License ([MIT](http://opensource.org/licenses/MIT)).
