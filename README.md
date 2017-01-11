# Larsen-etal_Alu_Neurodegeneration

generate_gene_set_FASTA_files.Rmd is an R markdown script that extracts intra-genic and flanking sequences for MitoCarta genes and 10 random sets of non-MitoCarta genes.
generate_gene_set_FASTA_files.RMD must be executed in the same directory as Human.MitoCarta2.0.Eids.csv.

The folder FASTA_files contains the intra-genic, upstream, and downstream FASTA files for the MitoCarta and 10 non-MitoCarta subsamples generated by generate_gene_set_FASTA_files.Rmd.
Files beginning with m_1_* refer to the MitoCarta gene sets, while s_#_* refers to the non-MitoCarta gene sets.  

The folder repeat_masker_output contains the output generated by running RepeatMasker on the FASTA files found in FASTA_files.  
RepeatMasker v. 4.0.6 (http://www.repeatmasker.org/) was used with the latest RepBase database of repeat elements v.20160829 (http://www.girinst.org/repbase/) and the RMBlast search engine 2.2.27 (http://www.repeatmasker.org/RMBlast.html).  
RepeatMasker was run on all FASTA files using the slow search –s option.  


