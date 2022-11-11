---
title: 'BioHackEU22 #6: Building a robust and reproducible assembly and annotation pipeline for non-model eukaryote genomes'
title_short: 'Eukaryotic Genome Assembly, Annotation, and Evaluation'
tags:
  - genome assembly
  - genome annotation
  - genome evaluation
authors:
  - name: Nadège Guiglielmoni
    affiliation: 1
  - name: Last Author
    orcid: 0000-0000-0000-0000
    affiliation: 2
affiliations:
  - name: Universität zu Köln
    index: 1
  - name: Second Affiliation
    index: 2
date: 8 November 2022
cito-bibliography: paper.bib
event: BH22EU
biohackathon_name: "BioHackathon Europe 2022"
biohackathon_url:   "https://biohackathon-europe.org/"
biohackathon_location: "Paris, France, 2022"
group: Project 6
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/abueg/2022-biohackathon-bhxiv
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---


# Introduction

As part of the BioHackathon Europe 2022, we here report...

# Oxford Nanopore (ONT) pipeline improvements

Intro sentence

## Integration of high quality (HQ) ONT reads

Blah

# New tool integrations in Bioconda and Galaxy

We implemented many tools in Bioconda and as Galaxy tool wrappers, thus increasing the availability of these important assembly & annotation software to a broader audience. This will help facilitate these computationally intensive analyses, since users will not have to go through laborious installations on their local computational resources.

| Software name | Category | Description | Status before BHEU22 | Status after BHEU22
| -------- | -------- | -------- | -------- | -------- 
| instaGRAAL | Assembly | description | Docker image | Galaxy tool
| NextDenovo | Assembly | description | no conda package | conda package
| hicstuff | Assembly | description | conda package | Galaxy tool (WIP)
| Ratatosk | Annotation | description | no conda package | conda package
| BandageNG | Evaluation | description | no conda package; Galaxy tool outdated | Galaxy tool using new BandageNG
| FASTK | Evaluation | description | no conda package | conda package

Table: Note that table caption is automatically numbered.

A figure is added with:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use CiTO annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate why you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* discusses
* extends
* agreesWith
* disagreesWith

# Results


# Discussion

...

## Acknowledgements

...

## References
