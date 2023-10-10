# Áreas turísticas de Galicia

En este repositorio se crea el un mapa de Galicia con las áreas turísticas que enseña [AEITG](https://aei.turismo.gal/es/portada) en su web.
![mapa](https://aei.turismo.gal/osdam/filestore/5/0/1/9/2_009f0b6c49152b7/50192scr_17eab49f7d0c570.jpg)


# Repositorio
Para utilizar el archivo **environment.yml** hay que usar:
```sh
conda env create -f environment.yaml
```
[**data**](./data): Aquí se encuetran el shapefile de los municipios y el excel con la agrupación de los municipios.   
[**src**](./src): Aquí se encuentra el código utilizado   
[**out**](./out): Aquí se encuentran los archivos generados

# Fuentes
[Mapa de municipios](https://opendata.esri.es/datasets/53229f5912e04f1ba6dddb70a5abeb72_0/explore?location=37.043808%2C9.456355%2C5.62)   
[Agrupación de municipios](https://aei.turismo.gal/osdam/filestore/5/0/1/9/3_985604b31214d44/50193_8913d029d25d9f2.xls)