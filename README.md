
scripts to reproduce the analysis and figures from Bai et al., 2015

originally by Ruben Garrido-Oter

garridoo@mpipz.mpg.de



This folder contains all scripts necessary to reproduce the results
of the whole-genome comparative analysis presented in Bai et al., 2015.
from the raw data. It consists of the following separate steps:

1. assembly of genomes using A5 and SOAPdenovo:
    
    assembly.sh

2. prediction of ORFs and annotation:

    datagen.sh

3. extraction of AMPHORA marker genes and generation of spp. tree:

    phylo.sh

4. whole-genome taxonomic classification using taxator-tk:

    taxator.sh

5. figures and statistical tests:

    script.R


NOTE:

Steps 1.-4. are very computationally intensive and can only be performed in 
a reasonable time frame using high-performance computing and parallelization.
For this reason, the secondary data generated be these scripts (namely:
assemblies, ORFs, annotations, species tree, WGS taxonomy info., etc.) are
provided here:

http://www.at-sphere.com/download/whole_genome_analysis.tar.gz

Step 5. can be easily run in under 15 min. in most systems and will generate
all figures presented in Bai et al., 2015 related to the whole-genome analyses 
starting from the mentioned secondary data.

If you use any of these scripts, please cite our paper:

Functional overlap of the Arabidopsis leaf and root microbiota.
Bai Y, Müller DB, Srinivas G, Garrido-Oter R, Potthoff E, Rott M, Dombrowski N, Münch PC, Spaepen S, Remus-Emsermann M, Hüttel B, McHardy AC, Vorholt JA, Schulze-Lefert P.
Nature. 2015 Dec 2. doi: 10.1038/nature16192.

For any questions regarding these scripts, please contact

Ruben Garrido-Oter

garridoo@mpipz.mpg.de

