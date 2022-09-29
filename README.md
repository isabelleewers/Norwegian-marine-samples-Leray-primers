# Norwegian marine samples COI diversity

[Leray et al. 2013](https://frontiersinzoology.biomedcentral.com/articles/10.1186/1742-9994-10-34):

- mlCOIintF GGWACWGGWTGAACWGTWTAYCCYCC
- jgHCO2198 TAIACYTCIGGRTGICCRAARAAYCA

## Statistical analysis

(see the Rmarkdown scripts, starting with
[src/01\_numerical\_ecology.Rmd](src/01_numerical_ecology.Rmd))

Note that library functions are noted as `package::function()` (for
example, `vegan::diversity()`), except for tidyverse functions and
base packages.


**Roadmap**:

- [ ] data check,
- [ ] filtering (only protists),
- [ ] rarefaction,
- [ ] beta diversity

for each taxonomic group in Dino, Diatoms, Haptophyta, Red Algae:

- [ ] filtering (only the target taxonomic group),
- [ ] rarefaction,
- [ ] beta diversity
