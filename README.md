# SESOI_IN

An R-based research and meta-analysis repository focusing on Smallest Effect Size of Interest (SESOI) analyses, 
utilizing empirical data from various experimental phonetics studies, originally published in:
Nicenboim, B., Roettger, T. B., & Vasishth, S. (2018). Using meta-analysis for evidence synthesis: The case of incomplete neutralization in German. Journal of phonetics, 70, 39-55.

## Repository Structure

The project is organized into a structured RStudio project layout:

* **`SESOI_IN.Rproj`**: RStudio project file for easy environment and dependency management.
* **`Original_Data/`**: Raw dataset files in TSV and CSV formats from historical and published literature.
* **`Derived_Data/`**: Processed and cleaned datasets prepared for statistical modeling.
* **`Script/`**: R scripts containing data wrangling, cleaning, and analysis workflows.
* **`Estimate_extraction/`**: Scripts and routines dedicated to extracting statistical estimates and effect sizes.
* **`Models/`**: Saved R model objects, including the primary meta-analysis model (`meta_analysis.rds`).
* **`Plots/`**: Output directory for generated visualizations.

## Included Studies (`Original_Data/`)

The repository aggregates data from multiple foundational studies in the field, including[cite: 9]:
* Fourakis & Iverson (1984)
* Grawunder (2014)
* Charles-Luce (1985)
* Greisbach (2001)
* Mitleb (1981)
* Piroth & Janker (2004)
* Port & Crawford (1989)
* Port & O'Dell (1985)
* Fuchs (2005)
* Roettger et al. (2014) (E1 & E2 production datasets)
* Baer-Henney & Roettger (2019) (E1 & E2)
* Overview study lists (`studies.tsv`) and tracking files (`issues.tsv`)
