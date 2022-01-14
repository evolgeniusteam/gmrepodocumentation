# Data downloads

## Download processed data from <b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>

|    **File**   |   **Description**                    |
| ------------- | ------------------------------------ |
| [Projects](https://gmrepo.humangut.info/Downloads/SQLDumps/projects.txt.gz) | a list of projects and related information such as project description |
| [Projects summary](https://gmrepo.humangut.info/Downloads/SQLDumps/projects_summary.txt.gz) | a list of projects and related information such as total numbers of associated runs, processed runs, valid runs and failed runs. |
| [All runs](https://gmrepo.humangut.info/Downloads/SQLDumps/sample_to_run_info.txt.gz) | information on runs/samples collected in this database, including their associated projects, and other curated meta-data. | 
| [Runs to phenotypes](https://gmrepo.humangut.info/Downloads/SQLDumps/sample_to_disease_info.txt.gz) | all runs and their corresponding phenotypes (if any); one run/sample can be associated with multiple phenotypes. |
| [Processed runs](https://gmrepo.humangut.info/Downloads/SQLDumps/samples_loaded.txt.gz)| a list of proccessed runs, tools used to do the analysis, and their QC statuses |
| [Relative abundances](https://gmrepo.humangut.info/Downloads/SQLDumps/species_abundance.txt.gz) | relative abundances at species and genus levels in samples/runs that passed our QC criteria |
| [Relative abundance summary](https://gmrepo.humangut.info/Downloads/SQLDumps/species_abundance_summary.txt.gz) | some statistics on the taxonomic abundances data |
| [Taxon co-occurrence data](https://gmrepo.humangut.info/Downloads/SQLDumps/species_cooccurence.txt.gz) | taxon cooccurence in runs/samples of each phenotype, calculated separately for species and genus |
| [Statistics by phenotype](https://gmrepo.humangut.info/Downloads/SQLDumps/stats_by_phenotype.txt.gz) | statistics by phenotype, including total number of runs (with meta-data available) associated with each phenotype, the numbers of processed, valid and failed runs for each phenotype, and the total numbers of species and genera associated with each phenotype in our database |
| [MySQL dump of the whole database](https://gmrepo.humangut.info/Downloads/SQLDumps/gmrepo.sql.gz) | mysql dump of all tables included in our database |
| [MeSH table](https://gmrepo.humangut.info/Downloads/SQLDumps/mesh_data.txt.gz) | Medical Subject Headings (MeSH) data used in this study |
| [NCBI taxonomy table](https://gmrepo.humangut.info/Downloads/SQLDumps/superkingdom2descendents.txt.gz) | reformatted NCBI taxonomy information, including ncbi taxon ID to scientific name and rank information |

!!! note
    Please NOTE that in the NCBI taxonomy database two types of taxonomy ids are used,

    * taxon_id: refers to internal unique id used by NCBI taxonomy, while
    * ncbi_taxon_id: refers to the *REAL* taxonomy id of a taxnomy entity.

## Download raw sequence data

Due to limited hardware capacity we do not offer downloading raw sequence data directly from our database.

Instead, users should download the raw sequence reads from public databases such as [SRA (Sequence Read Archive) database :octicons-link-external-16:](https://www.ncbi.nlm.nih.gov/sra){:target="_blank"} at NCBI (National Center for Biotechnology Information).

To do so, users can either copy & paste the run ID of interest to the "Search" box of [SRA (Sequence Read Archive) database :octicons-link-external-16:](https://www.ncbi.nlm.nih.gov/sra){:target="_blank"}, go to the web page for the run, and use the download links provided at the SRA web page to download the raw sequence data.
or use the "linkout" :octicons-link-external-16: icon usually available for each run ID in our database to go directly to the corresponding SRA web page.

Alternatively, users can use command line tools in the [SRA Tookit :octicons-link-external-16:](https://trace.ncbi.nlm.nih.gov/Traces/sra/sra.cgi?view=software){:target="_blank"} to download raw data of various formats from [NCBI SRA :octicons-link-external-16:](https://www.ncbi.nlm.nih.gov/sra){:target="_blank"}. Commonly used tools include:

* [fastq-dump :octicons-link-external-16:](https://trace.ncbi.nlm.nih.gov/Traces/sra/sra.cgi?view=toolkit_doc&f=fastq-dump){:target="_blank"}: download SRA data to local directory. Usage:

`fastq-dump [options] <run_accesion_id>`

* [prefetch :octicons-link-external-16:](https://trace.ncbi.nlm.nih.gov/Traces/sra/sra.cgi?view=toolkit_doc&f=prefetch){:target="_blank"} : download SRA, dbGaP and ADSP data. Usage:

`prefetch [options] <run_accesion_id>`

Please consult the [SRA Toolkit documentation :octicons-link-external-16:](https://trace.ncbi.nlm.nih.gov/Traces/sra/sra.cgi?view=toolkit_doc){:target="_blank"} for more details.

## Programmable access

<b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b> also provides programmable access to most of the database contents through `RESTful APIs`.

Below please find example codes for a few languages that we use in our lab; users who are using other languages can either create their own codes following these examples, or contact us for support.

* [R :octicons-link-external-16:](https://github.com/evolgeniusteam/GMrepoProgrammableAccess/blob/master/programmable-access/R.md){:target="_blank"}
* [Perl :octicons-link-external-16:](https://github.com/evolgeniusteam/GMrepoProgrammableAccess/blob/master/programmable-access/perl.md){:target="_blank"}
* [Python (2&3) :octicons-link-external-16:](https://github.com/evolgeniusteam/GMrepoProgrammableAccess/blob/master/programmable-access/python.md){:target="_blank"}

See our [GitHub page :octicons-link-external-16:](https://github.com/evolgeniusteam/GMrepoProgrammableAccess){:target="_blank"}  for details.