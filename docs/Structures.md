# Análisis de Estructura de Proteínas 
Los mecanimsos moleculares y celulares que permiten el metabolismo de nuestras células esta regulado por la función de genes que se traducen en proteínas. Las proteínas estan formadas por aminoácidos que se pliegan en una estructura tridimensional dando forma y funcionalidad, que con la flexibilidad de estas estructuras inmersas en un medio acuoso y sales, en conjunto con la interacción de otras proteinas, le otorgan la dinámica a los procesos vivos y el funcionamiento de estos en condiciones normales y patológicas. La compresión de estos mecanismos, su dinámica, es fundamental tanto en procesos biotecnológicos como en la preservación de la salud humana, así como de otros animales y plantas.

RA: Realizar análisis de secuencias de origen biológico.
EV: Desarrollar una función en python en cuaderno de programación para realizar una tarea asignada de análisis de estructura.

Este es el contenido que iremos revisando en el curso, donde se trabajará en un contexto general y revisión de 15-20 minutos por concepto con 30 minutos de una actividad. 

# Banco de Datos de Proteínas (PDB)
Las coordenadas de las estructura de proteínas son depositadas en el Banco de Datos de Proteínas, [PDB](https://www.rcsb.org). Estas coordenadas provienen principalmente de la determinación de mapas de densidad electrónica desde experimentos de [cristalografía de rayos X](https://www.youtube.com/watch?v=-6j7_xS5FAI), [resonancia nuclear para determinación de estructura de proteínas](https://en.wikipedia.org/wiki/Nuclear_magnetic_resonance_spectroscopy_of_proteins), de [modelamiento comparativo](https://en.wikipedia.org/wiki/Homology_modeling), y finalmente desde [crio-microscopía electrónica](https://en.wikipedia.org/wiki/Transmission_electron_cryomicroscopy). Un bioinformático debe conocer la estructura de un archivo PDB y generar visualizaciones tridimensionales de estas estructuras para realizar un análisis de estructura-función.

## Conceptos
* PDB format
* Descargar PDB
* Pymol Visualizar 3D
* NGLView en Jupyter

## Lecturas
[Bases de datos de estructuras de proteínas](https://doi.org/10.1016/B978-0-12-809633-8.20280-X)
[Historia del PDB](https://www.rcsb.org/pages/about-us/history)
[Visualización de proteínas](https://doi.org/10.1016/B978-0-12-809633-8.20283-5)
[Formato de un archivo PDB](http://www.wwpdb.org/documentation/file-format-content/format33/v3.3.html)
[Visualizador molecular Pymol](https://pymol.org)|[Conda](https://anaconda.org/schrodinger/pymol)
[Visualizador molecular NGLView](https://academic.oup.com/bioinformatics/article/34/7/1241/4721781)|[Github](https://github.com/arose/nglview)

## Actividades
* [Elegir una molécula del mes](http://pdb101.rcsb.org/browse)
* Instalar Pymol
* Descargar un archivo PDB en Pymol
* Visualizar el formato de su archivo
* Generar una vista del sitio activo
* Inscrustar una vista de una molécula en Jupyter

# Modelamiento de proteínas
La determinación de estructuras de proteínas es un proceso experimentalmente costoso en tiempo en dinero. Mientras desde análisi de filogenia y compararndo secuencias se pueden obtener secuencias con un alto porcentaje de identidad (>50%), usando la información de estos alineamiento se ha demostrado que es posible extrapolar esta estructura para reconstruir proteínas relacionadas. Esta técnica es muy utilizada por bioinformáticos, cuando se dispone de una estructura cristalizada y es homologa a nuestra proteína de interes. Muchas veces las proteínas cristalizados son de microorganismos y no humanas y con modelamiento comparativo se pueden calcular estas estructuras para realizar análisis de estructura-función. En los últimos años con el poder computacional que se dispone incluso se ha simulado con éxito el plegamiento de proteínas desde su secuencia primaria.    

## Conceptos
* [Algoritmos en modelamiento comparativo](https://doi.org/10.1016/B978-0-12-809633-8.20484-6)
* [Algoritmos es modelamiento *ab initio*](https://doi.org/10.1016/B978-0-12-809633-8.20321-X)
* [Evaluación del modelo](https://doi.org/10.1016/B978-0-12-809633-8.20282-3)

## Lecturas
[Modeller]([Modeller](https://salilab.org/modeller))
[Modelamiento básico con Modeller](https://salilab.org/modeller/tutorial/basic.html)
[ModFOLD](https://www.reading.ac.uk/bioinf/ModFOLD/index.html)

## Actividades
* Instalar Modeller
* Ejecutar modeler en Jupyter
* Realizar una búsqueda de moldes
* Construir un alineamiento en formato PIR
* Construir un modelo de proteína.
* Evaluar un modelo de una proteína.

# Cribado molecular.
La comunicación a nivel molecular y la transferencia de señales, fuerzas, e inclusive reconocimiento celular, esta gobernado por las fuerzas de interacción molecular, y el proceso de unión entre estas moléculas con una energía determinada se denomina cribado (*docking*) molecular. En biología estos procesos están involucrados en la transducción de señales, en el transporte de metabolitos, en el reconocimiento de sustratos, en la afinidad de anticuerpos, en la sinapsis, entre otrso; así como en la acción de practicamente todos los fármacos que modulan una respuesta biológica. El cribado molecular nos permite calcular mdoos de unión entre proteínas, seleccionar ligandos de una base de datos que se unirían a un receptor, evaluar la energía de unión.

## Conceptos
* Docking proteína-proteína
* Docking proteína-ligando
* Análisis de docking molecular

## Lecturas
* [Algoritmos de cribado molecular](https://doi.org/10.1016/B978-0-12-809633-8.20485-8)
* [Diseño de fármacos basado en estructura](https://doi.org/10.1016/B978-0-12-809633-8.20275-6)
* [Smina docking])(https://sourceforge.net/projects/smina/files)
* [Lightdock](https://lightdock.org)

## Actividades
* Realizar un docking molecular receptor-ligando con smina, analizar los resultados.
* Realizar un docking molecular proteína-proteína con lightdock, analizar los resultados.

# Simulaciones de dinámica molecular
Los procesos biológicos no son estáticos y la vida depende de la dinámica molecular al interior de la célula. Estos procesos respoden a las leyes de la mecánica estadística y la fisicoquímica, donde tempranamente se han desarrollado métodos para realizar simulaciones de ensambles termodinámicos que representan los componentes de la vida desde sus átomos y poder ver estos procesos en una resolución naométrica y en tiempos de femtosegundos. Con la potencia de cálculo computacional en sistemas distribuidos, tanto de cluster como en GPU, se ha logrado simular sistemas tan grandes como virus y ribosomas; mientras en sistemas más pequeños se han logrado simulaciones de milisengudos a segundos. Hoy estas simulaciones son parte de las herramientas que un bioinformático utiliza para analizar sistemas biológicos y nuevamente establecer relaciones de estructura-función.

* Simulaciones de dinámica molecular
* Campo de fuerza
* Ensambles
* Simulaciones
* Análisis de SDM

## Lecturas
[Simulaciones de dinámica molecular (SDM)](https://doi.org/10.1016/B978-0-12-809633-8.20284-7)
[SDM y diseño de fármacos](https://www.sciencedirect.com/science/article/pii/B9780128096338201544)

## Actividades
*

# Extras [Opcional].

## Módulos python
* [Prody](http://prody.csb.pitt.edu)
* [Biopandas](http://rasbt.github.io/biopandas)
* [MDanalysis](https://www.mdanalysis.org)
* [Pytraj](https://amber-md.github.io/pytraj/latest/index.html)

* [General MacroMocelecular I/O (GEMMI)](https://gemmi.readthedocs.io)
* Diseño de fármacos
* Evaluación del efecto de mutaciones en proteínas
