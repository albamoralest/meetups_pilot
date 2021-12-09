# MEETUPS PILOT

Extracting information of musical artist from Wikipedia pages.

The initial collection of Wikipedia pages can be found here: https://github.com/albamoralest/scrappingWikipediaMusicBiographies

In this pilot we extract people, places, events and time entities from 543 wikipedia pages.

Step 1: cleaning and organising information by sentences

Step 2:
  
  2.1 extracting entities using DBpedia spotlight
  
  2.2 extracting time expressions using nltk
  
The dataset is organised by folders:

The folder extractedEntities contains the final result of the extraction pipeline

Here you will find a csv named by the wikipedia id of the authors. In the file "infoBiographies.csv" you will find the name of the person related with the wikipedia page, the date of birth
