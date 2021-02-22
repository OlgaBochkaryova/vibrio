# vibrio

This is the repository for Vibrio genomics project. The project includes phylogenetic reconstruction, comparative genomics of replicons,
reconstruction of orthologs evolution.

The project was performed by Kristina Perevoshchikova and Olga Bochkareva

## Folder Replicons:
 - ***StrainsTable.txt*** holds strains' IDs and names, chromosomes size, number of CDs
 - ***ChromosomesMapping.csv*** holds origin|terminus positions, replichores lengths, GC content
  - ***BurkholdeiraStrainsTable.csv*** holds strains' IDs and names, chromosomes size, number of CDs in Burkholderia genus


## Folder Phylogenetics:
 - ***int_nodes.nwk*** phylogenetic tree with labeled nodes
 - ***Vibrio.nwk*** phylogenetic tree with branch lengths and bootstraps
 - ***gene_trans_desc.csv*** transitions of orthologs between replicons
 - ***itol_beautiful_colors_out.txt*** species annotation for itol visualization


## Folder Orthologs:
 - ***gentable_wth_all_paralogs.txt*** table of orthologs with genes IDs
 - ***loctable_wth_all_paralogs.txt*** table of orthologs with genes localization

## Folder Paralogs:
 - ***Ref_ParalogsAll.tsv***  table of paralogs in gammaproteobacteria
 - ***Ref_paralogs_sequences.fasta*** aa sequences of paralogs in gammaproteobacteria
 - ***Ref_ParalogsStat.tsv*** statistics of paralogs in gammaproteobacteria
 - ***Vibrio_ParalogsAll.tsv***  table of paralogs in Vibrio genus
 - ***Vibrio_paralogs_first_sequences.fasta*** aa sequences of paralogs in the first chromosomes in Vibrio genus
 - ***Vibrio_paralogs_second_sequences.fasta*** aa sequences of paralogs in the second chromosomes in Vibrio genus
 - ***Vibrio_paralogs_cross_sequences.fasta*** aa sequences of paralogs placed in differnet chromosomes in Vibrio genus
 - ***Vibrio_ParalogsStat.tsv*** statistics of paralogs in Vibrio genus
