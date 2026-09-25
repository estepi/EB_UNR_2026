#  Análisis de datos de RNA-Seq con R/Bioconductor

## Especialidad en Bioinformática - Universidad Nacional de Rosario

### 📅 Fecha: 28 y 29 de septiembre de 2026

### 📍 Localización: Facultad de ciencias Agrarias, UNR Zavalla, Argentina

# Descripción

Este curso combina fundamentos teóricos con práctica intensiva en análisis de datos de RNA-Seq. 
Está organizado en dos días, el contenido recorre los principales pasos en el protocolo de la generación y el posterior análsisi estadistico de los datos de RNA-Seq

# ✅ Requisitos Previos

- Conocimientos de biología molecular (transcripción, expresión génica), de estadística básica
y buen nivel de  R/RStudio

- Se recomienda tener instalado R, RStudio y los siguientes paquetes:

## [CRAN](https://cran.r-project.org/)

* ggplot2, RColorBrewer, pheatmap, tidyverse, hexbin, kableExtra, gplots, Cairo

### Función para instalar:

```r
install.packages(c(
    "ggplot2",
    "RColorBrewer"))
```

## [Bioconductor](https://bioconductor.org/)

- DESeq2, PCAtools, sva, edgeR, SummarizedExperiment, ExploreModelMatrix, AnnotationDbi, Biostrings, org.Hs.eg.db, org.Mm.eg.db, vsn, ComplexHeatmap, simplifyEnrichment, GSEABase, apeglm, clusterProfiler

### Función para instalar:

```r
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install(c(
    "DESeq2",
    "PCAtools"))
```

## 🗓️ Agenda

# Contenido del curso

## Día 1: Fundamentos de RNA-SEQ

* Sesión 1: Introducción general del curso
* Sesión 2: Fundamentos de las tecnologías de secuenciación aplicadas al estudio del ARN (RNA-Seq)
* Sesión 3: Bioinformática para RNA-Seq. Análisis e interpretación de control de calidad de un protocolo típico de RNA-Seq 
* [Sesión 4](s4.2.Rmd): Repaso de R/Bioconductor. OpenSciene, protocolos FAIR, reportes Markdown

## Día 2: Análisis de datos de RNA-Seq con R/Bioconductor
* [Sesión 5](s5.Rmd): Diseño experimental y control de calidad de datos de expresión génica
* [Sesión 6](s6.Rmd): Normalización y transformación de datos 
* [Sesión 7](s7.Rmd): Pruebas de expresión diferencial
* [Sesión 8](s8.Rmd): Enriquecimiento de conjuntos de genes y herramientas de visualización

## Consulta por trabajo final: 05 de noviembre de 2026, Aula virtual

## Entrega trabajo final: 05 de diciembre de 2026

# 🎯 Objetivos de aprendizaje

Al finalizar el curso, los alumonos serán capaces de:

1. Comprender los fundamentos de la tecnología de RNA-Seq
2. Localizar, descargar y depositar datos de expresión en repositorios públicos.
3. Evaluar la calidad de archivos FASTQ provenientes de experimentos de RNA-Seq.
4. Diseñar experimentos de RNA-Seq y aplicar controles de calidad iniciales.
5. Normalizar y transformar datos de expresión génica utilizando R/Bioconductor.
6. Realizar análisis de expresión diferencial utilizando R/Bioconductor.
7. Aplicar herramientas de enriquecimiento de conjuntos de genes y visualizar resultados.

# 📖 Bibliografía
- [frontiers](https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2025.1697922/full)
- [nature](https://www.nature.com/articles/s41576-019-0150-2)
- [pmc](https://pmc.ncbi.nlm.nih.gov/articles/PMC3904521/pdf/btt688.pdf)
- [springer](https://link.springer.com/article/10.1186/s13059-016-0881-8)
- [FAIR](FAIR: https://www.cell.com/current-biology/fulltext/S0960-9822(23)00668-1)
- [xx](https://www.nature.com/articles/sdata201618)
- [nature](https://www.nature.com/articles/nprot.2013.099)

# 📚 Lecturas Recomendadas

- [Open and sustainable AI: challenges, opportunities and the road ahead in the life sciences]()
- [Rethinking bioinformatics expertise in the era of artificial intelligence]()
- [DESeq2 vignette]()
- [RNA-seq workflow: gene-level exploratory analysis and differential expression]()
- [edgeR Users Guide , edgeR vignette]()
- [Introduction to DGE - normalization]() 
- [RNA-Seq analysis with R/Bioconductor - Carpentries]()
- [Analyzing RNA-seq data with DESeq2]()

# ✉️ Consultas

Para dudas o comentarios sobre el curso, contactar a contact@estepi.com

