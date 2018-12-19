The Excel file AlgaeWGMS_supplement_Cserhati_PGEVconf_2019.xls contains 5 tabs:

species: a list of the 42 species used in the study: name, larger taxonomic group, genome size, link to genome, 
number of significant motifs found by algorithm, and the number of the cluster assigned to it by the kmeans 
method in R.

CC value matrix: the matrix of Pearson correlation values for all species pairs for k-mers of length 8.

p-values: group number, number of species and p-values of the 12 clusters found by the kmeans method in R.
Out of these 12 clusters, only seven had a significant p-value, and at least 3 species.

12 clusters: name of species and number of cluster that it is assigned to.

motifs: list of motifs for each of the seven statistically significant clusters.
These motifs were found by calculating the mean and the standard deviation of the score values for all
motifs for the genome of a given species. Those motifs were selected which were at least two z-scores above
or below the mean motif score value (these correspond to a significance level of 5%).

The image file algae_wgms_heatmap.jpg depicts a heat map of the Pearson CC values calculated by the method.
The heat map depicts a square matrix, meaning that a CC value is depicted for each pair of species. 
The CC values range from 0 to 1, with lower CC values in lighter, yellowish colors, and higher CC values in
reddish colors.
