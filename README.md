# 247.782 Special Topic in Computational Biology

This repository contains information and assignments for the course "Special
Topics in Computational Biology". 

## Course aims

This course is designed to get postgraduate students up to speed in
computational biology. The course includes hands-on practical examples of 
programming (using Python)  and data management in a unix envrionment. In
addition, the course will give students and opportunity to engage crtically with
published research in computatoinal biology and the opportunities and challanges
associated with genomic technologies. 

The specific learning outcomes are

1. Gain basic proficiency with the python programming language
2. Interpret and synthesise recent research papers in computational biology
3. Be able to explain and interpret research findings and critically asses
   research designs and computational methods.

## Assesment 

### Practical programming task 
**Due**: Week 4
**Weight**: 25%
**Task description**:

Clone this repository on to your computer. In the directory `task_1` you will
find two files, `ref.fna` is a very short reference genome and `reads.fq` are
fake sequencing reads aligned to this genome.

Your task is to write a python script that can be called from the command line
and 

1. Converts the records in fastq file to fasta format
2. Records the positions of bases in the reads that do no match the 
    corresponding position in the refernce in a vcf file.

**Assesment criteria**:

Writing a script that achieves this task will not be sufficient to earn a
passing grade. In addition to working the script should

1. Have a markdown README file that explains its usage, expected input files and
   output of the results.
2. Have comments explaining what functions and/or lines of code are doing
3. The script should be as flexible as possible, allowing users to specify
   different reference genomes or fastq files and produce the same result.
4. Make use your own functions to split the work required to do these steps into
   distinct 'modules'

You may use any pre-existing library, google as much as you like and read as
many stackoverflow or biostar questoins as it takes to get an answer to this
task. Some useful links include the [Software Carpentry
Lesson](http://swcarpentry.github.io/python-novice-inflammation/) on python, [the
Biopython project](https://biopython.org/) and the [codeacademy python
course](https://www.codecademy.com/learn/learn-python-3). You can dicuss your
progress on this assesment with colleagues and with David.

The VCF format is [formally defined here](https://samtools.github.io/hts-specs/VCFv4.2.pdf)[pdf],
though [the wikipedia page may offer a better
introduction](https://en.wikipedia.org/wiki/Variant_Call_Format). For our
purposes, we need only to use on the CHROM, POS, ID, REF and ALT columns. 

### Report with annotated bibliography 
**Due**: Week 6
**Weight**: 30%
**Task description**:

Prepare an annotated bibliography on a topic agreed on with David. The topic
should allow you to focus on papers with a computational biology angle, but need
not be a purely computational topic. 

The report should include a short narrative summary (no more than three single spaced
pages) of the research discussed. Under this short report, the bibliography
should include a short summary for a selection (15-20) of the cited papers. e.g.

Albertin, W., & Marullo, P. (2012). Polyploidy in fungi: evolution after whole-genome duplication. _Proc. Biol Sci_ 279:2497-2509. https://doi.org/10.1098/rspb.2012.0434 

>This review article explores the evolutionary consequences of polyploidy in fungi. The authors list poorly-accessible data among reasons why, at the time of this publication, fungal polyploidy remained largely disregarded by the general scientific community. They employ a number of case studies (particularly of species from the Saccharomyces genus, due to data availability), in combination with generalisations, to discuss both the factors capable of influencing genome size in fungi and the consequences of such variations. The authors describe the use of microarray platforms in the elucidation of gene expression variations in fungal polyploids, such as the identification of genes displaying non-additive expression in Saccharomyces cerevisiae strains with various ploidy levels. Moreover, they suggest a link between the ploidy level of Saccharomyces species and culture productivity, thus providing a plausible motive for polyploid research in this genus to-date, whilst also highlighting the need for future studies to focus on fungal polyploidy from an evolutionary perspective. Overall, this review provides generalisations and specific examples regarding the consequences of fungal polyploidy, in addition to suggested direction for future research.

**Assesment criteria**:

You will be assessed on your ability to summarise the research that you discuss.
You should find a mixture of papers (including reviews, pure research papers,
papers with more computational more more experimental focus etc). The brief
statements under each cited should clearly describe the findings and / or points
made in the paper, describe the tools used to achieve these findings. 

## Presentation

**Due**: TBC

**Weight** 25%

**Task Description**

Give a short presentation on the "challenges and opportunities" for transposable element research in fungi in 2020. The talk should describe how new sequencing technologies and computational methods contribute to TE biology, but also address shortcomings of current approaches.

** Assessment criteria **

The talk will be assessed on both the content of the talk and the style of your presentation. The total grade will consist of 5 points for each of **Introduction**, **Overall-content**, **Structure and slide design**, **Presentation style** and **Handling questions**. To achieve a very high grade, you should present a talk that draws on recently published papers to describe current state of TE research. The presentation should use simple slides, each with a clear message and it should be presented in an engaging style. Because I'll be marking this, [you can see what I think makes a good talk here](https://sciblogs.co.nz/the-atavism/2011/04/06/what-makes-a-great-scientific-talk/)! 
