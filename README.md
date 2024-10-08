# Timeliness of UKHSA datafeeds for mandatory reporting of HCAIs


This repo contains the `rmarkdown` code plus the knitted html file containing the analysis results used for the journal article "Understanding the timeliness of automated data feeds is important for determining their usability for large-scale surveillance of healthcare-associated infections". The data used for the analysis is hosted separately in [Zenodo](https://zenodo.org/doi/10.5281/zenodo.12805820).
All names of laboratories and health providers have been anonymised.


## Recreating the analysis

1. Clone the project and restore the `renv` lock file.

1. Download the data file "ukhsa_datafeeds_timeliness_anon.csv" from [https://zenodo.org/doi/10.5281/zenodo.12805820](https://zenodo.org/doi/10.5281/zenodo.12805820) into the root of the project.

1. Knit analysis.Rmd


## Acknowledgements

This project was funded by the National Institute for Health Research (NIHR) Health Protection Research Unit in Healthcare Associated Infections and Antimicrobial Resistance at Oxford University in partnership with the UK Health Security Agency (UKHSA) (NIHR200915), and supported by the NIHR Biomedical Research Centre, Oxford.
