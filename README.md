# Network analysis of the Hungarian literary ecosystem in Transylvania (1835-2010)
###### EszterMolnar_slides_HU.pdf  
My presentation about the project in Hungarian (presented at the National Scientific Students' Associations Conference - OTDK).
###### Data:
  1. lexikon.json  
Original database. Built a parser to download the Hungarian literary lexicon in Romania from: https://lexikon.kriterion.ro/
  2. lexikon.xlsx  
Cleaned data. Manually categorized all 5262 articles.  
Categories:  
a - almanac  
bp - book publisher  
bs - book series, novel series, lexicon, encyclopedia  
co - codex  
f - folklore educator,  ethnomusicologist   
lh - local historian  
n - not relevant (other form of art or industry)  
p - periodical, journal, excerpt, newspaper, student paper, pamphlet   
s - literary societies, associations  
sw - scientific writer  
w - writer, poet, editor, publicist, translator, and journalist   
###### Gephi:
  1. nodes.xlsx  
Nodes in the entire network.  
  3. links.xlsx  
Connections in the entire network.  
###### Networks:  
  - Communities: communities in the entire network and in the writers homogeneous network.
  - Ego-networks: egocentric networks of TOP 8 periodicals and TOP 5 societies.
  - full.tif  
Entire network.  
  - full_without6degree.tif  
Entire network with degree of nodes >= 6.
  - periodicals.tif  
Homogeneous network of periodicals. 
  - periodicals_label.tif  
Homogeneous network of periodicals with top actors' labels.
  - periodicals_top8.tif  
Connections of TOP8 periodicals by degree in the heterogeneous network of periodicals-writers. (for more details: EszterMolnar_slides_HU.pdf)
  - scientific_writers.tif  
Homogeneous network of scientific writers.
  - societies_top5.tif  
Connections of TOP5 societies by degree in the heterogeneous network of periodicals-writers. (for more details: EszterMolnar_slides_HU.pdf)
  - writers.tif  
Homogeneous network of writers.
  - writers_label.tif  
Homogeneous network of writers with top actors' labels.
  - writers_periodicals.tif  
Heterogeneous network of periodicals-writers.
  - writers_periodicals_without8degree.tif  
Heterogeneous network of periodicals-writers with degree of nodes >= 8.
  - writers_societies.tif  
Heterogeneous network of societies-writers.

