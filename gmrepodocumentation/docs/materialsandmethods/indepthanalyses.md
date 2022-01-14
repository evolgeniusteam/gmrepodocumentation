# Identification of disease markers in curated projects

Please note this is an <code>ongoing effort</code> and the results are available for a limited number of projects; more projects will be added as the analyses go.

## Overview

Marker identification was performed for <code>selected projects</code> referred as 
[curated projects :octicons-link-16:](https://gmrepo.humangut.info/data/curatedprojects) in 
<b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>
. These projects were selected based on the following criteria (of course in addition to availability of manpower and time):

* high-quality meta-data with clearly defined diseases and healthy controls,
* high-quality of data, and
* enough numbers of both cases and controls, usually more than 20 per group.

## Marker taxa

A <code>marker taxon</code> refers to a genus or species that showed significantly differential abundances between two different groups (e.g., cases vs. controls or different disease stages such as adenoma vs. CRC) using 
<code>LEfSe (Linear discriminant analysis effect size)</code>
[PMID: 21702898  :octicons-link-external-16:](https://www.ncbi.nlm.nih.gov/pubmed/21702898){:target="_blank"}.

Marker taxa were identified on a per-project basis. 

Please consult the ["All marker taxa" page :octicons-link-16:](https://gmrepo.humangut.info/taxon/markertaxa) for more information.

## Curated projects

In <b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>
, manually curation was performed for selected projects in order to:

* select usable runs with clearly defined phenotype,
* merge multiple runs if they correspond to the same sample, and calcualte taxon abundances on per-sample basis instead of per-run basis,
* group samples according to their corresponding phenotypes, and
* identify marker taxa between a pair of phenotypes of intersts, e.g. CRC vs. Health.

Curated projects are highlighted with a :fontawesome-solid-check-double: symbol. In addition to the project meta data and run table, the project page for curated projects also contains a list of samples manually curated, their phenotypes and corresponding runs. Followed by marker taxa identified from pairs of phenotypes (refers to as [phenotype comparisons :octicons-link-16:](https://gmrepo.humangut.info/phenotypes/comparisons) in our database). Marker taxa are shown in both table view and boxplot view. If a curated project contains more than two phenotype groups, for example,

* Healthy controls,
* Adenoma and
* colorectal cancer (CRC)

multiple phenotype comparisons can be performed, such as

* Healthy control vs. CRC,
* Healthy control vs. Adenoma, and 
* Adenoma vs. CRC

in order to identify marker taxa for different disease stages.

See [PRJEB6070 :octicons-link-16:](https://gmrepo.humangut.info/data/project/PRJEB6070) for an example.

So far, 
<b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>
includes:

* 168 [curated projects :octicons-link-16:](https://gmrepo.humangut.info/data/curatedprojects), for
* 81 [diseases :octicons-link-16:](https://gmrepo.humangut.info/phenotypes/comparisons), involving
* 26,253 samples.