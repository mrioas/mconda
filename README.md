# mconda

Aqui realizaremos modificaciones de código con el fin de usar JULIA y Jupyter Notebook

## Objetivo

Resolver Método de inventario en Promedio Ponderado

## Sobre Julia

Si no lo tienes instalado, existen varias maneras de realizarlo, la que yo usé y si es su comodidad es lo pueden usar, se llama: choco install Julia

## El entorno

Miniconda
y su paquete estrella: conda install -c conda-forge notebook

Antes de lo anterior por una buena practica se recomienda crear un entorno virtual
para eso actualizaremos el repositorio oficial de conda conda-forge
conda update -n base -c defaults conda

el entorno se lo crea 
conda create -n myenv python=<python_version>

Y activamos el entorno

conda activate myenv


Se creará en la CLI que estes usando un nuevo comando: jupyter notebook

Este abrirá un navegador.


Siguiendo con las buenas prácticas haremos uso del control de versiones git

para eso debemos tener instalado, lo obviaremos por el momento

$ git clone ó si usas llaves de acceso via ssh {git@github.com:mrioas/mconda.git} si clonas por web y no quieres crear un push y pull de una nueva versión {https://github.com/mrioas/mconda.git}, existe de igual manera la versión Github CLI si usar github como tu repositorio de control de versiones.
