# Data acquisition

## Raw sequencing data

Raw data, including sequences in FASTQ format were obtained from the following public databases:

* [ENA (European Nucleotide Archive) :octicons-link-external-16:](https://www.ebi.ac.uk/ena/browse){:target="_blank"} at [EBI (European Bioinformatics Institute) :octicons-link-external-16:](https://www.ebi.ac.uk/){:target="_blank"} of [EMBL (European Molecular Biology Lab) :octicons-link-external-16:](https://www.embl.de/){:target="_blank"},
* [SRA (Sequence Read Archive) database :octicons-link-external-16:](https://www.ncbi.nlm.nih.gov/sra){:target="_blank"} at [NCBI (National Center for Biotechnology Information) :octicons-link-external-16:](https://www.ncbi.nlm.nih.gov/){:target="_blank"} ,
* [HMP (Human Microbe Project) :octicons-link-external-16:](https://www.hmpdacc.org/){:target="_blank"}, and
* [AGP (American Gut Project) :octicons-link-external-16:](http://americangut.org/){:target="_blank"}. 

Data were downloaded using [enaBrowserTools :octicons-link-external-16:](https://github.com/enasequence/enaBrowserTools){:target="_blank"} and [SRA-Tools :octicons-link-external-16:](https://github.com/ncbi/sra-tools){:target="_blank"} facilitated by Aspera (a high-speed data transfer tool).

## Meta data

Meta-data were first extracted using in-house Perl/R/Python scripts and then manually curated at least two-rounds to ensure the quality. Meta-data curation was not painless because sometimes such information were often incomplete, misplaced or even completely missing. Very often we had to consult the description of the samples, supplementary data of related publications or sometimes even the authors.

Technical meta-data extracted include:

* experiment type (16S or Metagenomics),
* sequencing devices / instruments, and
* number of obtained sequencing reads.

Host-related, biological-relevant meta-data extracted include:

* disease or health of the host (refered as to <code>phenotype</code> in our database),
* age,
* sex,
* BMI (body mass index), and
* antibiotic usage.

More meta-data will be added in the future.

