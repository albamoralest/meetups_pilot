---
container-id: meetups-pilot
name: Musical MEETUPS
type: Project
description: MEETUPS Pilot container with all the elements that support the knowledge extraction of historical meetups
work-package: 
- WP4
pilot:
- MEETUPS
project: polifonia-project
bibliography:
- main-publication: "Morales Tirado, Alba; Carvalho, Jason; Mulholland, Paul and Daga, Enrico (2023). Musical Meetups: a Knowledge Graph approach for Historical Social Network Analysis. In: Proceedings of the ESWC 2023 Workshops and Tutorials, Semantic Methods for Events and Stories (SEMMES)."
funder:
- name: European Commission H2020
  url: https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/programmes/h2020
  grant-agreement: GA101004746
credits: "This project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement GA101004746. The communication reflects only the author’s view and the Research Executive Agency is not responsible for any use that may be made of the information it contains."
has-part:
- meetups-knowledge-graph
- meetups-ontology
- meetups-data-cleaning
- meetups-themes
- meetups-entity-recognition
- meetups-time-extraction
- meetups-corpus-collection
- meetups-coreference
- meetups-hm-identification
---

# MEETUPS PILOT

[![DOI](https://zenodo.org/badge/436452967.svg)](https://zenodo.org/badge/latestdoi/436452967)

## People and music: exploring their encounters over centuries

This pilot focuses on supporting music historians and teachers by providing a Web tool that enables the exploration and visualisation of encounters between people in the musical world in Europe from c.1800 to c.1945, relying on information extracted from public domain books such as biographies, memoirs and travel writing, and open-access databases. These encounters will be explored in a timeline and map interface and may reveal unexpected connections and relationships that cast new light on aspects of European music history. The tool will provide persistent, citable identifiers in order to support referencing in scholarship outputs.

## Description

In this pilot, we extract people, places, events and time entities from 33.309 Wikipedia pages.

Components related to the KG.
1. Meetups Ontology. The framework to build the Musical Meetups Knowledge Graph [Meetups Ontology](https://github.com/polifonia-project/meetups-ontology)
2. Meetups Knowledge Graph. It contains the structured data extracted using a knowledge extraction pipeline to obtain evidence of artists' encounters throughout history. [Musical Meetups Knowledge Graph](https://github.com/polifonia-project/meetups-knowledge-graph)
3. Meetups Corpus. The repository of the Meetups corpus, Wikipedia pages collected in text format of a list of musical artist. [Meetups Corpus Collection](https://github.com/polifonia-project/meetups_corpus_collection)

## Meetups Ontology description

## Meetups Knowledge Extraction description

![KG extraction pipeline](https://github.com/polifonia-project/meetups-knowledge-graph/blob/17bbb79cf1ee3f7c04ab9a60a339b350cf6fe1b7/diagrams/meetups-pipeline.png "KG extraction pipeline")

Step 1: cleaning and organising information by sentences

Step 2:
  
  2.1 extracting entities using DBpedia spotlight
  
  2.2 extracting time expressions using nltk
  
Folders organise the dataset:

The folder extractedEntities contains the final result of the extraction pipeline

Here you will find a csv named by the wikipedia id of the authors. In the file "infoBiographies.csv" you will find the name of the person related with the wikipedia page, the date of birth

![MEETUPS software-tools](https://github.com/polifonia-project/meetups-knowledge-graph/blob/b993d1650df723723801673d0fa220de0d962b22/diagrams/meetups-software_tools.png)
