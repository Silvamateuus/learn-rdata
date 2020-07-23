# Estudo da linguagem R

## Passos de instalação RStudio linux:

    $ apt-get install r-base r-base-dev
    
    $ sudo apt-get install gdebi-core
    
    $ wget https://download2.rstudio.org/server/xenial/amd64/rstudio-server-1.3.1056-amd64.deb

    $ sudo gdebi rstudio-server-1.3.1056-amd64.deb

## Instalação dos pacotes:

    $ sudo apt-get install -y --allow-downgrades libxcb1
    
    $ sudo apt-get install -y --no-install-recommends \
        libssl-dev \
        libpq-dev \
        libz-dev \
        curl \
        openssl \
        libcurl4 \
        libcurl4-openssl-dev \
        libxml2-dev \
        libglu1-mesa-dev \
        libfreetype6-dev 
            
        
    $ sudo R
        install.packages("Rccp")
        install.packages("rlang")
        install.packages("BH")
        install.packages("later")
        install.packages("magrittr")
        install.packages("R6")
        install.packages("promises")
        install.packages("httpuv")
        install.packages("shiny")
        install.packages("rgl")
        install.packages("kml")
        install.packages("xml2")
        install.packages("curl")
        install.packages("httr")
        install.packages("aws.signature", repos = c("cloudyr" = "http://cloudyr.github.io/drat"))
        install.packages("RJSONIO")
        install.packages("MASS")
        install.packages("openxlsx")
