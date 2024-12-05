# Saccharomyces cerevisiae MDH1

# Uniprot ID: P17505
# Variation: phosphorylation of S177 (pS160 in structure)



## Description

Serine 177 of yeast MDH1 was identified as a post-translationally modified site by [Reinders and coworkers](https://pubmed.ncbi.nlm.nih.gov/17761666/) in 2007. The study identified proteins with a role in the assembly of ATP synthase and energy metabolism.  This modification site is not conserved in human MDH2 [(P40926)](https://www.uniprot.org/uniprotkb/P40926/entry) 
and there are no functional studies of the role of this site in yeast metabolism. 
*Entry started 10/21/2024 CEB*

# Comparison of MDH1 models and phospho modified MDH1

1. Alignment of MDH1, MDH1 with phosphoS 177 (orange), and S177D (magenta)
![Alignment of MDH1, MDH1 with phosphoS 177, and S177D](images/align.png){: width = "200px"}


2. Modification site alignment within MDH1
![alt text](images/site.png)

The modification site is near to R174 and E178 and could make ionic or hydrogen bonding interactions with both of those side chains when modified. 

## Effect of the sequence variant and PTM on MDH dynamics

The RMSD of the final frame from MD simulations of MDH1 and MDHS177D was 0.76 Å. The unmodified MDH1 is shown in green while the modified form is shown in purple. 
![alt text](images/md_align.png)


After simulation, the overall protein structures are similar as well as the area surrounding the modification sites. A solvent sodium ion has moved close and is forming an ionic interaction with the D in position 177. D177 also is making contact with R174. Neither of these interactions are observed in the unmodified enzyme.


![alt text](images/md_site.png)

### Comparison of the enzyme dynamics
After simulation, the dynamics as described by the root mean square fluctuation (RMSF) value were compared. In the plot, there are differences between the unmodified (purple) and S177D (green) around amino acids 400 and 500. These sites are loops bordering the active site. The difference around residue 400 is the active site loop which is key for binding the carboxylic acid substrate. The vertical line indicates the end of one subunit and the beginning of the next subunit of the MDH1 dimer.

![alt text](images/rmsf_compare.png)

The loops sites are shown below in blue with stick representations. The upper grouping is the active site loop. The yellow ellipse shows the approximate bind sites of the carboxylic acid and NAD+ substrates.

![alt text](images/loop_sites_active.png)


### Effect of modification on the pKa values

Overall the modification did not affect the pKa values of the active site histidine. There are only minor differences in the spread of the data over the simulation which may be due to equilibration. 
![alt text](images/pka_over_traj.png)


## Comparison of the mimic and the authentic PTM
The RMSD MDHS177D and phosphoS177 MDH1 was 0.48 Å. The overall structures are similar with no major differences in structure or position.

![alt text](images/mod_compare.png)

## Authors

Christopher E. Berndsen

## Deposition Date
10/21/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg

## References

* Reinders, Jörg, et al. “Profiling Phosphoproteins of Yeast Mitochondria Reveals a Role of Phosphorylation in Assembly of the ATP Synthase.” Molecular & Cellular Proteomics: MCP, vol. 6, no. 11, Nov. 2007, pp. 1896–906. PubMed, https://doi.org/10.1074/mcp.M700098-MCP200.
