# Coding_Resources

## Useful tutorials

[Coding Club](https://ourcodingclub.github.io/tutorials/) - A LOT of useful tutorials on everything from R to Python to linear mixed models to Git and more!

## Software 

### R

[skimr](https://github.com/ropensci/skimr) - take a quick comprehensive look at your data before starting analysis!

#### [tidyverse](https://www.tidyverse.org/)
1. [readr](http://r4ds.had.co.nz/data-import.html) - reading in data
2. [dplyr](http://r4ds.had.co.nz/transform.html) - manipulate data
3. [tidyr](http://r4ds.had.co.nz/tidy-data.html) - transform data
4. [ggplot2](http://r4ds.had.co.nz/data-visualisation.html) - plot data
  * [ggstatsplot](https://github.com/IndrajeetPatil/ggstatsplot/blob/master/README.md) - A nice package to visualize statistics in ggplot frameworke
  * [ggtree](https://bioconductor.org/packages/devel/bioc/vignettes/ggtree/inst/doc/treeVisualization.html) - How to construct dendrograms in ggplot2 framework
  * [ggrepel](https://cran.r-project.org/web/packages/ggrepel/vignettes/ggrepel.html) - add labels to data points with minimal overlap of text
  * [maps](https://microbeecology.wordpress.com/2018/07/25/making-maps-with-ggplot2-and-sf/) - A short tutorial on how to make maps in ggplot2
  * [gghighlight](https://www.littlemissdata.com/blog/highlight) - A package to make highlighting data easier.
  * [visualization overview 1](https://www.data-to-viz.com/index.html#portfolioanchor) - A great resource for nice visualizations
  * [visualization overview 2](https://serialmentor.com/dataviz/) - Another great resource for nice visualizations
5. [purrr](http://r4ds.had.co.nz/iteration.html) - iterate across data
6. [modelr](http://r4ds.had.co.nz/model-basics.html) - building models to describe data
7. [tidyeval](https://edwinth.github.io/blog/dplyr-recipes/) - moving from strings to variables for functionalizing within tidyverse framework
8. [ViewPipeSteps](https://github.com/daranzolin/ViewPipeSteps) - to visualize each generated dataframe in a dplyr pipe. for debugging

#### People to follow on twitter
1. @dataandme - data scientist and tidyverse developer
2. @_ColinFay - developer of purrr
3. @romain_francois - developer at tidyverse
4. @hadleywickham - developer at tidyverse
5. @juliasilge - data scientist at stackoverflow
6. @JennyBryan - engineer at Rstudio
7. @thomasp85 - data scientist who makes a lot of useful packages
8. @ClausWilke - Computational biologist with a great blog [Serial Mentor](serialmentor.com)

### Manipulating VCF

1. [BCFtools](https://samtools.github.io/bcftools/bcftools.html) - subset, filter, convert, and other functionality for VCF files
2. [VCFtools](https://vcftools.github.io/man_latest.html) - less powerful than BCFtools, but can also calculate simple population genetic statistics - pi, tajima's, etc
3. [PLINK](https://www.cog-genomics.org/plink2) - Fast processing of VCF files
4. [vcflib](https://github.com/vcflib/vcflib) - Fills in some gaps in BCFtools and VCFtools
5. [vcfanno](https://github.com/brentp/vcfanno) - fast annotation of VCF files
6. [SnpEff & SnpSift](http://snpeff.sourceforge.net/) - annotate VCFs with varient effects
7. [SNP filtering](http://ddocent.com/filtering/) - a guide to filtering high quality SNPs

### Genomic data visualization

1. [IGV](https://software.broadinstitute.org/software/igv/) - Visualize BAMs
2. [MSscan](https://github.com/tanghaibao/jcvi/wiki/MCscan-(Python-version)) - A tool to visualize genome synteny. Also check out the [jcvi](https://github.com/tanghaibao/jcvi) parent directory
3. [samplot](https://github.com/ryanlayer/samplot) - Visualize structural variants

### Calling Variants

1. [Currated CNV and SV resources](https://github.com/geocarvalho/sv-cnv-studies) - we are currently running Manta, Smoove (Lumpy), Delly, and TIDDIT
2. [Strelka2](https://github.com/Illumina/strelka) - Small variants
3. [GATK4](https://github.com/broadinstitute/gatk) - Small variants

### Presentations

1. [Better Presentations Cheatsheet](https://policyviz.com/2018/08/14/better-presentations-cheatsheet/) - This is a cheat sheet describing the fundamentals discussed in the Better Presentations book by Jonathan Schwabish. Also, [here](https://policyviz.com/better-presentations/) is a website with a lot of the information discussed with book.
2. [Data Viz Cheatsheet](https://policyviz.com/2018/08/07/dataviz-cheatsheet/)
3. [PEQG2018 Crow Award Presentations](http://genestogenomes.org/videos-from-peqg18-keynote-and-crow-award-sessions/?category=science-and-publishing)

### Phylogeny

1. [Tree Snatcher](http://www.cibiv.at/software/treesnatcher/) - convert static images of trees to distance matrix for plotting

### Selection

1. [Sweep Overview](http://www.cs.cmu.edu/~sssykim/teaching/f11/slides/Lecture10.pdf)
2. [Sweep Overview](https://math.la.asu.edu/~jtaylor/teaching/Spring2017/BIO545/lectures/scans.pdf)
3. [Haplotype Selection Stats](https://github.com/ngarud/SelectionHapStats) - from this [paper](http://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1005004)
4. [Classic Popgen stats](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.210.4017&rep=rep1&type=pdf) 
5. [Machine Learning Popgen](https://www.sciencedirect.com/science/article/pii/S0168952517302251?via%3Dihub)
6. [EHH](https://www.nature.com/articles/nature01140) - The EHH measures the decay of identity, as a function of distance, of haplotypes that carry a specified “core” allele at one end. For each allele, haplotype homozygosity starts at 1, and decays to 0 with increasing distance from the core site (Figure 1B). As shown in the figure, when an allele rises rapidly in frequency due to strong selection, it tends to have high levels of haplotype homozygosity extending much further than expected under a neutral model. Hence, in plots of EHH versus distance, the area under the EHH curve will usually be much greater for a selected allele than for a neutral allele. 
7. [iHS](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.0040072#pbio-0040072-b005) -  In order to capture this effect, we compute the integral of the observed decay of EHH away from a specified core allele until EHH reaches 0.05. This integrated EHH (iHH) (summed over both directions away from the core SNP) will be denoted iHHA or iHHD, depending on whether it is computed with respect to the ancestral or derived core allele. Finally, we obtain our test statistic iHS using iHHa/iHHd. 
8. [H1/H2](http://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1005004)
9. 

### Command Line
1. [Useful tools](https://astrobiomike.github.io/bash/six_commands)

### Nextflow

1. [Nextflow Documentation](https://www.nextflow.io/docs/latest/index.html)
2. [Nextflow Patterns](https://github.com/nextflow-io/patterns)

### Learning
1. [Math Tutorials](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw/playlists?app=desktop) - Aaron Quinlan approved videos!
2. [Stats Overview](http://www.statsoft.com/Textbook/Elementary-Statistics-Concepts)


