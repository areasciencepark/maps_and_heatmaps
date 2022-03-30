# maps_and_heatmaps
maps and heatmaps in Python

some preliminary tests on maps and heatmaps
es1_density_maps: examples of density maps 
es2_maps: examples of maps with border and colorfill

subfolders:
* "maps": a collection of maps (EU, ITA, FVG)
* "data" sample datasets for testing

link to download datasets:
EUROSTAT: countries and regions
https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/administrative-units-statistical-units/nuts?msclkid=fbe760f3af7411eca894829840064600

ISTAT: italian municipalities and regions
Shapefile https://www.istat.it/it/archivio/222527 
Names and codes https://www.istat.it/storage/codici-unita-amministrative/Elenco-comuni-italiani.csv 

In this notebook we use SHAPEFILE and coord.system EPSG 4326 
of course TopoJSON and geoJSON are available

Sample output: [sample_output.png]


TODO:

1. load maps SHP / JSON / CSV di 
    * Italy nuts2 / nuts3 (Comuni + CODICE ISTAT comune e regione)
    * EU Countries nuts1/nuts2 (+ codes)

2. prepare standard code to produce JSON and CSV

3. load some test data (e.g. 1000 rows, only syntetic data / samples)

4. make a map with background (border+color fill) and superimposed heatmaps

5. load code and data in powerbi

