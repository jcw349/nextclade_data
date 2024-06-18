# StaPH-B: West Nile Virus All Lineages

## Authors
| Key                    | Value                                                                                                                                  |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------|
| authors                | [Jade Wang (NYC DOHMH)](email:jwang7@health.nyc.gov), [Byeong Jeong (NJ DOH)](email:), [Luc Gagne (MA DPH)](email:), [Matthew Doucette (MA DPH)](email:), [Sean SierraPatev (RI DOH)](email:)       |
| data source            | US Public Health Laboratories, WNV4k Project, NCBI Genbank                                                                             |
| nextclade dataset path | community/staph-b/wnv/lineages-all                                                                                                     |
| reference              | [NC_009942]([https://www.ncbi.nlm.nih.gov/nuccore/NC_001802](https://www.ncbi.nlm.nih.gov/nuccore/158516887)                           |

## Background
The goal at Public Health Laboratories are to be able to rapidly determine West Nile virus (WNV) lineages and also be able to standardize nomenclature to track the evolution and characteristics of WNV. 
This Nextclade data use West Nile virus lineage 1 for genome annotations.

This data is intended to include as many lineages and diversity as are published until the phylogenetic tree grows beyond manageable size. 

## Method

### Data
Sequence and metadata are collected from contributing public health laboratories, WNV4K Project, and NCBI Genbank.

#### Inclusion criteria:
-Sequences that are initially published as the representative lineages
- ...?
- 
#### Exclusion criteria:
-Sequences that are <=90% of reference sequence length are excluded
-...?

#### Metadata:
-strain: name representing the sequences reference sequences on the Nextclade
-date: collection date
-country: country from which the samples are collected
-state: state, provincial, or regional names
-division: location names representing the sites from which the samples are collected
-host: scientific name of the host
-host-categories: colloquial names of host
-clade_membership: lineage/clade names that were historically published
-strain_membership: strains that represent subgroups within the lineage/clades
-organization: organization that published the data
-DataSource: sources from which the data was gathered
-latitude: decimal latitude values of the collection sites represented by the value in division
-longitude: decimal longitude values of the collection sites represented by the value in division
