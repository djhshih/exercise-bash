# Whole-exome sequencing exercise

## Prerequisites

```
gsutil
bwa
samtools
bcftools
```

## Preparation

1. Install prerequisites.
2. Download the reference sequence in `ref`.

## Instructions

The paired-end DNA sequencing data are in `fq`.

1. Build a minimialistic pipeline to align the read pairs of tumour and normal
   samples to GRCh38 and identify somatic mutations in the tumour.
   Write good quality Bash scripts that can be re-used.
   Minimalize disk IO.
   (Hint: There are two real somatic mutations in this synthetic dataset.)

2. Describe how your pipeline can be modified to produce high quality mutation
   calls. Describe key steps that need to be added to the pipeline so that
   it can used in production.

