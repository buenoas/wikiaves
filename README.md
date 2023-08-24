# wikiaves
Repositório com dados e funções para extração de listas de espécies do WikiAves.

* **municipios_ibge.txt:** O arquivo corresponde à tabela de atributos do shapefile da Malha Municipal do Brasil (IBGE, 2022), baixado pelo link https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2022/Brasil/BR/BR_Municipios_2022.zip em 2023-08-24. O arquivo "BR_Municipios_2022.shp" foi aberto no programa QGIS (versão 3.28.3), convertido para o CRS "EPSG:4326 - WGS 84" e exportado no formato "ESRI Shapefile". O shapefile exportado foi aberto no programa R e, com a função `sp::coordinates`, foi obtido o centroide das coordenadas geográficas.
