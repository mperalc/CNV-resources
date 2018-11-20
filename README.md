# CNV-resources
Tools to detect CNVs from exome sequencing data.

* [CNVkit](https://cnvkit.readthedocs.io/en/stable/)
Python. It can be run with and without control samples.

* [ONCOCNV](https://github.com/BoevaLab/ONCOCNV/)
Perl and R. It needs control samples (they recommend at least 3 replicates). It has nice visualization plots in R. 

* [XHMM](http://atgu.mgh.harvard.edu/xhmm/index.shtml)
C++. It requires high coverage of genomic regions for many samples.

* [Control-FREEC](https://github.com/BoevaLab/FREEC)
C++. It needs control samples.

* [Quandico](https://github.com/reineckef/quandico)
R. Data are expected to be from gene-panels with primer-counts in the range of hundreds, and roughly double-digit number genes. It will not work well on whole-exome-enrichment data.

* [CNVPanelizer](https://bioconductor.org/packages/release/bioc/html/CNVPanelizer.html)
R. It needs control samples.

* [varscan](http://dkoboldt.github.io/varscan/)
Java. It needs control samples.

