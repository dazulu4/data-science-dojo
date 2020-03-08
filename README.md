DOJO: Python y R
===
Repositorio con material para realización del **DOJO** básico de Python y R con introducción ML

## Instalación de Python y R sin Anaconda
Con el fin de aprender, vamos a realizar la instalación de los productos sin Anaconda para de esta forma comprender el proceso de instalación en ambientes no developer:

#### Python 3.7
* Realizar la instalación de Python <a href="https://www.python.org/downloads/windows/" target="_blank">3.7.x</a>. Siga el wizzard de instalación y al final verifique que en la variable de ambiente **PATH** se encuentra la rutan *bin* de Python.
* Realizar la instalación de Jupyter Notebook. Abra una consola **CMD** y lance el comando **pip**; si el programa responde proceda con la  instalación:
  * Actualizar la instalación de pip a la última versión:
  ```
  python -m pip install --upgrade pip
  ```
  * Realizar la instalación del componente Notebook:
  ```
  pip install notebook
  ```
  * Realizar la instalación del componente Jupyter:
  ```
  pip install jupyter
  ```
* Valide la instalación anterior lanzando el comando **jupyter notebook** en la consola **CMD**, se debe abrir el navegador por defecto y se debe poder visualizar los archivos del directorio actual.

#### R 3.5 for Windows
* Realizar la instalación de R <a href="https://cran.r-project.org/bin/windows/base/" target="_blank">3.5.x</a>. Siga el wizzard de instalación y al final verifique que en la variable de ambiente **PATH** se encuentra la ruta *bin* de la instalación de R.
* Instalar el Kernel de R para Jupyter Notebook. Siga las instrucciones siguientes:
  * Ingrese en la consola de R desde CMD ejecutando el comando **R**.
  * Realiza la instalación del paquete para configuración del Kernel:
  ```
  install.packages('IRkernel')
  ```
  * Ejecuta el comando de configuración del Kernel para el usuario actual:
  ```
  IRkernel::installspec()
  ```
  * Ejecuta el comando de configuración del Kernel para todos los usuarios:
  ```
  IRkernel::installspec(user = FALSE)
  ```
  * Cierre la consola de R utilizando **quit()** o **Ctrl+d**.
  * Ejecuta el comando **jupyter notebook**. Cuando habra el home de jupyter haz clic en *New* y verifica que aparezca la opción **R**. Esto quiere decir que el Kernel fue instalado correctamente.

#### Visual Studio Code (*Opcional*)
* Realizar la instalación de Visual Studio Code *(Opcional)*. Descargue e instale el producto, la url para descarga es la siguiente: <a href="https://code.visualstudio.com/download" target="_blank">code.visualstudio.com</a>.
* Abra el IDE y realice la instalación de los plugins Python que desee. Los recomendados son los siguientes: Python extension for Visual Studio Code, R support for Visual Studio Code, Code Runner (Ejecutor de scripts en cualquier lenguaje).

## Instalación de Python y R con Anaconda
Ver manual de instalación: <a href="/install-python-R-windows10.pdf" target="_blank">install-python-R-windows10.pdf</a>

## Creación Variables de Ambiente
Verifica que la variable de ambiente **Path** contenga las rutas correspondiente a los *bin* de Python (o Anaconda) y R. Ejemplo:
```
PATH=%PATH%;D:\Programas\Anaconda3;D:\Programas\Anaconda3\Library\bin;D:\Programas\Anaconda3\Scripts;D:\Programas\R\R-3.5.0\bin\x64
```

## Sincronización del Repositorio GitHub
1. Clona el repositorio:
```
git clone https://github.com/dazulu4/data-science-dojo.git
```
2. Ingresa en el directorio de trabajo
```
cd data-science-dojo
```

## Ejecución de Documentos Jupyter
Sobre el directorio **data-science-dojo** ejecute el comando:
```
jupyter notebook
```

## Ejercicios Básicos de Python
> * [P01-uso-interactivo.ipynb](P01-uso-interactivo.ipynb)
> * [P02-programacion.ipynb](P02-programacion.ipynb)
> * [P03-extraccion.ipynb](P03-extraccion.ipynb)
> * [P04-transformacion.ipynb](P04-transformacion.ipynb)
> * [P05-visualizacion.ipynb](P05-visualizacion.ipynb)

## Ejercicios Básicos de R
> * [R01-uso-interactivo.ipynb](R01-uso-interactivo.ipynb)
> * [R02-programacion.ipynb](R02-programacion.ipynb)
> * [R03-extraccion.ipynb](R03-extraccion.ipynb)
> * [R04-transformacion.ipynb](R04-transformacion.ipynb)
> * [R05-visualizacion.ipynb](R05-visualizacion.ipynb)

## Ejercicios Avanzados de Python (ML)
> * Pendiente

## Ejercicios Avanzados de R (ML)
> * Pendiente
