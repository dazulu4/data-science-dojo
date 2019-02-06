DOJO: Python y R
===
Repositorio con material para realización del **DOJO** básico de Python y R con introducción ML

## Instalación de Python y R sin Anaconda
Con el fin de aprender, vamos a realizar la instalación de los productos sin Anaconda para de esta forma comprender el proceso de instalación en ambientes no developer:

1. Realizar la instalación de Python [3.7.x](#https://www.python.org/downloads/windows/). Siga el wizzard de instalación y al final verifique que en la variable de ambiente **PATH** se encuentra la rutan *bin* de Python
2. Realizar la instalación de Jupyter Notebook. 
2.1. Abra una consola **CMD** y lance el comando **pip**; si el programa responde proceda con la  instalación según el manual en [jupyter.org/install](#https://jupyter.org/install)
2.2. Valide la instalación anterior lanzando el comando **jupyter notebook** en la consola **CMD**, se debe abrir el navegador por defecto y se debe poder visualizar los archivos del directorio actual.
3. Realizar la instalación de Visual Studio Code. *(Opcional)*
3.1. Descargue e instale el producto, la url para descarga es la siguiente: [code.visualstudio.com](#https://code.visualstudio.com/download)
3.2. Abra el IDE y realice la instalación de los plugins Python que desee. Los recomendados son los siguientes:
* Python extension for Visual Studio Code
* R support for Visual Studio Code
* Code Runner (Ejecutor de scripts en cualquier lenguaje)

## Instalación de Python y R con Anaconda
Ver manual de instalación: [install-python-R-windows10.pdf](https://github.com/dazulu4/sura-dojo-ml/blob/master/install-python-R-windows10.pdf)

## Creación Variables de Ambiente
Verifica que la variable de ambiente **Path** contenga las rutas correspondiente a los *bin* de Python (o Anaconda) y R. Ejemplo:
```
PATH=%PATH%;D:\Programas\Anaconda3;D:\Programas\Anaconda3\Library\bin;D:\Programas\Anaconda3\Scripts;D:\Programas\R\R-3.5.0\bin\x64
```

## Sincronización del Repositorio GitHub
1. Clona el repositorio:
```
git clone https://github.com/dazulu4/sura-dojo-ml.git
```
2. Ingresa en el directorio de trabajo
```
cd sura-dojo-ml
```

## Ejecución de Documentos Jupyter
Sobre el directorio **sura-dojo-ml** ejecute el comando:
```
jupyter notebook
```

## Ejercicios Básicos de Python
> * P01-uso-interactivo.ipynb
> * P02-programacion.ipynb
> * P03-extraccion.ipynb
> * P04-transformacion.ipynb
> * P05-visualizacion.ipynb

## Ejercicios Básicos de R
> * R01-uso-interactivo.ipynb
> * R02-programacion.ipynb
> * R03-extraccion.ipynb
> * R04-transformacion.ipynb
> * R05-visualizacion.ipynb

## Ejercicios Avanzados de Python (ML)
> * Pendiente

## Ejercicios Avanzados de R (ML)
> * Pendiente
