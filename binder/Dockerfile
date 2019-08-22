FROM rocker/tidyverse:3.6.0
    
# Copy your repository contents to the image
COPY .${HOME}

## Run an install.R script, if it exists.
RUN R --quiet -e "devtools::install_github('selcenari/ceRNAnetsim_binder')" 
