<!-- README.md is generated from README.Rmd. Please edit that file -->
BASEmetab
=========

Code accompanying Grace et al. (2015) Fast processing of diel oxygen curves: estimating stream metabolism with BASE (BAyesian Single-station Estimation). Limnology and Oceanography: Methods, 13, 103–114 <http://onlinelibrary.wiley.com/doi/10.1002/lom3.10011/full>

Currently the BASEmetab package contains just a single user function `bayesmetab`, which performs the above analysis.

See vignette and run `?bayesmetab` for details.
<https://github.com/dgiling/BASEmetab/blob/master/vignettes/BASEmetab.pdf>

Installation
============

The parameter estimation is performed with the JAGS software, which must be separately installed (Plummer
2003; http://mcmc-jags.sourceforge.net/). To install the BASEmetab package run the following code:

      # install devtools package
      install.packages(c("devtools"))

      # install BASEmetab package
        devtools::install_github("dgiling/BASEmetab")

        # Remove the package zip after installation
        unlink("BASEmetab.zip")
        
        #load library
        library(BASEmetab)
        
        #load R2jags to connect to JAGS
        library(R2jags)

Example
=======

See the help file associated with `bayesmetab`.

Developer
=========

Technical code prepared by Darren Giling <darren.giling@canberra.edu.au> Packaged by Nick Bond <n.bond@latrobe.edu.au>
