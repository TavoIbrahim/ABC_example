The directory ABC_scripts contains the prior distribution files (*.est) and the scenario files (*.par) used with ABCtoolbox and fastsimcoal. For each scenario, there is a .par file for nucleotide sequences (scX_asym_nuc.par) and another for microsatellite markers (scX_asym_str.par). I only put the scenarios with asymmetric migration, but it is pretty straightforward to modify the files to simulate scenarios with symmetric or no migration, by changing the migration matrices in the .par files.

The directory ABC_reftables contains the reference table for each model (parameters and simulated summary statistics – one line for each simulation).

The names of the parameters are slightly different than those used in the article.
DNA_MUT: mean nucleotide mutation rate
DNA_REC: mean nucleotide recombination rate
STR_MUT: mean microsatellite mutation rate
SD_MUT_M: standard deviation of the distribution for individual mutation rates
P: mean geometric parameter
ND_BOT/ ND_BOT_W/ ND_BOT_E: size of the domesticated population(s) at the time of domestication
ND_ADM_E/ ND_ADM_W: sizes of the domesticated populations at the time of admixture (sc4)
ND_NOW: current size of the domesticated population
NW_E/NW_W: sizes of the eastern and western wild populations
Md_we/Md_ww: migration from the domesticated population to the eastern and western wild populations
Mwe_d/Mww_d: migration from the eastern and western wild populations to the domesticated population 
Mww_we: migration between the wild populations
Md_w: migration from the domesticated population to the ancestral wild population (sc3)
Mw_d: migration from the ancestral wild population to the domesticated population (sc3)
Mde_we: migration from the eastern domesticated population to the eastern wild population before admixture (sc4)
Mdw_ww: migration from the western domesticated population to the western wild population before admixture (sc4)
Mwe_de: migration from the eastern wild population to the eastern domesticated population before admixture (sc4)
Mww_dw: migration from the western wild population to the western domesticated population before admixture (sc4)
tw: divergence time between the two wild populations
td/td_e/td_w: domestication time(s)
ta: time of the admixture between the two domesticated populations (sc4)

Summary statistics
They are indicated in the last 26 columns of each line. For each simulation, summary statistics for microsatellites (STR_XXX…) and nucleotide sequences (NUC_XXX…) have been computed. 
DOM: domesticated population, WW: western wild population, WE: eastern wild population
He: heterozygosity
He_sd: standard deviation of heterozygosity over loci
NGW: modified Garza-Williamson index
Fst: Fst values between populations
prS: number of private sites
D: Tajima's D
Pi: nucleotide diversity
