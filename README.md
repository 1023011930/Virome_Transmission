# Multi-site Virome Profiling in an Ovine Model
This repository contains code and analyses conducted in the manuscript **"Multi-site virome profiling reveals potential maternal–fetal viral transmission routes in an ovine model"**.

## Abstract
Early microbial colonization is essential for lifelong host health, yet the existence of in utero colonization remains controversial. Prior studies have reported sequence similarities between microbes from maternal and neonatal niches, suggesting potential vertical transmission routes. In this study, we employed a full-term lamb model delivered via sterile cesarean section to investigate prenatal intrauterine viral transmission. Initial non-concentrated metagenomic sequencing (NCS, n = 60) of prenatal fetal samples (meconium, amniotic fluid, placenta) and maternal samples (rumen contents, ileal contents, oral and vaginal swabs) from maternal–fetal pairs revealed limited viral operational taxonomic units (vOTUs) in fetal samples. Subsequent viral-like particle-concentrated virome sequencing (VPC) of multi-site samples from maternal–fetal pairs, adding negative controls and umbilical cord blood, was performed to enhance viral detection. After contamination exclusion, 13 fetal vOTUs–mainly Microviridae, Caudoviricetes, Rhabdoviridae, and Kitrinoviricota–were detected in 10 of 46 fetal samples, while 5,302 vOTUs were recovered from maternal samples. Analysis of viral transmission indicated the maternal gastrointestinal tract as the primary origin of fetal viromes, with no evidence of vaginal viral transmission. Evidence, including phylogenetic placement, synteny analysis, and selective viral mapping to Chlamydia prophage regions, indicated the presence of Chlamydiamicrovirus in matched maternal–fetal samples, supporting the possibility of prenatal viral transfer via the gastrointestinal–placental–umbilical axis**.

## Directory structure
- The clean and contaminated vOTUs sequence are deposited in figshare at https://doi.org/10.6084/m9.figshare.29614970.v1.
- `code/` – Scripts containing custom functions and core analytical workflows
  - `code/python/` – Python scripts (e.g., data parsing, viral detection pipelines)
  - `code/bash/` – Bash scripts (e.g., environment setup, batch job automation)
  - `code/R/` – R scripts (e.g., statistical analysis, visualization)
 
