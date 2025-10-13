# alignment-and-snp-calling
Lines of code to do alignment and SNP calling with one example with the SRA sample ERR1822668 aligned on A. lyrata

This pipeline is for a machine with 6 CPU and memory of 10gb
It's required some open source softwares:
- bowtie2 v2.4.2 (https://bowtie-bio.sourceforge.net/bowtie2/index.shtml; Langmead B, Salzberg S. Fast gapped-read alignment with Bowtie 2. Nature Methods. 2012, 9:357-359. )
- samtools v1.21 (https://www.htslib.org/)
- picard v3.4 (http://broadinstitute.github.io/picard)
- bedtools v2.31 (https://bedtools.readthedocs.io/en/latest/)
- GATK v4.2.5 (https://gatk.broadinstitute.org/hc/en-us)
