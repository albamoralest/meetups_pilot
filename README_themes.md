---
component-id: meetups-themes
type: Software
name: MEETUPS themes
description: "This tool is part of the meetups knowledge extraction pipeline that classifies text according to music themes of interes."
work-package:
- WP4
pilot:
- MEETUPS
project: polifonia-project
resource: https://github.com/polifonia-project/meetups_pilot/blob/main/MeetupType_applyClassifier.ipynb
release-date: 20/07/2022
release-number: v0.1
release-link: https://github.com/polifonia-project/meetups_pilot/releases/tag/v0.2
doi: https://zenodo.org/badge/latestdoi/436452967
changelog: https://github.com/polifonia-project/meetups_pilot/releases/tag/v0.2
licence: Apache 2.0
copyright: "Copyright (c) 2023 MEETUPS @ The Open University"
contributors:
- Alba Morales Tirado <https://github.com/albamoralest>
- Enrico Daga <https://github.com/enridaga>
related-component:
- persona:
  - Ortenz
  - David
  - Sophie
---

# MEETUPS Corpus preparation: data cleaning
### MEETUPS Corpus preparation: Cleaning data collected from Wikipedia web pages of people in the music scene in Europe


MEETUPS data cleaning is a tool developed using Python and Jupyter Notebook. This software prepares the biographies (collected as text files) in https://github.com/polifonia-project/meetups_corpus_collection for the next step in the extraction of historical meetups process.

- Use the Wikipedia authors' webpages collected in https://github.com/polifonia-project/meetups_corpus_collection
- Clean text blank lines, sections with no historical meetups data
- Organise the text in sentences as the main unit to extract meetups information


## Information on installation and setup

  - Run Jupyter Notebook MeetupType_applyClassifier.ipynb

## Details of the data

    

DOI:

[![DOI](https://zenodo.org/badge/436452967.svg)](https://zenodo.org/badge/latestdoi/436452967)
