### Supplementary data and codes for 

# SequencErr: measuring and suppressing sequencer errors in next generation sequencing

Eric M Davis<sup>\*1</sup>, Yu Sun<sup>\*1,2</sup>, Yanling Liu<sup>\*1</sup>, Pandurang Kolekar<sup>1</sup>, Ying Shao<sup>1</sup>, Karol Szlachta<sup>1</sup>, Heather L Mulder<sup>1</sup>, Dongren Ren<sup>3</sup>, Stephen V Rice<sup>1</sup>, Zhaoming Wang<sup>4</sup>, Joy Nakitandwe<sup>5</sup>, Alex Gout<sup>1</sup>, Leslie L Robison<sup>4</sup>, Stanley Pounds<sup>6</sup>, Jefferey Klco<sup>5</sup>, John Easton<sup>1</sup>, Xiaotu Ma<sup>1\#</sup>

* <sup>1</sup> Department of Computational Biology, St. Jude Children’s Research Hospital, Memphis, TN

* <sup>2</sup> Department of Computer Science, University of Memphis, Memphis, TN

* <sup>3</sup> Independent Researcher, Memphis, TN

* <sup>4</sup> Department of Epidemiology & Cancer Control, St. Jude Children's Research Hospital, Memphis, TN

* <sup>5</sup> Department of Pathology, St. Jude Children's Research Hospital, Memphis, TN

* <sup>6</sup> Department of Biostatistics, St. Jude Children's Research Hospital, Memphis, TN

* </sup>\#</sup> To whom correspondence should be addressed: Xiaotu.Ma@stjude.org


## SequencErr 

**SequencErr** app is available on St. Jude Cloud at https://platform.dnanexus.com/app/sequencerr for non-profit research uses. 

## Requirements

Following packages and their respective dependencies should be installed before using the [R](https://www.r-project.org/) scripts in this repository. At the time of analysis [R](https://www.r-project.org/) v3.6.1 was used to generate the figures.

* beeswarm
* ggpubr
* pheatmap
* RColorBrewer

```
install.packages(c('beeswarm', 'ggpubr', 'pheatmap', 'RColorBrewer'), repos = 'http://cran.us.r-project.org', dependencies = TRUE)
```

## Data
Unzip the archives _analysis.zip_ and _data.zip_

Please find pairerror data used in this study in the folder _data/pairerror_.

## Figures
All figures and related codes can be found in the folder _analysis_:

1. Fig1.e,f,g: Fig1_flowcell/heatmap/*pdf
2. Fig2.a,b and FigS2: in Fig2ab_S2_cross_platform_instrument_comparison/*pdf
3. Fig2.c,d: Fig2cd_compare_surface/*pdf
4. Fig3 and FigS6-8: Fig3_S678_COLO829/*pdf
5. FigS1 and FigS3: FigS13/*pdf
6. FigS4 and FigS5: FigS45/*pdf

## Codes and input data
R codes and input data for each figure can be found in the same folder as figure with similar names.

