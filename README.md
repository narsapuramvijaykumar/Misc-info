# Misc-info
General links and data related to bioinformatics and all lif science realted subjects

Random bash commands
for each in `ls -tlr */* | grep 'scaffold' | awk '{print $9}' | grep 'prediction.fa$' `;do grep -A 1 '>' $each | awk '{print $1"_"$2}'> $each"_mod";done
