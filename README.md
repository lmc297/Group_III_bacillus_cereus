# Group_III_bacillus_cereus
Supplementary material for the 2019-2020 cereulide-producing Group III *B. cereus s.l.* phylogenomics study

## Phylogenies

### GroupIII/ksnp3_outgroupAmes_core_SNPs_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using core SNPs identified among 71 emetic Group III *B. cereus s.l.* genomes 
and their closely related, non-emetic counterparts, plus outgroup genome *B. anthracis.* str. Ames. Core SNPs were 
identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### GroupIII/ksnp3_outgroupAmes_SNPs_in_majority0.5_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using majority SNPs identified among 71 emetic Group III *B. cereus s.l.* genomes 
and their closely related, non-emetic counterparts, plus outgroup genome *B. anthracis.* str. Ames. Majority SNPs were 
identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### GroupIII/ksnp3_outgroupGCF_002574215_core_SNPs_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using core SNPs identified among 71 emetic Group III *B. cereus s.l.* genomes 
and their closely related, non-emetic counterparts, plus outgroup genome *B. cereus s.l.* str. AFS057383. Core SNPs were 
identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### GroupIII/ksnp3_outgroupGCF_002574215_SNPs_in_majority0.5_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using majority SNPs identified among 71 emetic Group III *B. cereus s.l.* genomes 
and their closely related, non-emetic counterparts, plus outgroup genome *B. cereus s.l.* str. AFS057383. Majority SNPs were 
identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### Cluster1234/ksnp3_Cluster1234_outgroupCluster7_core_SNPs_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using core SNPs identified among 33 Group III *B. cereus s.l.* genomes 
assigned to RhierBAPS clusters 1-4, plus a cluster 7 outgroup genome. Core SNPs were identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### Cluster1234/ksnp3_Cluster1234_outgroupCluster7_SNPs_in_majority0.5_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using majority SNPs identified among 33 Group III *B. cereus s.l.* genomes 
assigned to RhierBAPS clusters 1-4, plus a cluster 7 outgroup genome. Majority SNPs were identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### Cluster1234/ksnp3_Cluster1234_outgroupCluster7_SNPs_all_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using all SNPs identified among 33 Group III *B. cereus s.l.* genomes 
assigned to RhierBAPS clusters 1-4, plus a cluster 7 outgroup genome. All SNPs were identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### Cluster123/ksnp3_Cluster123_outgroupCluster4_core_SNPs_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using core SNPs identified among 31 Group III *B. cereus s.l.* genomes 
assigned to RhierBAPS clusters 1-3, plus a cluster 4 outgroup genome. Core SNPs were identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### Cluster123/ksnp3_Cluster123_outgroupCluster4_SNPs_in_majority0.5_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using majority SNPs identified among 31 Group III *B. cereus s.l.* genomes 
assigned to RhierBAPS clusters 1-3, plus a cluster 4 outgroup genome. Majority SNPs were identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### Cluster123/ksnp3_Cluster123_outgroupCluster4_SNPs_all_matrix.fasta.treefile

Maximum likelihood phylogeny constructed using all SNPs identified among 31 Group III *B. cereus s.l.* genomes 
assigned to RhierBAPS clusters 1-3, plus a cluster 4 outgroup genome. All SNPs were identified using kSNP3, and the phylogeny was constructed using IQ-TREE/ModelFinder.

### ST26/snippy_TVMef5gamma_relaxed_bdsky_10burninLC_0burninTA_MCC_CAnodes.tree

Rooted, time-scaled maximum clade credibility (MCC) phylogeny constructed using core SNPs identified among 23 Group III *B. cereus s.l.* genomes belonging to sequence type (ST) 26. Core SNPs were identified using Snippy version 4.3.6. The phylogeny was constructed using the results of five independent runs using a relaxed lognormal clock model, the Standard_TVMef nucleotide substitution model with 5 gamma categories, and a serial Birth-Death Skyline population model implemented in BEAST version 2.5.1, with 10% burn-in applied to each run. LogCombiner-2 was used to combine BEAST 2 log files, and TreeAnnotator-2 was used to construct the phylogeny using common ancestor node heights. The phylogeny can be easily loaded into <a href="http://tree.bio.ed.ac.uk/software/figtree/">FigTree</a> to view node ages, node height highest posterior density (HPD) intervals, and other valuable metrics. If you would like to access the raw BEAST 2 log files used to create this tree, please <a href="https://github.com/lmc297/Group_III_bacillus_cereus/issues">create an issue with your contact information</a> so that we can arrange a way to send them to you (the log files are very large, and sadly cannot be hosted on GitHub!).

## Raw Data

### ST26/snippy_TVMef5gamma_relaxed_bdsky.xml

The raw BEAST 2 XML file used to construct ST26/snippy_TVMef5gamma_relaxed_bdsky_10burninLC_0burninTA_MCC_CAnodes.tree. If you would like to access the raw BEAST 2 log files produced by this XML, please <a href="https://github.com/lmc297/Group_III_bacillus_cereus/issues">create an issue with your contact information</a> so that we can arrange a way to send them to you (the log files are very large, and sadly cannot be hosted on GitHub!).

## Sample Scripts

### GroupIII/ancestral_state_ML_GroupIII.Rmd

R Markdown document describing how ancestral state reconstruction was performed for 71 de-replicated Group III *B. cereus s.l.* genomes.

### Cluster1234/ancestral_state_Cluster1234_outgroupCluster7.Rmd

R Markdown document describing how ancestral state reconstruction was performed for 33 Group III *B. cereus s.l.* genomes assigned to RhierBAPS clusters 1-4.

### Cluster123/ancestral_state_Cluster123_outgroupCluster4.Rmd

R Markdown document describing how ancestral state reconstruction was performed for 31 Group III *B. cereus s.l.* genomes assigned to RhierBAPS clusters 1-3.

### ST26/ancestral_state_beast_ST26.Rmd

R Markdown document describing how ancestral state reconstruction was performed for 23 *B. cereus s.l.* genomes assigned to sequence type (ST) 26. 


