# Final_project_Datahandlingandillustrationscourse
This is the repository for the final project assignment from the Data Handling and Illustrations course taken in Jan. 19-30, 2026.

## Objectives
The objectives of this assignment are to demonstrate the skills and knowledge the students have learned from the one week course in SLU Ultuna during Jan. 19-23.

## Contents
* Construct three geoms using ggplot using distinct data manipulation technics and data types
* Build one map
* Write a report in Quarto format that will be presented on Jan 30.

### Data used
The data used for the assignment are: 
* my own vegetation and GPS data collected from field work in 2024 and 2025.
* trait data extracted from the TRY database and Tyler et al. (2021).

The map was made using the software QGIS.
Graphs were made using the software R.

## Data availability
Trait data is readily available for request from try-db.org and in the Appendix A - Supplementary data 1 of Tyler et al. (2021) (DOI: https://doi.org/10.1016/j.ecolind.2020.106923).

Data from my PhD will not be made publicly availability until submission for publication.

## Set up

### Install and load packages
library(dplyr) #summarise, group_by, filter
library(ggplot2) #ggplot
library(tidyverse) #pivot_longer
library(forcats) #fct_reorder
library(patchwork)

> sessionInfo()
R version 4.5.2 (2025-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64
Running under: Windows 11 x64 (build 26100)

Matrix products: default
  LAPACK version 3.12.1

locale:
[1] LC_COLLATE=Swedish_Sweden.utf8  LC_CTYPE=Swedish_Sweden.utf8   
[3] LC_MONETARY=Swedish_Sweden.utf8 LC_NUMERIC=C                   
[5] LC_TIME=Swedish_Sweden.utf8    

time zone: Europe/Stockholm
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods  
[7] base     

other attached packages:
 [1] knitr_1.46      patchwork_1.3.0 lubridate_1.9.3 forcats_1.0.1  
 [5] stringr_1.5.1   purrr_1.0.2     readr_2.1.5     tidyr_1.3.2    
 [9] tibble_3.2.1    tidyverse_2.0.0 ggplot2_3.5.2   dplyr_1.1.4    

loaded via a namespace (and not attached):
 [1] vctrs_0.6.5        cli_3.6.2          rlang_1.1.7       
 [4] xfun_0.44          stringi_1.8.4      generics_0.1.4    
 [7] labeling_0.4.3     glue_1.8.0         hms_1.1.4         
[10] scales_1.4.0       fansi_1.0.7        grid_4.5.2        
[13] tzdb_0.4.0         lifecycle_1.0.4    compiler_4.5.2    
[16] RColorBrewer_1.1-3 timechange_0.3.0   pkgconfig_2.0.3   
[19] rstudioapi_0.16.0  farver_2.1.2       R6_2.5.1          
[22] tidyselect_1.2.1   utf8_1.2.4         pillar_1.9.0      
[25] magrittr_2.0.3     tools_4.5.2        withr_3.0.2       
[28] gtable_0.3.6 







