FROM rocker/r:3.6.0
    
# Copy your repository contents to the image
USER root
COPY .${HOME}
COPY chown -R ${NB_USER} ${ceRNAnetsim}

USER ${NB_USER}

## Run an install.R script, if it exists.
RUN R --quiet -e "devtools::install_github('selcenari/ceRNAnetsim')" 
