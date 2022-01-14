# Website overview

## The Main / Home page

The main containts of the [home page :octicons-link-16:](https://gmrepo.humangut.info/home) contain two main sections: 

### 1. brief summary of db contents

This sections contain:

* the main features of <b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>
* main contents of the database and links to the corresponding pages.

### 2. a graphic data selector

A graphic data selector that allows users to construct complex queries to the projects and runs in our database. It consists of two selectors, one is dedicated for searching for <code>samples/runs</code>, the other is for <code>projects</code>.

Below is a screenshot of the selector:

![](../images/index/query_builder_example.png).

The search logic is to find <code>runs/samples</code> that are: 

* related to healthy individuals, <code>AND</code>,
* 18 to 25 years old, <code>AND</code>,
* with healthy BMI from 18.5 to 24.9.

See the [Database usage :octicons-link-16:](../usage/graphicdataselector.md) section for details and more examples.

## Header bar / navigation bar

The header bar is the most important widget of 
<b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>.

It is fixed to the top so it is placed at the top of windows.

It plays three major roles, navigation and global search. See the screenshot below:

![](images/websiteoverview/header_bar.png)

### 1. Logo

It displays a logo of <b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>. Users can click this logo and navigate back to the [home page :octicons-link-16:](https://gmrepo.humangut.info/home).

### 2. Global search

It contains a global search widget that allows users to enter <code>keywords</code> of interests, shows the search results in a dropdown list, and allow users to click and go to the corresponding page in our database.

For example, users can use it to find any of the following entries in our database:

* projects,
* samples,
* runs,
* gut microbes, 
* marker microbes, 
* diseases and 
* disease-health comparisons

!!! note
    * The search is automatic when users enter three and more characters, i.e., the search results (if there is any) will be shown automatically as users type. It is thus no need to press the "enter" key.
    
    * The wideget does not show anything is no maches are found in the database.

Please consult the help pages in the "Database usage" section for details.

### 3. Menu items / navigation items

This section contains menu and sub-menu items that allow users to navigate through the main contents of <b><span style="color:darkblue">G</span><span style="color:red">M</span><span style="color:forestgreen">repo</span></b>.

These (sub)menu items include:

* :fontawesome-solid-home: Home : navigate back to the [home page :octicons-link-16:](https://gmrepo.humangut.info/home).
* :fontawesome-solid-disease: Phenotypes : mouse over or click  to show two sub-menus:
    * :fontawesome-solid-disease: All phenotypes: go to the [List of diseases and their associated gut microbes :octicons-link-16:](https://gmrepo.humangut.info/phenotypes).
    * :fontawesome-solid-check-double: Phenotype comparisons: contains a list of disease-health or disease-disease comparisons for which [microbial markers have been identified :octicons-link-16:](https://gmrepo.humangut.info/phenotypes/comparisons).
* :fontawesome-solid-bacteria: Taxa: contains two sub-menus:
    * :fontawesome-solid-bacteria: All taxa: list and characterisations of [gut microbes :octicons-link-16:](https://gmrepo.humangut.info/taxon) at species and genus levels identified from all qualified samples;
    * :fontawesome-regular-star: Marker taxa: list and distribution of [marker taxa :octicons-link-16:](https://gmrepo.humangut.info/taxon/markertaxa) at species and genus levels identified from curated projects.
* :fontawesome-solid-database: Data: contains two submenus:
    * :fontawesome-solid-database: All projects and runs: lists of [projects, runs and related metadata](https://gmrepo.humangut.info/data),
    * :fontawesome-solid-check-double: Curated projects: a list of [curated projects](https://gmrepo.humangut.info/data/curatedprojects).
*  :fontawesome-solid-info-circle: Help: link to this documentation.

## Footer

The footer shows at the bottom of all pages and contains copyright information and links to 
[contact information :octicons-link-16:](#contact-information), 
[Our latest publication :octicons-link-external-16:](https://doi.org/10.1093/nar/gkz764){:target="_blank"}.

## Contact information

This database is a collaboration by:

* [Chen Lab at Huazhong University of Science and Technology (HUST) :octicons-link-external-16:](http://chenlab.medgenius.info/){:target="_blank"},
* [Zhao Lab at Fudan University :octicons-link-external-16:](http://comp-sysbio.org/){:target="_blank"}, and
* [Ning Lab at HUST :octicons-link-external-16:](http://life.hust.edu.cn/info/1021/1470.htm){:target="_blank"}.
