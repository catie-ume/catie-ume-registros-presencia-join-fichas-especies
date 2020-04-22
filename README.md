# Combinación de registros de presencia (DwC) con fichas de especies (PLIC)
Este repositorio contiene un _notebook_ de [Jupyter](https://jupyter.org/) para añadir elementos de datos del estándar [Plinian Core](https://github.com/tdwg/PlinianCore) de fichas de especies a un archivo de registros de presencia de especies del estándar [Darwin Core](https://github.com/tdwg/dwc).

El libro de notas utliza el lenguaje de programación [Python](https://www.python.org/) y la biblioteca [Pandas](https://pandas.pydata.org/), los cuales se manejan en un ambiente de [Conda](https://conda.io/).

## Clonación de este repositorio
```terminal
$ git clone https://github.com/catie-ume/registros-presencia-join-fichas-especies.git
```

## Datos de presencia
Como ejemplo, pueden usarse los datos contenidos en:  
[https://www.gbif.org/occurrence/download/0002762-200127171203522](https://www.gbif.org/occurrence/download/0002762-200127171203522)  
El archivo .ZIP debe descomprimirse y el archivo descomprimido con registros de presencia debe renombrarse como _occurrences.txt_ y colocarse en el subdirectorio _input/_.

## Creación y activación de un ambiente Conda
```terminal
# El ambiente solo debe crearse una vez
$ conda create -n presencia-join-fichas python=3 pandas jupyter

$ conda activate presencia-join-fichas
```

## Ejecución del _notebook_
En el directorio raíz del repositorio clonado:
```terminal
$ jupyter notebook
```
Con el navegador de Jupyter, debe abrirse el _notebook_ que está en el directorio principal.
