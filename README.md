
![Reproducibility](https://github.com/espm-157/fish-module-fu-goulden/workflows/Reproducibility/badge.svg)

## Team Members:

- Joclyn Fu, JoslynFu
- Phoebe Goulden, phoebeca

This project explores data on global fishery collapse.

## assignment

All work for this assignment is in the `assignment` directory. It includes our `.Rmd` notebook, and rendered output files (`.md` and associated files).

## Special files

Our repository also includes:

### Common files

- `README.md` this file, a general overview of the repository in markdown format.  
- `.gitignore` Optional file, ignore common file types we don't want to accidentally commit to GitHub. 
- `<REPO-NAME>.Rproj`An R-Project file created by RStudio for it's own configuration. 


### Infrastructure for Testing

- The Reproducibility badge above shows whether our build is passing. 
- `DESCRIPTION` a metadata file for the repository, based on the R package standard. It's main purpose here is as a place to list any additional R packages/libraries needed for any of the `.Rmd` files to run.
- `tests/render_rmds.R` an R script that is run to execute the above described tests, rendering all `.Rmd` notebooks. 




