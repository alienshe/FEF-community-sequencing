Fastq files output by the ONT MiKnow software were filtered using the vsearch fastq_filter function to remove all reads with an error rate of more than .01, and all reads with length greater than 6kb or less than 1kb.

Porechop was then run on the filtered reads using the default parameters.

Reads were then clustered using the vsearch cluster_fast function. Minimum identity was set at .97, and the uclust-like output format was specified. 

The consensus sequences input as query sequences to BLAST+ using the blastn function, and the UNITE fungal ITS database as the database. Output format 6 was specified and the minimum E-value was set to 1e-100.

The output tables from blastn, along with the uclust-like output table from the clustering step were used as input for anlysis with phyloseq in R.
