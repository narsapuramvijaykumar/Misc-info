# Misc-info
General links and data related to bioinformatics and all lif science realted subjects

Random bash commands
for each in `ls -tlr */* | grep 'scaffold' | awk '{print $9}' | grep 'prediction.fa$' `;do grep -A 1 '>' $each | awk '{print $1"_"$2}'> $each"_mod";done

#MSA vs PSA for sequence analysis
https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2524-4
To test the performance of MSA and PSA methods on protein sequence level, we presented a benchmark study of sequence alignment methods for protein clustering. Results showed that PSA methods performed much better than MSA methods on all the BAliBASE datasets. These indicated us that PSA methods were a better choice of dealing with protein sequence alignment analyses than MSA methods.

#BAliBASE
BAliBASE is specifically designed to serve as an evaluation resource to address all the problems encountered when aligning complete sequences. The database contains high quality, manually constructed multiple sequence alignments together with detailed annotations. The alignments are all based on three-dimensional structural superpositions, with the exception of the transmembrane sequences.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC29792/

Informative links
#################
Challenge participation --> http://www.spoj.com/problems/classical/sort=-6

Galaxy RNA-seq end-end
##########
https://galaxyproject.org/tutorials/rb_rnaseq/

