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
Many small endotherms employ torpor as a survival strategy to reduce energy expenditure during periods with low food availability and cold temperatures. The expression and physiology of torpor can vary substantially within species because of phenotypic plasticity and adaptation of populations to their local environment. Understanding how plasticity and genetics influence intraspecific variation is fundamental to identifying the drivers of phenotypic variance in nature. Using a widely distributed bat species, the eastern bent-wing bat (*Miniopterus orianae oceanensis*), we exposed individuals from two thermally distinct sites to cold temperature regimes (ranging from 15 to 5 °C). We measured skin surface temperature (Tsk), oxygen consumption and carbon dioxide production (proxies for torpor metabolic rate, TMR), and water loss during torpor (TEWL) using open-flow respirometry. We analysed variation in torpor physiology using phylogenetically controlled, multilevel models, which indicated that bats from both sites exhibited a similar TMR at low Tsk, whereas bats from the colder site had a higher TMR at higher Tsk. Our results also showed that TMR had moderate heritability (*h*<sub>2</sub> = 0.41) whereas TEWL showed lower heritability (*h*<sub>2</sub> = 0.15), perhaps reflecting differing selective pressures because caves varied among sites in temperature but had similar relative humidity. However, estimates of heritability were limited by the relatively low sample size of individuals. We found limited evidence for genetic population structure, indicating movement of individuals and genetic interchange among the sites. It seems that some combination of phenotypic plasticity and among-individual genetic differences explain variation in torpor physiology in this species. Presumably, such flexibility in the expression of thermoregulatory strategies is important for a highly mobile and widely distributed endotherm to be successful across a large range of thermal climates.

**Keywords:** energy metabolism, evaporative water loss, genetic relatedness, hibernation, respirometry, temperature


## License
This repository is provided by the authors under the MIT License ([MIT](http://opensource.org/licenses/MIT)).
