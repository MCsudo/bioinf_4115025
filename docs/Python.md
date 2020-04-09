# Python
Este es el contenido que iremos revisando en el curso, donde se trabajará en un contexto general y revisión de 15-20 minutos por concepto con 30 minutos de una actividad. 

RA: Lograr construir funciones en código python.
EV: Crear un cuaderno de python para responder a un requerimiento relacionado con biología.

# Python-Conda-Jupyter.
En esta sesión configuraremos un entorno de programación para aprender a programar en python, prototipar nuestro código y compartir nuestros trabajos.

## Conceptos clave:
* Python
* Conda
* Jupyter

## Lecturas
* [Entorno Conda](https://docs.conda.io/projects/conda/en/latest)
* [Instalando miniconda](https://docs.conda.io/en/latest/miniconda.html)
* [Jupyter](https://jupyter.org)
* [Instalando Jupyter](https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter)

## Actividades
* Habilitar entorno de programación
* Ejecutar código Python en cuaderno Jupyter

# Variables
## Conceptos clave:
* cadenas
* enteros
* flotantes
* contenedores
* operaciones

## Lecturas
* [Tutorial Oficial Python 3 - Pag8-16](http://docs.python.org.ar/tutorial/pdfs/TutorialPython3.pdf)

## Actividades
* Crear cuaderno jupyter que incluya operaciones con las variables.

# Controles de Flujo
* if, elif, else
* for, range
* while

## Lecturas
* [Tutorial Oficial Python 3 - Pag16-18](http://docs.python.org.ar/tutorial/pdfs/TutorialPython3.pdf)

# Funciones
## Concepctos clave:
* def
* variables
* operaciones con funciones.

## Lecturas
* [Tutorial Oficial Python 3 - Pag20-25](http://docs.python.org.ar/tutorial/pdfs/TutorialPython3.pdf)

## Actividades

# Estructura de Datos
## Conceptos clave:
* listas
* tuplas
* diccionarios
* instrucción
* iteración

## Lecturas
* [Tutorial Oficial Python 3 - Pag26-35](http://docs.python.org.ar/tutorial/pdfs/TutorialPython3.pdf)

## Actividades
* Operaciones con estos elementos
* Creación de funciones para explorar datos

# Extras [Opcional]

## Python: Gráficos.
Los gráficos son una herramienta poderosos para comunicar y realizar análisi de nuestros datos. Estos son módulos que entregan herramientas para poder realizar gráficos con nuestros datos, estos pueden estar embebidos en un cuaderno jupyter, y así poder complementar nuestros análisis de datos.
    - [Matplotlib])(https://matplotlib.org) es la biblioteca principal de gráficado y es de un nivel más bajo (es decir necesita configurar cada detalle de los gráficos).
    - [Seaborn](https://seaborn.pydata.org) esta biblioteca está diseñada para utilizar tablas (DataFrame) desde Pandas y posee un nivel rápido para obtener gráficos de análisis.
    - [Altair](https://altair-viz.github.io) esta biblioteca es la de más alto nivel y nos permite gráficar desde yablas de Pandas, combinar gráficos e interactividad.

## Python: Matemáticas.
Python posee dos biblioteca que continene modulos para realizar operaciones matemáticas, desde alegbra, cálculo a trigonometría. La bibloteca basa es numpy, que es perfectamente complementada por la biblioteca de python científico que posee funciones de análisis de más alto nivel. Para el trabajo con grafos se recomienda networX.
- [Numpy](https://numpy.org)
- [Scipy](https://www.scipy.org)
- [NetworkX](https://networkx.github.io)

## Python: Estadísticas
Los análisis estadísticos de los datos son muy importantes para poder realizar conclusiones d enuetsros datos, y enconjunto con los gráficos osn herramientas esenciales para el análisis de datos. En python existen varios módulos que realizan estos análisis desde los de más bajo nivel como numpy y scipy, hasta aquellos de más alto nivel, es decir que nos entregan tablas y análisis como statsmodels y pingouin. Otras herramientas de análisis estadísticos son Rstudio (interfaz para usar el lenguaje R que posee test estadisticos en investigación)y una herramienta simple, pero robusta llamda JASP.
- [Statsmodels](https://www.statsmodels.org)
- [Pingouin](https://pingouin-stats.org)
- [Rstudio](https://rstudio.com)
- [JASP](https://jasp-stats.org)

## Python: Inteligencia Artificial
La inteligencia artificial a tomado un gran protagonismo este último tiempo, principalmente por el dearrolla de la capacidad de comùta de los dispositivos ue utilizamos, donde se puede dearrollar su teoría, que provienes de 1950. Esta rama ha permeado varias áreas del desarrollo científico donde la bioinformática no e sla excepción, una revisón es descrita en:
* Inza, I., Calvo, B., Armañanzas, R., Bengoetxea, E., Larrañaga, P., & Lozano, J. A. (2010). Machine learning: an indispensable tool in bioinformatics. Methods in Molecular Biology (Clifton, N.J.), 593(Chapter 2), 25–48. http://doi.org/10.1007/978-1-60327-194-3_2

En python existen dos bibliotecas muy útiles:

- El aprendizaje automático (machine learning), que se utiliza para entrenar modelos de clasificación o de agrupación. [Scikitlearn](https://scikit-learn.org)[Google Book](https://books.google.cl/books?id=GyBKDwAAQBAJ&printsec=frontcover) [Amazon Book](https://www.amazon.com/-/es/Cyrille-Rossant-ebook/dp/B079KBGPQC) [Github](https://github.com/ipython-books/cookbook-2nd-code) 

- El aprendizaje profunfo (deep learning), que se utiliza para entrenar modelos de reconocimiento de información desde mexclas de datos no procesados como imagenes, grabaciones, etc. [Pytorch](https://pytorch.org)

## Python: Datos desde la Web.
El webscrapping es una técnica para obtener datos desde sitios en internet, tablas e inclusos imágenes. Estos son mósulos que nos permiten conectarnos a distintos sitios en forma programable y buscar solo la información o datos relevantes y organizarlos en una estructura. Estos en conjunto con el usos de expresiones regulares (RE), es cómun a varios lenguajes entre ellos Python, es una valiosa herramienta para obtener datos estructurados, el primer pasos para realizar un ánalisis de datos robusto.
    - [Requests](https://requests.readthedocs.io)
    - [BeautyfulSoup](https://www.crummy.com/software/BeautifulSoup)
    - [Expresiones Regulares](https://docs.python.org/3/library/re.html)

[Lectura 01](https://www.learndatasci.com/tutorials/ultimate-guide-web-scraping-w-python-requests-and-beautifulsoup/) [Github](https://github.com/LearnDataSci/article-resources/tree/master/Ultimate%20Guide%20to%20Web%20Scraping)

## Python: Interfaz Gráfica.
La interfaz gráfica de usuario es útil para poder explorar análisis o prestar algún servicio guiando sobre los requerimientos de datos y los parámetros utilizados. Para poder aprender a construir interfaz gráfica hay que comprender bien la profgramación orientada a objetos y el uso de clases, ya que cada ventana o boton es un objeto con atributos que están descritos en una clase. Existen varias bibliotecas para esto como kivy, wxglade, entre otras. Tkinter a demostrado ser una de las más robustas y multiplataforma de las que hemos probado.
    - [Tkinter](https://docs.python.org/3/library/tk.html)