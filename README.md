# Marquilly_et_al_2020
Statistical analyses for the article by [Marquilly et al. (PLoS Genetics, 2020)](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1009287).

Comparison of control, Df/+, ko/+, int/+, RNAi/+ and int+UAS (figure 1E):

``R CMD BATCH R_commands_multiple_Fisher``

(the published figure uses the results of Fisher's exact test with Bonferroni correction)


Comparison of UAS, UAS/int and +UAShtt (figure 4D):

``R CMD BATCH R_commands_multiple_Fisher3``

(the published figure uses the results of Fisher's exact test with Bonferroni correction)
