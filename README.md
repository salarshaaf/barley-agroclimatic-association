This repository contains data files and source code used in a project in which we looked for 
genome-wide association with high-resolution climate data of the Iberian Peninsula with the 
goal of discovering selection footprints in the genomes of barley landraces from the
[Spanish Barley Core Collection](http://www.eead.csic.es/barley/index.php?lng=1).

URL: [eead-csic-compbio.github.io/barley-agroclimatic-association](https://eead-csic-compbio.github.io/barley-agroclimatic-association)

**Authors**

B Contreras-Moreira (1,2), R Serrano-Notivoli (1), NE Mohamed (1), CP Cantalapiedra (1), S Begueria (1), AM Casas (1), E Igartua (1)

1. Estacion Experimental de Aula Dei-CSIC, Zaragoza, Spain
2. Fundacion ARAID, Zaragoza, Spain


There are several R markdown documents describing the selection of agroclimatic variables, 
mapping and diverse protocols for association analyses:

| filename | summary | 
|:---------|:--------:|
|[HOWTOclimate](./HOWTOclimate.html)| Preparation and selection of climate variables |
|[HOWTOstructure](./HOWTOstructure.html)| Analysis of population structure of Spanish barleys |
|[HOWTORDA](./HOWTORDA.html)| Redundancy Analysis |
|[HOWTOLD](./HOWTOLD.html)| Linkage Disequilibrium |
|[HOWTOsnps](./HOWTOsnps.html)| Association between SNPs and climate variables (bayenv2) |
|[HOWTOXtX](./HOWTOXtX.html)| XtX subpopulation differentiation (bayenv2) |

<!--|[HOWTOmaps.md](./HOWTOmaps.md)| Iberian maps of SNPs significantly associated to climate variables, saved in [maps/plots](./maps/plots) | -->

<!--An example of the maps that were produced is shown below:
![**Legend.** Sample map of SNPs and agroclimatic variable](./maps/plots/BOPA2_12_10979_verna_30d.png) -->

## Dependencies

Besides [bayenv2](https://gcbias.org/bayenv) and a few Perl scripts, included in this repository,
these protocols require a few R packages which must be installed to reproduce the results:

[dplyr](https://cran.r-project.org/package=dplyr),
[grid](https://cran.r-project.org/package=grid),
[maptools](https://cran.r-project.org/package=maptools),
[raster](https://cran.r-project.org/package=raster),
[ape](https://cran.r-project.org/package=ape),
[cluster](https://cran.r-project.org/package=cluster),
[corrplot](https://cran.r-project.org/package=corrplot),
[dendextend](https://cran.r-project.org/package=dendextend),
[devtools](https://cran.r-project.org/package=devtools),
[ggplot2](https://cran.r-project.org/package=ggplot2),
[gplots](https://cran.r-project.org/package=gplots), 
[qqman](https://cran.r-project.org/package=qqman),
[vegan](https://cran.r-project.org/package=vegan),
[LDcorSV](https://cran.r-project.org/web/packages/LDcorSV/index.html),
[pracma](https://cran.r-project.org/package=pracma)

In addition [knitr](https://cran.r-project.org/package=knitr) is required to compile the .Rmd files in Rstudio.

