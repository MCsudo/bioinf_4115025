# Bioinformatica y Estructura Macromolecular - 4115025
- **Profesor: Dr. Alexis Salas B.**
- **Mágister de Bioquímica y Bioinformática**
- **Universidad de Concepción - Chile**

# Instrucciones Iniciación
*Se recomienda encarecidamente instalar linux en su computador, para esto se puede instalar una versión de linux, realizar una partición (se requiere buen computador i7), habilitar la terminal linux en Mac o en Windows (sólo en 10). Esto lo veremos en la [primera clase](Linux.md/#Linux)*.

Este repositorio puede ser clonado en su computador con:
git clone https://github.com/labnanocell/bioinf_4115025.git
[¿Cómo instalar GIT en mi computador?](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Instalaci%C3%B3n-de-Git)


Las clases presenciales comenzarán el Miércoles 15 de Abril en la plataforma CANVAS de la UdeC.

# Syllabus

## Descripción del curso
Curso Teórico-Práctico que incorpora las competencias requeridas para poder realizar análisis bioinformáticos de datos experimentales desde: 

* Base de trabajo en entornos linux.
* Programación en lenguaje python.
* Análisis de secuencias biológicas. 
* Análisis de estructural bioinformático.

Los datos de origen biológico provenientes desde secuencias de ácidos nucleicos y proteínas son analizados por metodologías de la biología computacional con aplicaciones en bioquímica, biología molecular, ingeniería de proteínas y biotecnología. Las actividades semanales son programadas con una revisión bibliográfica desde revistas bioinformáticas y los talleres son realizados en la plataforma Jupyter con python para reforzar las habilidades de pensamiento crítico y de programación computacional, respectivamente.

Esta asignatura aporta a las siguientes competencias del perfil de egreso del magíster en Bioquímica y Bioinformática:

1. Analizar y seleccionar en forma crítica información proveniente de fuentes diversas y validadas para fundamentar la investigación y formular argumentos sólidos que permitan tomar decisiones. 
2.	Comunicar resultados y hallazgos de la investigación, mediante el manejo responsable de la información en sus diferentes modalidades, ya sea en forma oral, escrita o a través de los medios y tecnologías de la información y comunicación

## Tipos de Actividades

* [Planificación de Contenido.](#curriculum) Entrega de contenidos en clases sincrónicas y asincrónicas, documento de lecturas.
* [Investigar y Analizar.](Journal.md) Presentación de artículos científicos.
* [Proyecto.](Project.md) Se desarrollará un proyecto en el curso que será diseñado para tributar en la tesis que se realizará para desarrollar un obejtivo bioinformático.

## Curriculum

Este es el contenido que iremos revisando en el curso, donde se trabajará en un contexto general y revisión de 15-20 minutos por concepto con 30 minutos de una actividad. 

- [Mes 1: Entorno de Sistema Operativo](Linux.md#entorno-de-sistema-operativo)
  * [Linux.](Linux.md#linux)
  * [SSH.](Linux.md#ssh)
  * [Computación de alto rendimiento.](Linux.md#computaci-n-de-alto-rendimiento)
  * [Extras [Opcional]](Linux.md#extras--opcional-)
- [Mes 2: Programando en Python](Python.md#python)
  * [Python-Conda-Jupyter.](Python.md#python-conda-jupyter)
  * [Variables](Python.md#variables)
  * [Contenedores](Python.md#contenedores)
  * [Controles de Flujo](Python.md#controles-de-flujo)
  * [Funciones](Python.md#funciones)
  * [Extras [Opcional]](Python.md#extras)
- [Mes 3: Análsis de Secuencias Biológicas](Sequences.md#secuencias)
  * [Módulos Python Bioinformáticos](Sequences.md#m-dulos-python-bioinform-ticos)
  * [Descripción de secuencias](Sequences.md#descripci-n-de-secuencias)
  * [Evolución Similaridad](Sequences.md#evoluci-n-similaridad)
  * [Alineamiento](Sequences.md#alineamiento)
  * [Filogenia Molecular](Sequences.md#filogenia-molecular)
  * [Diseño de partidores](Sequences.md#dise-o-de-partidores)
  * [Extras [Opcional]](Sequences.md#extras)
- [Mes 4: Análisis de Estructura de Proteínas](Estructures.md#estructura)
  * [PDB.](Estructures.md#pdb)
  * [Modelling.](Estructures.md#modelling)
  * [Docking.](Estructures.md#docking)
  * [Dinámica Molecular.](Estructures.md#din-mica-molecular)
  * [Extras.](Estructures.md#extras)

## Modalidad de Clases Online

Las clase serán online (Escenario Pandemia Covid-19), para ello se utilizará la plataforma [Canvas](https://www.instructure.com/canvas/es), [Microsoft Team](https://www.microsoft.com/es-es/education/products/teams) y [Github](https://github.com/). Las presentaciones de evaluación de los artículos serán a través de estas plataformas.

## Actividades de Evaluación

* Presentación de búsqueda bibliográfica/seminario semanal (25%): Dado un journal específico cada estudiante deberá enviar un día antes del miércoles un resumen del artículo seleccionado de una hoja y una ppt de 4-6 diapositivas. Un estduiante por clase presentará en forma aleatoria.
* Presentación de las tareas (25%): Las tareas de los talleres serán revisadas por los alumnos ayudantes, el promedio de todos estos trabajos será esta nota.
* Proyecto integrador (30%): Este proyecto deberá desarrollarse durante el semestre e incluye una presentación de 20 minutos de un tema y la aplicación de un script en Python. El escrito ponderará un 10%, el script 10%, y la presentación un 10%
* Prueba final de conocimientos (20%): Examen electrónico de la asignatura.

## Bibliografía Recomendada

*	Antao, Tiago. Bioinformatics with Python Cookbook: Learn How to Use Modern Python Bioinformatics Libraries and Applications to Do Cutting-Edge Research in Computational Biology, 2nd Edition. Edición: 2. Packt Publishing, 2018. ISBN-13: 978-1789344691. [Google Book](https://books.google.cl/books?id=ii59DwAAQBAJ&printsec=frontcover) | [Amazon Book](https://www.amazon.com/-/es/Tiago-Antao-ebook/dp/B07FNYFS9V) | [Github](https://github.com/PacktPublishing/Bioinformatics-with-Python-Cookbook-Second-Edition) 
*	Bessant, Conrad, Darren Oakley, and Ian Shadforth. Building Bioinformatics Solutions 2nd Edition. Edición: 2. Oxford, United Kingdom ; New York, NY, United States of America: Oxford University Press, 2014. ISBN-13 978-0199658565. [Google Book](https://books.google.cl/books?id=vkueAgAAQBAJ&printsec=frontcover) | [Amazon Book](https://www.amazon.com/Building-Bioinformatics-Solutions-Conrad-Bessant/dp/0199658560)
*	Lesk. Introduction To Bioinformatics. Edición: 5. Oxford, United Kingdom: Oxford University Press, 2019. ISBN-13: 978-0198794141. [Google Book](https://books.google.cl/books?id=xYmcAQAAQBAJ&printsec=frontcover) | [Amazon Book](https://www.amazon.com/-/es/Lesk/dp/0198794142)
*	Rocha, Miguel ; Ferreira, Pedro G.: Bioinformatics Algorithms: Design and Implementation in Python. 1 edition. Aufl. Waltham, MA : Academic Press, 2018 — ISBN 978-0-12-812520-5. [Google Books](https://books.google.cl/books?id=rkc1DwAAQBAJ&printsec=frontcover) | [Amazon Book](https://www.amazon.com/-/es/Miguel-Rocha/dp/0128125209)
*	Stevens, Tim J. ; Boucher, Wayne: Python Programming for Biology: Bioinformatics and Beyond. 1 edition. Aufl. Cambridge, United Kingdom : Cambridge University Press, 2015 — ISBN 978-0-521-72009-0 [Google Book](https://books.google.cl/books?id=oQNoBgAAQBAJ&printsec=frontcover) | [Amazon Book](https://www.amazon.com/-/es/Tim-J-Stevens-ebook/dp/B00SYVZ3WC/ref=sr_1_1?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=Python+Programming+for+Biology%3A+Bioinformatics+and+Beyond&qid=1586376277&s=books&sr=1-1)
*	Loging, W. T. (Hrsg.): Bioinformatics and Computational Biology in Drug Discovery and Development. Reprint edition. Aufl. S.l. : Cambridge University Press, 2018 — ISBN 978-1-108-46115-3. [Google Book](https://books.google.cl/books?id=6Bd-CwAAQBAJ&printsec=frontcover) | [Amazon Book](https://www.amazon.com/-/es/William-T-Loging-ebook/dp/B01B1G83SM/ref=sr_1_1?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=Bioinformatics+and+Computational+Biology+in+Drug+Discovery+and+Development&qid=1586376386&s=books&sr=1-1)