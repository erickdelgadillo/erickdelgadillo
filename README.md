## Marine Molecular Ecologist & Computational Biologist

[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--9434--0211-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0000-0002-9434-0211)
[![Google Scholar](https://img.shields.io/badge/Google-Scholar-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=Q4wYPwwAAAAJ)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-Profile-00CCBB?logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Erick-Delgadillo-Nuno)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/delgadillo-erick/)

I'm a marine molecular ecologist and computational biologist working at the intersection of microbial ecology, molecular biology, and bioinformatics.

My research background focuses on marine microbial communities, particularly phytoplankton–bacteria interactions and their responses to environmental change. I combine this biological background with computational approaches for analysing high-throughput sequencing data.

Here you will find projects related to metatranscriptomics, metabarcoding, microbial community analysis, and reproducible bioinformatics, alongside tools and workflows I develop while expanding my computational toolkit.
##

<details>
<summary><strong> Featured projects</strong></summary>


## 🧬 [metatrans-dge](https://github.com/erickdelgadillo/metatrans-dge)

Reusable **Nextflow DSL2 workflow for differential gene expression analysis of metatranscriptomic count data**.

The workflow implements:

- edgeR quasi-likelihood differential expression
- configurable contrasts and significance thresholds
- TMM normalization
- volcano and MA plots
- differential-expression summaries
- top-feature visualization
- global expression heatmaps
- sample MDS and correlation analysis
- synthetic test datasets
- R-level testing
- Docker-based reproducible environments

`Nextflow` `R` `edgeR` `Docker` `Metatranscriptomics` `Testing`

---

## 🧬 [nf-human-variants](https://github.com/erickdelgadillo/nf-human-variants)

Modular **Nextflow DSL2 germline variant-calling workflow** developed to explore modern NGS workflow engineering and nf-core design principles.

Current components include:

- FastQC
- fastp
- BWA-MEM2
- SAMtools
- GATK reference preparation
- modular DSL2 subworkflows
- nf-core modules
- metadata-aware channels
- reproducible containerized execution
- lightweight test profiles

Variant calling and annotation components are under active development.

`Nextflow` `nf-core` `Docker` `BWA-MEM2` `SAMtools` `GATK`

---

## 🐆 [Ocelotl](https://github.com/erickdelgadillo/ocelotl)

Automated provisioning of a **reproducible bioinformatics workstation** using Ansible.

Ocelotl can configure a clean Ubuntu system with scientific and development tooling while keeping infrastructure configuration version-controlled and repeatable.

The project includes:

- modular Ansible roles
- Docker
- Conda / Mamba
- Nextflow
- R
- VS Code
- shell configuration
- idempotent provisioning
- GitHub Actions CI
- tagged releases

`Ansible` `Linux` `Docker` `Nextflow` `GitHub Actions` `Infrastructure as Code`

---

## 🌊 Reproducible marine science

### [dealing-with-p-metat](https://github.com/erickdelgadillo/dealing-with-p-metat)

Reproducible downstream analysis for a published metatranscriptomic study investigating **phosphorus deficiency in marine phytoplankton and bacteria**.

The repository contains curated analysis-ready datasets, provenance information, checksums, R workflows, and the code required to regenerate the published figures.

`R` `Metatranscriptomics` `Microbial ecology` `Reproducible research`

---

### [coastal-upwelling-metat](https://github.com/erickdelgadillo/coastal-upwelling-metat)

Metatranscriptomic and microbial-community analyses associated with research on **bacterioplankton functional specialization across coastal upwelling conditions**.

`R` `Metatranscriptomics` `Microbial ecology`

---

### [coastal-upwelling-oceanography](https://github.com/erickdelgadillo/coastal-upwelling-oceanography)

Reproducible MATLAB workflows for the physical and biogeochemical oceanography associated with the coastal-upwelling study.

Includes:

- CTD profiles
- nutrient distributions
- longitudinal transects
- restored historical workflows
- data provenance and checksums
- animated coastal–offshore sections

`MATLAB` `Oceanography` `Scientific visualization` `Reproducibility`

---


</details>


<details>
<summary><strong> Publications</strong></summary>

#### First-author publications

- **Delgadillo-Nuño E. et al. (2026).** Dealing with phosphorus deficiency: contrasting strategies in marine phytoplankton and bacteria. *ISME Communications*, **6**(1), ycag035. [DOI: 10.1093/ismeco/ycag035](https://doi.org/10.1093/ismeco/ycag035)

- **Delgadillo-Nuño E. et al. (2023).** Coastal upwelling systems as dynamic mosaics of bacterioplankton functional specialization. *Frontiers in Marine Science*, **10**, 1259783. [DOI: 10.3389/fmars.2023.1259783](https://doi.org/10.3389/fmars.2023.1259783) · [Correction (2026)](https://doi.org/10.3389/fmars.2026.1886620)


#### Selected collaborative publications

- **Teira E. et al. (2025).** Contrasting diversity and temporal patterns in leaf and root microbiome of two nearby temperate *Zostera marina* meadows. *Environmental Microbiome*, **20**, 98. [DOI: 10.1186/s40793-025-00760-z](https://doi.org/10.1186/s40793-025-00760-z)

- **Justel-Díez M. et al. (2025).** Effect of bacteria on the phytoplankton response to P-replete and P-deplete riverine water inputs. *Marine Environmental Research*, **211**, 107400. [DOI: 10.1016/j.marenvres.2025.107400](https://doi.org/10.1016/j.marenvres.2025.107400)

- **Costas-Selas C. et al. (2024).** Linking the impact of bacteria on phytoplankton growth with microbial community composition and co-occurrence patterns. *Marine Environmental Research*, **193**, 106262. [DOI: 10.1016/j.marenvres.2023.106262](https://doi.org/10.1016/j.marenvres.2023.106262)

- **Juárez O.E. et al. (2024).** Transcriptome characterization of *Pocillopora grandis* transplanted into reefs with different health conditions: potential stress indicators at the holobiont level. *Latin American Journal of Aquatic Research*, **52**(1), 119–149. [DOI: 10.3856/vol52-issue1-fulltext-2991](https://doi.org/10.3856/vol52-issue1-fulltext-2991)

- **Justel-Díez M. et al. (2023).** Inputs of seabird guano alter microbial growth, community composition and the phytoplankton-bacterial interactions in a coastal system. *Environmental Microbiology*, **25**(6), 1155–1173. [DOI: 10.1111/1462-2920.16349](https://doi.org/10.1111/1462-2920.16349)

- **Delgadillo-Nuño M.A. et al. (2023).** Two biomarkers of gene expression plasticity in *Pocillopora* corals from the Carrizales reef, Mexican Tropical Pacific. *Hidrobiológica*, **33**(2), 115–126. [DOI: 10.24275/aohh9236](https://doi.org/10.24275/aohh9236)

- **Delgadillo-Nuño M.A. et al. (2020).** Gene expression plasticity in *Pocillopora* corals from 2 locations on the Carrizales Reef, Pacific coast of Mexico. *Ciencias Marinas*, **46**(2), 89–100. [DOI: 10.7773/cm.v46i2.3062](https://doi.org/10.7773/cm.v46i2.3062)


</details>

<details>
<summary><strong> Technical toolkit</strong></summary>

### Workflow engineering

`Nextflow` · `nf-core` · `Git` · `GitHub Actions`

### Programming and analysis

`R` · `Python` · `MATLAB` · `Bash`

### Reproducible computing

`Docker` · `Apptainer` · `Conda` · `Mamba` · `Ansible` · `Linux`

### Bioinformatics

`FastQC` · `MultiQC` · `fastp` · `BWA-MEM2` · `Bowtie2` · `SAMtools` · `GATK` · `SPAdes` · `MEGAHIT` · `Trinity` · `Kraken2` · `MetaPhlAn` · `BLAST` · `HMMER`

### Data analysis

`edgeR` · differential expression · multivariate statistics · scientific visualization · microbial community analysis


</details>


