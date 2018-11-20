# CNV-resources
Tools to detect CNVs from exome sequencing data.

* [CNVkit](https://github.com/etal/cnvkit)
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

* [CVNator](https://github.com/abyzovlab/CNVnator)
C++. See their [paper](https://genome.cshlp.org/content/21/6/974.long).

* [conifer](http://conifer.sourceforge.net/tutorial.html)
Python. 

* [ExomeCopy](http://www.bioconductor.org/packages/release/bioc/html/exomeCopy.html)
R. Does not need control samples. See their [paper](http://cmb.molgen.mpg.de/publications/Love_2011_exomeCopy.pdf).

* [ExomeDepth](https://cran.r-project.org/web/packages/ExomeDepth/index.html)
R. It needs control samples. ExomeDepth is really suited to detect rare CNV calls (typically for rare Mendelian disorder analysis).

* [contra-cnv](http://contra-cnv.sourceforge.net/)
[paper](https://www.ncbi.nlm.nih.gov/pubmed/22474122)

* [pindel](http://gmt.genome.wustl.edu/packages/pindel/)
[paper] (https://onlinelibrary.wiley.com/doi/full/10.1002/humu.22537)

* [codex](https://github.com/yuchaojiang/CODEX)

* [deAnnCNV](https://mcg.ustc.edu.cn/bsc/cnv/tool.html)
Check their main [website](https://mcg.ustc.edu.cn/bsc/cnv/index.html) as well.

* [CREST](https://www.stjuderesearch.org/site/lab/zhang)
[Paper](https://www.nature.com/articles/nmeth.1628)


Also check the following threads:
https://www.researchgate.net/post/Any_suggestions_about_some_tools_for_CNV_calling_analysis_on_whole_Exome_sequencing_data
https://www.biostars.org/p/13807/
