# Refseq-MLST

MLST overview of all NCBI refseq complete genomes for selected bacterial species

# Links to reports
* [Listeria monocytogenes] (https://cdn.rawgit.com/crarlus/refseq-MLST/master/mlst_report.html)


## Methods
1. Download NCBI's [assembly_summary](ftp://ftp.ncbi.nlm.nih.gov/genomes/refseq/bacteria/assembly_summary.txt)
2. Filter for `Complete Genome` and latest
3. Filter for species `Listeria_monocytogenes` 
4. Download genomes
5. Call [MLST](https://github.com/tseemann/mlst)


## References
* ftp://ftp.ncbi.nlm.nih.gov/genomes/refseq/bacteria
* https://github.com/tseemann/mlst
