# tools
Processing scripts and pipelines that have been useful for me.

### fastqs_to_bam.sh
This provides our standard process for aligning paired-end fastq files to genomes in the Fishman Lab. It includes a bunch of stuff from GATK and Picard, so you'll want to make sure those paths are correct!

The general form of the command is
$ fastqs_to_bam.sh /file/path/fastqprefix /path/to/genome.fa [readGroup] [threads]
