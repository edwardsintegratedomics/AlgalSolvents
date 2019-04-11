# Algal Biosolvents

This project is designed to test the response of various species of algae to organic solvents. Many algae are capable of mixotrophic growth using an organic carbon source, and this growth is generally greater than phototrophic growth alone. 

Algae are generally photosynthetic, eukaryotic organisms that contain chlorophyll *a*. Recent research into algal biology is inspired by their ability to produce high value compounds for nutraceutical and biofuel use. Many of these high-value compounds are lipids: a diverse group of organic molecules that are generally insoluble in water and composed mainly of carbon and hydrogen.

The Edwards lab is uniquely equipped to process algal lipids via mass-spectrometry via the Orbitrap ID-X, an UHPLC-HRAM instrument designed specifically for small molecule identification and annotation. Generally, the workflow for the project is outlined below:


**Culturing --> Sampling --> Extracting --> Running --> Data processing**

Each of these steps is outlined in greater detail below.

## Culturing and sampling

### Algae species

The focus for this project is on high-value algae, a few of which are listed below:
 - Green algae
	 - Chlorella
	 - Chlamydomonas
	 - Dunaliella
	 - Nannochloropsis
	 - Scenedesmus
 - Diatoms
	 - Chaetocerous
	 - Navicula
	 - Phaeodactylum
	 - Thalassiosira

For the preliminary project, the focus will be placed on *Chlorella vulgaris*, a common freshwater algae that has already seen [extensive research]([https://www.sciencedirect.com/science/article/pii/S1364032114002342](https://www.sciencedirect.com/science/article/pii/S1364032114002342)), including some [preliminary lipid profiles]([https://www.sciencedirect.com/science/article/pii/S0960852411017147](https://www.sciencedirect.com/science/article/pii/S0960852411017147)). This culture has been purchased from UTEX and comes axenic on an algal slant.

### Carbon sources

Various organic carbon sources can be added to the media to enable mixotrophic growth, the most common of which are listed below:

 - Inorganic
	 - Carbon dioxide (by bubbling through the liquid media)
	 - Bicarbonate
 - Organic
	 - Methanol
	 - Ethanol
	 - Glycerol
	 - Acetate
	 - Glucose

For the preliminary project, the focus will be placed on methanol, ethanol, and acetate; beginning with methanol.

### Concentrations

For each organic solvent added, the concentration can significantly affect the growth rate and lipid composition. Typical values range 0-3%. For the preliminary experiment, the concentrations used will be 0.0, 0.1, 0.5, 1.0, and 3.0 % v/v.

### Sampling

Algae will be cultured in triplicate in 250ml of media, in 600ml culture flasks, and kept horizontal to maximize light availability and air exchange. Time points will be taken during lag, log, and stationary phase (currently expected to be at 1day, 3day, and 7day timepoints).

Each time point will involve removing 50ml of culture, checking the density of the culture via spectrophotometry, and filtration of the sample onto a Durapore filter to obtain the particulate fraction.

Filters will then be frozen in the -80, or extracted into vials and blown down, in preparation for the mass-spec coming online at the end of May.

### Constants

Light intensity - held constant at whatever intensity the incubator produces normally. 

Media - we'll be using the [UTEX Proteose Medium]([https://utex.org/products/proteose-medium](https://utex.org/products/proteose-medium)) which they use to grow *C. vulgaris*.

### Preliminary experimental matrix:

***C. vulgaris*, methanol:**

|     | 0.0% | 0.1% | 0.5% | 1.0% | 3.0% |
| --- | --- | --- | --- | --- | --- |
| Lag |
| Log |
| Stat |

***C. vulgaris*, ethanol:**

|     | 0.0% | 0.1% | 0.5% | 1.0% | 3.0% |
| --- | --- | --- | --- | --- | --- |
| Lag |
| Log |
| Stat |

***C. vulgaris*, acetate:**

|     | 0.0% | 0.1% | 0.5% | 1.0% | 3.0% |
| --- | --- | --- | --- | --- | --- |
| Lag |
| Log |
| Stat |

Note that each of the above matrices will have a third dimension, as each is cultured in triplicate.

The methanol trials will be done first. These trials will require about 4 liters of Proteose medium.

## Extraction

The typical Bligh and Dyer extraction process will be used to extract the algal lipids, coupled with [sonication](https://link.springer.com/article/10.1007/s12010-011-9207-1) designed to break up the notoriously resistant cell wall. 

Internal standards TBD will be added to the extract.

## Running

The [Hummel 2011]([https://www.frontiersin.org/articles/10.3389/fpls.2011.00054/full](https://www.frontiersin.org/articles/10.3389/fpls.2011.00054/full)) methodology will be used when running the samples on the mass spec.

Ideally, high-resolution fragmentation data will be collected to help elucidate complex molecule structures.

## Analysis

Analysis will be done in either LOBSTAHS or MS-DIAL.

Particular lipids to target are listed below:
 - Fatty acids
	 - 16:0, 16:1
	 - 18:0, 18:1, 18:2, 18:3, 18:4
	 - 20:0, 20:1, 20:2, 20:3, 20:4, 20:5
 - Membrane lipids
	 - Not very well characterized, especially under mixotrophic growth
 - TAGs
	 - These haven't been studied, like, at all.
 - Pigments
	 - Chlorophyll *a*, *b*
	 - $\beta$-carotene
	 - Astaxanthin
	 - Lutein
	 - Pheophytin *a*, *b*
	 - Violaxanthin

Et voila!
