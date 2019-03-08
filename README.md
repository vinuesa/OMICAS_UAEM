# Curso de OMICAS-UAEM-UNAM, m&oacute;dulo de Gen&oacute;mica

Este **minitaller sobre pan-genómica y filogenómica microbiana** lo imparto cada semestre en el [Centro de Ciencias Genómicas - UNAM](http://www.ccg.unam.mx) para alumnos de licenciatura, maestría y doctorado de la [Universidad Autómoma del Estado de Morelos (UAEM)](https://www.uaem.mx/) y de la [Universidad Nacional Autónoma de México (UNAM)](https://www.unam.mx/).

## Ediciones del Curso
- 1a. Febrero-Marzo 2017
- 2a. Octubre-Noviembre 2017
- 3a. Febrero-Marzo 2018
- 4a. Octubre-Noviembre 2018
- 5a. Febrero-Marzo 2019

Es a partir de la segunda edición que distribuyo públicamente el matrial did&aacute;ctico asociado a trav&eacute;s de este respositorio GitHub.

## Licencia y términos de uso
Este material did&aacute;ctico lo distribuyo bajo la [**Licencia No Comercial Creative Commons 4.0**](https://creativecommons.org/licenses/by-nc/4.0/)

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 </a>

### Clonaci&oacute;n del repositorio
Si tienes instalado [git](https://git-scm.com/) en tu computadora, puedes clonar el repositorio con todo el material del curso con el comando:

   <code>git clone https://github.com/vinuesa/OMICAS_UAEM.git</code>

En [ubuntu](https://www.ubuntu.com/) es muy f&aacute;cil instalar git: 

  <code>sudo apt install git</code>

***
 
## Presentaci&oacute;n

### El profesor
Hola, me llamo [Pablo Vinuesa](http://www.ccg.unam.mx/~vinuesa/). Soy investigador titular del 
[Centro de Ciencias Gen&oacute;micas](http://www.ccg.unam.mx) de la 
[Universidad Nacional Aut&oacute;noma de M&eacute;xico - UNAM](http://www.unam.mx/). 
Puedes seguirme en twitter [\@pvinmex](https://twitter.com/pvinmex).

Mis [l&iacute;neas de investigaci&oacute;n](http://www.ccg.unam.mx/~vinuesa/research.html) 
integran la genómica y la bioinformática con la biología y genética molecular para entender 
la evolución y emergencia de patógenos oportunistas a partir de microbios ambientales.

### ¿Dónde se imparten las clases?
Las clases se imparten en el sal&oacute;n 3 de la [LCG-UNAM](http://www.lcg.unam.mx), de 14 a 18 hrs, en los d&iacute;as indicados abajo.

***

## Temario
El  curso consta de tres temas. Cada uno tiene su bloque de teor&iacute;a y pr&aacute;cticas asociadas

### Tema 1: Introducci&oacute;n al bioc&oacute;mputo en sistemas GNU/Linux (22-02-2019)

Dado que generalmente el trabajo en genómica se realiza en servidores UNIX o GNU/Linux de alto rendimiento, 
es esencial familiarizarse con este ambiente de c&oacute;mputo al inicio de la formaci&oacute;n acad&eacute;mica. 
En consecuencia:

- todas las prácticas asociadas a este módulo se realizan en un servidor GNU/Linux
- iniciamos el módulo aprendiendo Linux

- [presentaci&oacute;n - PDF](https://github.com/vinuesa/OMICAS_UAEM/tree/master/docs/Intro2biocomputo_sistemas_en_sistemas_UNIX-Linux.pdf)

#### Pr&aacute;ctica 1. Primer contacto con un sistema GNU/Linux
- [pr&aacute;ctica1 - html](https://vinuesa.github.io/OMICAS_UAEM/intro2linux/)
- [pr&aacute;ctica1 - pdf](https://github.com/vinuesa/OMICAS_UAEM/tree/master/docs/intro2linux/working_with_linux_commands.pdf)

#### Pr&aacute;ctica 2. Descarga de secuencias en formato FASTA de GenBank usando el sistema ENTREZ y parseo de los archivos usando herrramientas de filtrado
- [pr&aacute;ctica2 - html](https://vinuesa.github.io/OMICAS_UAEM/practica2_parseo_fastas/)
- [pr&aacute;ctica2 - pdf](https://github.com/vinuesa/OMICAS_UAEM/tree/master/docs/practica2_parseo_fastas/ejercicio_parseo_fastas_ENTREZ.pdf)

#### Lecturas recomendadas
- Atma Ivancevic. The ten commandments for learning how to code. [Carrer Column, Nature, 20 Feb. 2019](https://www.nature.com/articles/d41586-019-00653-5)
- Velez Rueda AJ, Benítez GI, Marchetti J, Hasenahuer MA, Fornasari MS, Palopoli
N, Parisi G. Bioinformatics calls the school: Use of smartphones to introduce
Python for bioinformatics in high schools. [PLoS Comput Biol. 2019 Feb
14;15(2):e1006473.](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006473)
- Dudley JT, Butte AJ. A quick guide for developing effective bioinformatics
programming skills. [PLoS Comput Biol. 2009 Dec;5(12):e1000589](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000589)

### Tema 2:  Cómputo de homólogos a escala genómica y análisis de pan-genomas microbianos con GET_HOMOLOGUES (01-03-2019)
- [presentaci&oacute;n - PDF](https://github.com/vinuesa/OMICAS_UAEM/tree/master/docs/introduccion_a_la_pangenomica_microbiana_OMICAS-UAEM_Mar18.pdf)

#### Pr&aacute;ctica 2. Introducci&oacute;n a la pangenómica microbiana usando GET_HOMOLOGUES
- [manual GET_HOMOLOGUES](https://github.com/eead-csic-compbio/get_homologues) 
- [tutorial básico de GET_HOMOLOGUES - html](https://vinuesa.github.io/get_phylomarkers/)
- [código para práctica GET_HOMOLOGUES](https://github.com/vinuesa/OMICAS_UAEM/tree/master/docs/get_hom/code4_GET_HOMOLOGUES_OMICAS-UAEM-UNAM.txt)

#### Lecturas recomendadas
- Tettelin H, Riley D, Cattuto C, Medini D. Comparative genomics: the bacterial 
pan-genome. [Curr Opin Microbiol. 2008 Oct;11(5):472-7](https://www.sciencedirect.com/science/article/pii/S1369527414001830?via%3Dihub)
- Contreras-Moreira B, Vinuesa P. GET_HOMOLOGUES, a versatile software package
for scalable and robust microbial pangenome analysis. [Appl Environ Microbiol.
2013 Dec;79(24):7696-701.](https://aem.asm.org/content/79/24/7696.long)
- Vinuesa P, Contreras-Moreira B. Robust identification of orthologues and
paralogues for microbial pan-genomics using GET_HOMOLOGUES: a case study of
pIncA/C plasmids. [Methods Mol Biol. 2015;1231:203-32.](https://link.springer.com/protocol/10.1007%2F978-1-4939-1720-4_14)
- Contreras-Moreira B, Cantalapiedra CP, García-Pereira MJ, Gordon SP, Vogel JP,
Igartua E, Casas AM, Vinuesa P. Analysis of Plant Pan-Genomes and Transcriptomes 
with GET_HOMOLOGUES-EST, a Clustering Solution for Sequences of the Same Species.
[Front Plant Sci. 2017 Feb 14;8:184.](https://www.frontiersin.org/articles/10.3389/fpls.2017.00184/full)


### Tema 3: Estima de filogenias genómicas con GET_PHYLOMARKERS (08-03-2019)
Finalizamos el curso con una sesión de introducción a [GET_PHYLOMARKERS - html](https://vinuesa.github.io/get_phylomarkers/), 
un paquete de código fuente abierto para análisis filogenómico de genes del core genómico y de matrices pan-genómicas.

- [presentación - PDF](https://github.com/vinuesa/OMICAS_UAEM/tree/master/docs/get_phylomarkers_handout_4slidespp.pdf)

#### Pr&aacute;ctica 3. Introducci&oacute;n a la inferencia filogen&oacute;mica usando GET_PHYLOMARKERS
- [pr&aacute;ctica2 GET_PHYLOMARKERS - html](https://vinuesa.github.io/get_phylomarkers/)

#### Lecturas recomendadas
- Vinuesa P, Ochoa-Sánchez LE, Contreras-Moreira B. GET_PHYLOMARKERS, a Software
Package to Select Optimal Orthologous Clusters for Phylogenomics and Inferring
Pan-Genome Phylogenies, Used for a Critical Geno-Taxonomic Revision of the Genus 
Stenotrophomonas. [Front Microbiol. 2018 May 1;9:771.](https://www.frontiersin.org/articles/10.3389/fmicb.2018.00771/full)