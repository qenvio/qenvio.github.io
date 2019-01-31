
# Simple statistical models for complex 3D genome data

> Taking advantage of statistical models to deal with tricky Hi-C data

## Abstract


Spatial organization of the genome plays a key role in living cells. Thanks to
the 3C technologies we are able to interrogate the chromatin structure. But the
answers are not always easy to interpret. Data from conformation experiments
present different sources of variation. Although some of them are relevant,
others can be seen as undesired biases. Besides, aberrant karyotypes can distort
Hi-C maps. In this situation, we aim to rule out biases before extracting useful
information.
 
We present OneD, a model-based strategy that captures the main sources of
unwanted variation. Used to remove biases, it improves sample
reproducibility. Thanks to its properties, we can increase computational
efficiency. This paves the road to a deep (high resolution) and broad
(genome-wide) analysis of the genome structure. Finally, our approach can handle
aneuploidies and also estimate copy number alterations.


## Random thoughts

- Hi-C has biases

- identify and reduce the problem, summarize the data, extract general patterns.

- explicit model requires knowing your data and making assumptions, but offers advantages

- go one step backwards and interrogate the model

- model checking

- model metrics as quality control

- estimation of copy number


## Take home messages


### General

- Hi-C data present biases

- Explicit modeling can help to reduce them

- Exploit models

### OneD specific

- Increases reproducibility

- Fast and scalable ("resolution free")

- Suitable for aberrrant karyotypes


## Story

Working in the 4DGenome project, born in 2014

Fucusing on computational and statistical aspects around 3C techniques (mostly
Hi-C)


Genome is not randomly packed inside the nucleus

3C as a useful approach to interrogate genome structure

Hi-C






## Intro

- Importance of chromatin structure

- Hi-C as a technique to interrogate structure

- Identify main sources of variation

- Model based

- GAM, splines

- Bias in Hi-C experiments

- Aggregate data to estimate patterns

- Subset in space and resolution

- Model metrics as quality control

- Reduce the problem: 4D -> 3D -> 2D -> 1D

- Negative binomila to deal with overdispersion

- Aberrant karyotypes

## Outro




