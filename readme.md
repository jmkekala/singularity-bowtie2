# Singularity: Bowtie2

Example on howto combine [Singularity](https://www.sylabs.io/singularity/) and [Anaconda](https://www.anaconda.com/distribution/). Example application is [bowtie2](http://bowtie-bio.sourceforge.net/bowtie2/index.shtml)

## How to use
1. Build Singularity Image
..* $ sudo singularity build bowtie2.simg bowtie2.def
2. Run image
..* $ singularity run bowtie2.simg --version 

