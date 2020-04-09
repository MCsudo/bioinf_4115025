# Entorno de Sistema Operativo
Este es el contenido que iremos revisando en el curso, donde se trabajará en un contexto general y revisión de 15-20 minutos por concepto con 30 minutos de una actividad. 

RA: Ejecutar software en un entorno linux-terminal.
EV: Crear una carpeta con su nombre/archivos y enviar un proceso a slurm, monitorear la ejecución y capturar los resultados.

# Linux. 

## Conceptos clave:
* Distribuciones.
* La terminal y el lenguaje bash. 
* Conocer la arquitectura de archivos en sistemas linux. 
* Aplicar comandos, parámetros y flags.
* Sistema de permisos.

## Lecturas:
[Curso Linux](http://www.ee.surrey.ac.uk/Teaching/Unix)

## Actividad:
Instalar algunas de las siguientes distribuciones de linux:
* [Ubuntu](https://ubuntu.com/)
* [MX Linux](https://mxlinux.org)
* [Mint](https://www.linuxmint.com)
* [Windows10 - Activar Terminal](https://medium.com/@rodritorrico/tutorial-como-activar-la-terminal-de-linux-en-windows-10-beta-52769b5cab7e)
* [MacosX - Habilitar terminal](https://www.freecodecamp.org/news/how-to-configure-your-macos-terminal-with-zsh-like-a-pro-c0ab3f3c1156/)

# Secure Shell (SSH).

## Conceptos clave:
* Usuarios e IP.
* Conexión por SSH y transferencia de archivos.
* Utilización de llaves
* Software relacionado: duck, filezilla, tmux.

## Lecturas
* [SSH protocol](https://en.wikibooks.org/wiki/OpenSSH/SSH_Protocols)
* [Laves SSH](https://www.digitalocean.com/community/tutorials/como-configurar-las-llaves-ssh-en-ubuntu-18-04-es)
* [Tmux](https://www.hostinger.es/tutoriales/usar-tmux-cheat-sheet/#Tmux-Cheat-Sheet-comandos-de-referencia-para-Tmux)

## Actividad
* Conexión a bender con la terminal.
* Transferir archivos con la terminal.
* Utilizar un administrador de archivos como Fillezila.
* Crear una sesión tmux.

# Computación de alto rendimiento.

## Conceptos claves:
* HPC. Cluster de computadoras
* Modulos. Software Científico
* SLURM. Sistema de encolamiento.
* OpenMP.
* MPI.

## Lecturas
* Inscribirse y realizar este curso: [High Performance Computing](https://school.scientificprogramming.io/course/scientific-computing-essentials/5)

## Actividad
* Conectarse al cluster
* Subir un trabajo en mpi
* Condigurar el archivo slurm
* Ejecutar y monitorear el trabajo.
* Obtener los resultados

# Extras [Opcional]

## Sitios Web
Configurar sitios web es una parte fundamental en el desarrollo de proyectos bioinformáticos hoy en día. Existen protocolos de comunicación entre los computadores como SSH, conocerlos nos permite configurar servidores y poder habilitar sitios web complejos que entreguen información o presten servicios. Conocer las bases de como funciona un servidor, como se monta un wordpress, como funcionan otros servidores que se pueden lazar desde python como flask o django. Puede ser relevante al momento de realizar un proyecto bioinformático y ponerlo a disposición de la comunidad.
- Front-end
- Back-end
- Dominio Web
- Servidor DNS
- Servidor Apache2
- Python-Flask

## Base de datos
Las bases de datos son esenciales para administrar datos y dar estructura a estos datos, el usos de bases de datos nos permite realizar consultas y poder análisis sofisticados de la información [Lectura de tipos de bases de datos](https://www.alooma.com/blog/types-of-modern-databases). Las bases de datos más populares en bioinformática:
- [MySQL](https://www.mysql.com)
- [MariaDB](https://mariadb.org)
- [MongoDB](https://www.mongodb.com/es)
- [Redis](https://redis.io)

## Virtualización
La virtualización se refiere a la capacidad de encapsular sistemas operativos como máquinas independientes donde configurar nuestros entornos de trabajo, realizar cálculos o levantar servicios. Aquellas que levantan computadores como máquinas totalmente autónomas son VMware y Virtualbox-Vagrant. Mientras otras más modernas se levantan en capas como son Docker.
- [VMware](https://www.vmware.com/cl.html)
- [VirtualBox](https://www.virtualbox.org)
- [Docker](https://www.docker.com)

## Computación en la nube.
Varios servicios de servidores o incluso de cluster de computación se pueden contratar directo desde proveedores con sus protocolos de autorización, estos posee costos asociados que dependiendo del uso pueden llegar a ser altos para un proyecto (usese con precaución).
- [Digital Ocean](https://www.digitalocean.com)
- [Amazon Cloud](https://aws.amazon.com/es)
- [Google Cloud](https://cloud.google.com)

## Administración de subversiones
EL manejo de subversiones se refiere o como se va mejorando o agregando información en forma continua para que un contenido se haga dinámico, estas herramientas están diseñadas para trabajar principalmente con texto. Gdocs posee un manejo de versiones anteriores, para textos que escribimos. Mientras para programas o sitios, es mejor utilizar Github, bitbucket también es una buena opción.
- [Gdocs](https://www.google.com/intl/es-419_cl/docs/about)
- [Github](https://github.com)
- [Bitbucket](https://bitbucket.org)