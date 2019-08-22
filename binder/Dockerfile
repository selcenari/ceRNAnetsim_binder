FROM rocker/binder:3.6.0
    
# Copy your repository contents to the image
COPY --chown=rstudio:rstudio . ${ceRNAnetsim}

## Run an install.R script, if it exists.
RUN R --quiet -e "devtools::install_github('selcenari/ceRNAnetsim')" 
