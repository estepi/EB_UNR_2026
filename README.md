#  Análisis de datos de RNA-Seq con R/Bioconductor

Especialidad en Bioinformática - Universidad Nacional de Rosario
Fecha: 28 y 29 de septiembre de 2026
Lugar: Rosario, Argentina

# Descripción

Este curso combina fundamentos teóricos de RNA-Seq con práctica intensiva en el análisis, control de calidad e interpretación de datos de expresión génica. Está organizado en dos días, cubriendo desde la generación y control de calidad de los datos crudos hasta el análisis estadístico de expresión diferencial y su visualización.

# Requisitos previos

- Conocimientos de biología molecular (transcripción, expresión génica), de estadística básica
y fluencia con R/RStudio

- Antes de empezar, se recomienda tener instalado R, RStudio y los siguientes paquetes:

* [CRAN](https://cran.r-project.org/)
  - ggplot2
  - RColorBrewer
  - pheatmap
  - tidyverse
  - hexbin
  - kableExtra
  - gplots

```r
install.packages(c(
    "ggplot2",
    "RColorBrewer"))
```

- [Bioconductor](https://bioconductor.org/)
  - DESeq2
  - PCAtools
  - sva
  - edgeR
  - SummarizedExperiment
  - ExploreModelMatrix
  - AnnotationDbi
  - Biostrings
  - org.Hs.eg.db
  - org.Mm.eg.db
  - vsn
  - ComplexHeatmap
  - simplifyEnrichment

```r
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install(c(
    "DESeq2",
    "PCAtools"))
```

  

# Contenido del curso

## Día 1: Fundamentos de RNA-SEQ. Repaso R/RStudio,Bioconductor

* Sesión 1: Introducción general
* Sesión 2: Fundamentos de las tecnologías de secuenciación aplicadas al estudio del ARN
* Sesión 3: Bioinformática para RNAseq. Análisis e interpretación de control de calidad de un protocolo típico de RNA-Seq 
* Repaso de R/Bioconductor. OpenSciene, reportes MD
* [Sesión 4](s4.2.Rmd)

## Día 2: Análisis de datos de RNA-Seq con R/Bioconductor
* [Sesión 5](s5.Rmd): Diseño experimental y control de calidad inicial 
* [Sesión 6](s6.Rmd): Normalización y transformación de datos 
* [Sesión 7](s7.Rmd): Pruebas de expresión diferencial
* [Sesión 8](s7.Rmd): Enriquecimiento de conjuntos de genes y herramientas de visualización

# Objetivos de aprendizaje

Al finalizar el curso, los participantes serán capaces de:

1. Comprender los fundamentos de las tecnologías NGS aplicadas al ARN.
2. Localizar, descargar y depositar datos de expresión en repositorios públicos.
3. Evaluar la calidad de archivos FASTQ provenientes de experimentos de RNA-Seq.
4. Diseñar experimentos de RNA-Seq y aplicar controles de calidad iniciales.
5. Normalizar y transformar datos de expresión génica.
6. Realizar análisis de expresión diferencial utilizando R/Bioconductor.
7. Aplicar herramientas de enriquecimiento de conjuntos de genes y visualizar resultados.


# Contacto

Para dudas o comentarios sobre el curso, contactar a contact@estepi.com