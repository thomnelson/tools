# tools
Processing scripts and pipelines that have been useful for me.

### fastqs_to_bam.sh
This provides our standard process for aligning paired-end fastq files to genomes in the Fishman Lab. It includes a bunch of stuff from GATK and Picard, so you'll want to make sure those paths are correct!

The general form of the command is
$ fastqs_to_bam.sh /file/path/fastqprefix /path/to/genome.fa [readGroup] [threads]

### getStacksCoverage.py

Use output files from the Stacks pipeline to collect per-sample and per-locus read coverage in a RADseq dataset. (For folks running Stacks v1.x).

### thomtools.py

This module contains a number of little functions that have been useful to me. A number of the functions are wrappers I used to run, e.g., ms and phase from within Python before I figured out better ways of doing that. But on the off-chance that they're useful to you, go nuts!
