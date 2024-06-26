# StaPH-B: West Nile Virus Lineage 1a

## Authors
| Key                    | Value                                                                                                                                  |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------|
| authors                | Jade Wang (NYC DOHMH), Byeong Jeong (NJ DOH), Luc Gagne (MA DPH), Matthew Doucette (MA DPH), Sean SierraPatev (RI DOH)                 |
| data sources           | US Public Health Laboratories, WNV4k Project, NCBI Genbank                                                                             |
| workflow               | [github.com/jcw349/WNV-ns-global](https://github.com/jcw349/WNV-ns-global)                                                             |
| nextclade dataset path | community/staph-b/wnv/lineages-1a                                                                                                     |
| reference              | [NC_009942](https://www.ncbi.nlm.nih.gov/nuccore/158516887)                                                                            |
| root                   | [AF481864](https://www.ncbi.nlm.nih.gov/nuccore/AF481864)                                                                              |

## Background
The goal at Public Health Laboratories are to be able to rapidly determine West Nile virus (WNV) lineages and also be able to standardize nomenclature to track the evolution and characteristics of WNV. 
This Nextclade data use West Nile virus lineage 1 for genome annotations.

This data is intended to include all lineage 1a diversity that are published until the phylogenetic tree grows beyond manageable size. 

## Method

### Data
Sequence and metadata are collected from contributing public health laboratories, WNV4K Project, and NCBI Genbank.

#### Inclusion criteria:
- Sequences that are as published and inferred as lineage 1a
- ...?

#### Exclusion criteria:
- Sequences that are <=90% of reference sequence length are excluded
- ...?

#### Metadata:
| Column Names  | Description    |
|---------------|----------------|
| strain  | name representing the sequences reference sequences on the Nextclade    |
| date  | collection date    |
| country  | country from which the samples are collected    |
| state  | state, provincial, or regional names    |
| division  | location names representing the sites from which the samples are collected    |
| host  | scientific name of the host    |
| host-categories  | colloquial names of host    |
| clade_membership  | lineage/clade names that were published    |
| strain  | strains that represent subgroups within the lineage/clades    |
| organization  | organization that published the data    |
| DataSource  | sources from which the data was gathered    |
| latitude  | decimal latitude values of the collection sites represented by the value in division    |
| longitude  | decimal longitude values of the collection sites represented by the value in division    |

#### Nextstrain Build:
Followed [grubaughlab/WNV-nextstrain](https://github.com/grubaughlab/WNV-nextstrain) pipeline with some minor modifications to process the data collected from the above sources. 
Modified workflow for this nextclade build can be found here: [github.com/jcw349/WNV-ns-1a](https://github.com/jcw349/WNV-ns-global) 

#### Initial clade and strain designations:
Initial clade and strain memberships are designated in publications. References from which we retrieved the clade and strain names are listed below.
- Tamás Bakonyi et al provided a list of WNV lineages and clades with their sequences and strain names from Central Europe.
- Nisha K. Duggal et al describes co-evolution of WNV and house sparrows in North America including strain names and mutations.
- Fiona J. May et al describes phylogeography of WNV in Africa, Eurasia, Australia, and the Americas.
- R. Tobias Koch et al explores the genomic epidemiology of WNV in Europe

#### Lineage designation:
Used Autolin for lineage designation. Specifying the initial designations as the lineage/clade and strains that were previously designated in published literature.

## References
- Bakonyi T, Ivanics E, Erdélyi K, Ursu K, Ferenczi E, Weissenböck H, Nowotny N. Lineage 1 and 2 strains of encephalitic West Nile virus, central Europe. Emerg Infect Dis. 2006 Apr;12(4):618-23. doi: 10.3201/eid1204.051379. PMID: 16704810; PMCID: PMC3294705.
- Bakonyi T, Hubálek Z, Rudolf I, Nowotny N. Novel flavivirus or new lineage of West Nile virus, central Europe. Emerg Infect Dis. 2005 Feb;11(2):225-31. doi: 10.3201/eid1102.041028. PMID: 15752439; PMCID: PMC3320449.
- Duggal NK, Bosco-Lauth A, Bowen RA, Wheeler SS, Reisen WK, Felix TA, Mann BR, Romo H, Swetnam DM, Barrett AD, Brault AC. Evidence for co-evolution of West Nile Virus and house sparrows in North America. PLoS Negl Trop Dis. 2014 Oct 30;8(10):e3262. doi: 10.1371/journal.pntd.0003262. PMID: 25357248; PMCID: PMC4214623.
- Hadfield J, Brito AF, Swetnam DM, Vogels CBF, Tokarz RE, Andersen KG, Smith RC, Bedford T, Grubaugh ND. Twenty years of West Nile virus spread and evolution in the Americas visualized by Nextstrain. PLoS Pathog. 2019 Oct 31;15(10):e1008042. doi: 10.1371/journal.ppat.1008042. PMID: 31671157; PMCID: PMC6822705.
- Koch, R. T., Erazo, D., Folly, A. J., Johnson, N., Dellicour, S., Grubaugh, N. D., & Vogels, C. B. (2023). Genomic epidemiology of West Nile virus in Europe. One Health, 100664. ISSN 2352-7714, doi: 10.1016/j.onehlt.2023.100664
- May FJ, Davis CT, Tesh RB, Barrett AD. Phylogeography of West Nile virus: from the cradle of evolution in Africa to Eurasia, Australia, and the Americas. J Virol. 2011 Mar;85(6):2964-74. doi: 10.1128/JVI.01963-10. Epub 2010 Dec 15. PMID: 21159871; PMCID: PMC3067944.
-McBroome, J., de Bernardi Schneider, A., Roemer, C., Wolfinger, M. T., Hinrichs, A. S., O'Toole, A. N., Ruis, C., Turakhia, Y., Rambaut, A., & Corbett-Detig, R. (2024). A framework for automated scalable designation of viral pathogen lineages from genomic data. Nature microbiology, 9(2), 550–560. https://doi.org/10.1038/s41564-023-01587-5
