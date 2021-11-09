# QSPipeline

QSPipeline is a pipeline to detect viral quasispecies in NGS data. It is based in R and can be run via RStudio or via command-line script. It is compatible with Linux, Mac OS and Windows.

## Table of contents

1. [The QSPipeline workflow](#workflow)
2. [Dependencies](#dependencies)
3. [Installation](#installation)
4. [Usage](#usage)

## The QSPipeline workflow <a name="workflow"></a>

FIGURE

The image above shows the workflow the user should follow to obtain the viral quasispecies present in its samples:

  1. Check metadata: to verify primer descriptors and files for pools in run.
  2. Quality assesment: to analyze samples' quality.
  3. QSPipeline: to obtain quasispecies present in the samples after applying quality, similarity and abundance filters.

## Dependencies <a name="dependencies"></a>

To run QSPipeline, several R libraries are required:

  * [Biostrings](https://bioconductor.org/packages/release/bioc/html/Biostrings.html)
  * [ShortRead](https://bioconductor.org/packages/release/bioc/html/ShortRead.html)
  * [data.table](https://cran.r-project.org/web/packages/data.table/)
  * [stringr](https://cran.r-project.org/web/packages/stringr/)
  * [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/)
  * [optparse](https://cran.r-project.org/web/packages/optparse/)

FLASH of Illumina is required too, but it is provided in this repository.

## Installation <a name="installation"></a>

Clone the QSPipeline repository in directory of your choice:

```
git clone https://github.com/bsorianos/QSPipeline.git
```

Or download it directly from GitHub QSPipeline page.

This repository includes:

  * a folder called R which includes several scripts needed to run the pipeline.
  * this README file
  * the LICENSE file

## Usage <a name="usage"></a>

https://github.com/alesssia/MAP#example
