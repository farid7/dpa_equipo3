#Data Product Architecture

##Integrantes
Ma. Fernanda Téllez Girón Enríquez  
Jorge Carlos Urteaga Reyesvera  
Ángel Farid Fajardo Oroz  
José Carlos Castro Montes  

## Parallel Download

	seq -f "%02g" 31 | parallel echo "http://data.gdeltproject.org/events/201612{}.export.CSV.zip"

