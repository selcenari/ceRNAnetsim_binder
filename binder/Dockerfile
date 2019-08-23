FROM rocker/tidyverse:3.6.0
    
COPY --chown=rstudio:rstudio . ${HOME}

## Run an install.R script, if it exists.
RUN R -e "devtools::install_github('selcenari/ceRNAnetsim')" 
## RUN ~/install.R
