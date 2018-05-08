# gordon-square-gardens

The file "primers_and_conditions" lists the PCR and sequencing primers used, as well as the thermocycler conditions.

The file "OTU_table_commands" lists all commands used in QIIME to generate an OTU table via closed-reference OTU picking,
for both the Gordon Square Gardens and Central Park datasets. 

The file "97_otus.tre" is the tree used for closed-reference OTU picking.

Counts of sequences and observations (OTUs) per sample are available in both BIOM and table summary format, for the Gordon
Square Gardens, Central Park and merged datasets, respectively, as:
  gordon_square_otu_table.biom
  gordon_square_biom_table_summary.txt
  central_park_otu_table.biom
  central_park_biom_table_summary.txt
  merged_otu_table.biom
  merged_biom_table_summary.txt

Mapping files, containing metadata required for data analysis, for the Gordon Square Gardens, Central Park and merged
datasets are available, respectively, as:
  gordon_square_map.tsv
  central_park_map.tsv
  merged_map.tsv

The file "data_analysis_commands" lists all commands used for data analysis in QIIME. 

Unweighted UniFrac distances used to produce the boxplots are available in the file "box_plot_distances.txt".

Student's t test statistics for the boxplots are available in the file "box_plot_stats.txt". 


The output of diversity analysis and statistical analysis can be reproduced by running the commands listed in
"data_analysis_commands". 
