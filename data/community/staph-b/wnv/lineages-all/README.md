# StaPH-B: West Nile Virus All Lineages

## Authors
| Key                    | Value                                                                                                                                  |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------|
| authors                | Jade Wang (NYC DOHMH), Byeong Jeong (NJ DOH), Luc Gagne (MA DPH), Matthew Doucette (MA DPH), Sean SierraPatev (RI DOH)                 |
| data source            | US Public Health Laboratories, WNV4k Project, NCBI Genbank                                                                             |
| workflow               | [jcw349/nextstrain/wnv-ns-global/](https://www.github.com/jcw349/nextstrain/wnv-ns-global/)                                                                                                       |
| nextclade dataset path | community/staph-b/wnv/lineages-all                                                                                                     |
| reference              | [NC_009942](https://www.ncbi.nlm.nih.gov/nuccore/158516887)                                                                            |

## Background
The goal at Public Health Laboratories are to be able to rapidly determine West Nile virus (WNV) lineages and also be able to standardize nomenclature to track the evolution and characteristics of WNV. 
This Nextclade data use West Nile virus lineage 1 for genome annotations.

This data is intended to include as many lineages and diversity as are published until the phylogenetic tree grows beyond manageable size. 

## Method

### Data
Sequence and metadata are collected from contributing public health laboratories, WNV4K Project, and NCBI Genbank.

#### Inclusion criteria:
- Sequences that are initially published as the representative lineages
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
| strain_membership  | strains that represent subgroups within the lineage/clades    |
| organization  | organization that published the data    |
| DataSource  | sources from which the data was gathered    |
| latitude  | decimal latitude values of the collection sites represented by the value in division    |
| longitude  | decimal longitude values of the collection sites represented by the value in division    |

#### Nextstrain Build:
Followed [grubaughlab/WNV-nextstrain](https://github.com/grubaughlab/WNV-nextstrain) pipeline with some minor modifications to process the data collected from the above sources.

#### Lineage designation:
Used Autolin for lineage designation. Specifying the initial designations as the lineage/clade and strains that were previously designated in published literature.

## References
- ...
