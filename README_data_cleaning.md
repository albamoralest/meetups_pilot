---
id: 
name: MEETUPS preparation - data cleaning
brief-description: This tool is part of the corpus preparation process and it is used to clean data collected from Wikipedia. 
type: Software
release-date: 20/06/2022
release-number: v1.0
work-package:
- WP3
pilot: MEETUPS
keywords:
- Wikipedia
- Music
licence: GPLv3
release link:
  - 
credits:
  - https://github.com/albamoralest
---

# MEETUPS Corpus preparation: data cleaning
### MEETUPS Corpus preparation: Cleaning data collected from Wikipedia web pages of people in the music scene in Europe


MEETUPS data cleaning is a tool developed using Python and Jupyter Notebook. This software prepares the biographies (collected as text files) in https://github.com/polifonia-project/meetups_corpus_collection for the next step in the extraction of historical meetups process.

- Use the Wikipedia authors' webpages collected in https://github.com/polifonia-project/meetups_corpus_collection
- Clean text blank lines, sections with no historical meetups data
- Organise the text in sentences as the main unit to extract meetups information


#### Information on installation and setup

  - Run Jupyter Notebook 01_CleaningText.ipynb

#### Details of the data

    Code location:
    
    |_ 01_CleaningText.ipynb
    
    Raw corpus location:
    
    |_ text_dataset/            
    
    Clean text location:
    
    |_ cleanText/
    
    Index data location:
    
    |_ indexedParagraphs/
    |_ indexedSentences/
    
    |_ README_data_cleaning.md
    

DOI:

    TODO