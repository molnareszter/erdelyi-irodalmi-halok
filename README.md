# Network analysis of the Hungarian literary ecosystem in Transylvania (1835-2010)
**EszterMolnar_slides_HU.pdf**: Presentation about the project in Hungarian (presented at the National Scientific Students' Associations Conference - OTDK).
#### Data:
- **lexikon.json**: original database. Built a parser to download the Hungarian literary lexicon in Romania from: https://lexikon.kriterion.ro/
- **lexikon.xlsx**: cleaned data. Manually categorized all 5262 articles.  
&emsp; Categories:  
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
#### Gephi:
  1. nodes.xlsx  
Nodes in the entire network.  
  3. links.xlsx  
Connections in the entire network.  
#### Networks:  
  - **communities**: communities in the entire network and in the writers homogeneous network
  - **ego-networks**: egocentric networks of TOP 8 periodicals and TOP 5 societies
  - **full.tif**: entire network
  - **full_without6degree.tif**: entire network with degree of nodes >= 6
  - **periodicals.tif**: homogeneous network of periodicals
  - **periodicals_label.tif**: homogeneous network of periodicals with top actors' labels
  - **periodicals_top8.tif**: connections of TOP8 periodicals by degree in the heterogeneous network of periodicals-writers (for more details: *EszterMolnar_slides_HU.pdf*)
  - **scientific_writers.tif**: homogeneous network of scientific writers.
  - **societies_top5.tif**: connections of TOP5 societies by degree in the heterogeneous network of periodicals-writers (for more details: *EszterMolnar_slides_HU.pdf*)
  - **writers.tif**: homogeneous network of writers
  - **writers_label.tif**: homogeneous network of writers with top actors' labels
  - **writers_periodicals.tif**: heterogeneous network of periodicals-writers
  - **writers_periodicals_without8degree.tif**: heterogeneous network of periodicals-writers with degree of nodes >= 8
  - **writers_societies.tif**: heterogeneous network of societies-writers.

