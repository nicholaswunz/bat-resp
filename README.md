# Bat respirometry
[![license](https://img.shields.io/badge/license-MIT%20+%20file%20LICENSE-lightgrey.svg)](https://choosealicense.com/)
![Open Source
Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)

This repository contains code and data needed to reproduce the article:

**Wu N. C., Villada-Cadavid T., & Turbill, C.** (In review) Local climate and genetic influence on intraspecific variation in torpor physiology of a cave-roosting bat.

**Data**
- `resp_raw_dat.csv` - Raw respirometry data used for the analysis.
- `cave_survey.csv` - Raw cave temperature and humidity data during winter bat surveys inside the caves.
- `bat_gl7.fas.treefile` - Genetic relatedness of all measured individuals used in the study.
- `JEN_EXT_HOBO.csv` - External temperature readings for Jenolan to produce Figure 1.
- `JEN_END_HOBO.csv` - Internal cave temperature readings for Jenolan to produce Figure 1.
- `YES_EXT_HOBO.csv` - External temperature readings for Yessabah to produce Figure 1.
- `YES_END_HOBO.csv` - Internal cave temperature readings for Yessabah to produce Figure 1.

**Files**
- Miniopterus_orianae_oceanensis - Contains shape files of *Miniopterus orianae oceanensis* extent distribution from [BatMap](https://www.ausbats.org.au/batmap.html) to produce Figure 1.

**Analysis workflow**
- [`supplementary_information.html`](https://nicholaswunz.github.io/bat-resp/supplementary_information.html) - Supplementary information which contains the *R* workflow for processing and analysing the raw data, and creating figures.

## Abstract
Many small endotherms employ torpor as a survival strategy to reduce energy expenditure during cold and low food periods. The expression and physiology of torpor can vary substantially within species because of phenotypic plasticity and local adaptation of populations to their environment. Understanding how plasticity and genetics influence intraspecific variation is fundamental to identifying the drivers of phenotypic variance in nature. Using a widely distributed bat species, the eastern bent-wing bat (*Miniopterus orianae oceanensis*), we exposed individuals from two thermally distinct sites to cold temperature regimes (ranging from 15 to 5 °C). We measured skin surface temperature (*T*<sub>sk</sub>), oxygen consumption and carbon dioxide production (proxies for torpor metabolic rate, TMR), and water loss during torpor (TEWL) using open-flow respirometry. We analysed variation in torpor physiology using phylogenetically controlled, multilevel models, which indicated that bats from both sites exhibited a similar TMR at low *T*<sub>sk</sub>, whereas bats from the colder site had a higher TMR at higher *T*<sub>sk</sub>. TMR had moderate heritability (*h*<sub>2</sub> = 0.41), suggesting that related bats have similar TMR. In contrast, TEWL showed low heritability (*h*<sub>2</sub> = 0.15), likely because the relative humidity of caves was similar between sites, thereby reducing selective pressures for the adaptation of TEWL in this species. Given that individuals from these wintering sites are unlikely to be genetically isolated, the observed variation in torpor physiology most likely reflects phenotypic plasticity. Plasticity in the expression of thermoregulatory strategies is presumedly an important adaptation for widely distributed endotherms to be successful across a large range of thermal climates.

**Keywords:** energy metabolism, evaporative water loss, genetic relatedness, hibernation, respirometry, temperature


## License
This repository is provided by the authors under the MIT License ([MIT](http://opensource.org/licenses/MIT)).
