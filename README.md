# INSTALL
### For R 2.15 with git version *ggbio*
Install of developmental version of *ggbio* require developmental R now. 
Simply open *R* session and run the following code:

    source("http://www.tengfei.name/projects/ggbio/utils/installer.R")
    
This will install ggplot2/ggbio github version, and bioc-dev version 
denpendencies.

### For R 2.14 with git version *ggbio*
__not supported yet__

### For R-dev or released R with conresponding *bioconductor* version *ggbio*

    source("http://bioconductor.org/biocLite.R")
    biocLite("ggbio")

__This is currently now working due to the new-yet-unreleased ggplot2 0.9__

