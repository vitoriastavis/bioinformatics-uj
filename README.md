# Title
Laboratory of Bioinformatics and Genome Biology - Jagiellonian University, Cracow, Poland

# Introduction 
Insects, in general, are a good model to study genomics and transcriptomics, as well as easy to manage and take care of.
Amongst the non-coding RNA, there are piRNAs, which have 24-31 nt. and interact with piwi-subfamily Argonaute proteins. They are only found in animals so far, especially in the germ cells, where they protect the DNA from transposable elements and other genetic elements. 
piRNAs can also be expressed in somatic cells, but their role has not been fully comprehended.
In addition, the european cockroach, *Blattella germanica*, can be a model to study piRNA and their funcion.

# Objectives
The RNA from *Blatella germanica* was extracted and two companies, BGI and Novogene, performed rRNA depletion and sequencing of non-coding RNA.
The first objective is to compare the sequencing from BGI and Novogene....


# Methodology

## Data
The data consists in 3 groups per company: long RNA forward, long RNA reversed and short RNA
First of all, FastQC was run to check the quality of reads. The generated html reports can be seen in the folder 1-fastqc, for long1, long2 and short RNAs.
Then, trimming of adapters was made in the sequences from Novogene, since they did not send the clean data.
The trimming was made with Trimmomatic and Trim galore! in order to verify the efficiency of both methods.
...
