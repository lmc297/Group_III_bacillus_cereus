# Group_III_bacillus_cereus
Supplementary material for the 2019-2020 cereulide-producing Group III *B. cereus s.l.* phylogenomics study

## Files and Descriptions

### ksnp3_outgroupAmes_core_SNPs_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using core SNPs identified among 71 emetic Group III *B. cereus s.l.* genomes 
and their closely related, non-emetic counterparts, plus outgroup genome *B. anthracis.* str. Ames. Core SNPs were 
identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### ksnp3_outgroupAmes_SNPs_in_majority0.5_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using majority SNPs identified among 71 emetic Group III *B. cereus s.l.* genomes 
and their closely related, non-emetic counterparts, plus outgroup genome *B. anthracis.* str. Ames. Majority SNPs were 
identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### ksnp3_outgroupGCF_002574215_core_SNPs_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using core SNPs identified among 71 emetic Group III *B. cereus s.l.* genomes 
and their closely related, non-emetic counterparts, plus outgroup genome *B. cereus s.l.* str. AFS057383. Core SNPs were 
identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### ksnp3_outgroupGCF_002574215_SNPs_in_majority0.5_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using majority SNPs identified among 71 emetic Group III *B. cereus s.l.* genomes 
and their closely related, non-emetic counterparts, plus outgroup genome *B. cereus s.l.* str. AFS057383. Majority SNPs were 
identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### snippy_relaxed_skyline_10burnin_MCC_CAnode_10burninLC_0burninTA.tree

Rooted, time-scaled maximum clade credibility (MCC) phylogeny constructed using core SNPs identified among 64 Group III *B. cereus s.l.* genomes belonging to sequence type (ST) 26. Core SNPs were identified using Snippy version 4.3.6. The phylogeny was constructed using the results of ten independent runs using a relaxed lognormal clock model, the Standard_TVMef nucleotide substitution model, and a coalescent Bayesian skyline population model implemented in BEAST version 2.5.0, with 10% burn-in applied to each run. LogCombiner-2 was used to combine BEAST 2 log files, and TreeAnnotator-2 was used to construct the phylogeny using common ancestor node heights. The phylogeny can be easily loaded into <a href="http://tree.bio.ed.ac.uk/software/figtree/">FigTree</a> to view node ages, node height highest posterior density (HPD) intervals, and other valuable metrics. If you would like to access the raw BEAST 2 log files used to create this tree, please <a href="https://github.com/lmc297/Group_III_bacillus_cereus/issues">create an issue with your contact information</a> so that we can arrange a way to send them to you (the log files are very large, and sadly cannot be hosted on GitHub!).
