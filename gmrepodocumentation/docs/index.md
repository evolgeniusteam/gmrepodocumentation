# Welcome to <b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>

<b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>
 is a curated database of human gut metagenomes. Please choose a topic on the left navigation panel to continue.

## Citation

Please cite our latest publication if you find this resource useful:

[Dai, D. *et al.* "GMrepo v2: a curated human gut microbiome database with special focus on disease markers and cross-dataset comparison". *Nucleic Acids Res* (2022). Volume 50, Issue D1, Pages D777–D784. :octicons-link-external-16:](https://doi.org/10.1093/nar/gkab1019){:target="_blank"}.

### previous version(s):

[Wu, S. *et al.* "GMrepo: a database of curated and consistently annotated human gut metagenomes". *Nucleic Acids Res* (2020). :octicons-link-external-16:](https://doi.org/10.1093/nar/gkz764){:target="_blank"};

## What's new

### Nov 25, 2020

Added new pages:

* [curated projects :octicons-link-16:](https://gmrepo.humangut.info/data/curatedprojects),
* [phenotype comparisons :octicons-link-16:](https://gmrepo.humangut.info/phenotypes/comparisons), and
* [marker taxa :octicons-link-16:](https://gmrepo.humangut.info/taxon/markertaxa).

## Aims and features of <b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>

### Capture the full dynamics of human gut microbes

With <b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>,
we aim to capture the full dynamics of the microbes living in the human gut, including their

* abundances and prevalence,
* associations with [human health and diseases :octicons-link-16:](https://gmrepo.humangut.info/phenotypes) , and
* co-occurrences,

all of which can be further stratified by using manually curated meta-data:

* population (country),
* gender,
* age,
* body mass index, and
* many other available meta data.

### Emphasize on data quality and re-usability

With <b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>,
we emphasize on **data quality** and **re-usability** (i.e., availability of the host meta-data).
We thus:

* manually extracted and curated relevant meta-data (most of the time with difficulties) from public databases and related publications;
* consistently re-annotated all data using state-of-the-art methods (see the [Materials and methods :octicons-link-16:](materialsandmethods/dataprocessingandqc.md) page for details);
* applied vigorous quality control (QC) methods and stringent criteria to the data, in order to include only high quality data, but nonetheless kept the meta-data of the samples and runs in our database.

### Make relevant information easier to find

In order to further facilitate users to find data of interests, we equipped <b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b> with
[a graphical query builder (data selector) :octicons-link-16:](https://gmrepo.humangut.info/home) to help users to create complex and flexible queries with a few clicks. So far the data selector allows users to filter samples and runs by related technical meta data such as <code>experiment type (16S or Metagenomics)</code>, <code>number of sequenced reads</code>, and host- related meta data, including related phenotype (<code>disease or health</code>), <code>age</code>, <code>sex</code>, and <code>BMI (body mass index)</code>. More filters will be added in the future.
For example, the screenshot below allows users to search for samples (runs) that:

* were taken from healthy individuals with BMI (body mass index) over 25, <code>AND</code>
* were sequenced by either 16S <code>OR</code> metagenomics.

![ :octicons-link-16:](images/index/query_builder_example.png)

See [Use the graphic data selector :octicons-link-16:](usage/graphicdataselector.md) for details and more examples.
